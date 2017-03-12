---
layout: article
title: Preferences
permalink: /preferences/
---

You can see and change your preferences in the "Preferences" tab in Settings. To open Settings, click on the gear in the top right corner.

There are two main types of preference: appearance and input.

## Appearance

#### Theme

Dynalist has three themes right now: default, dark, and sepia. If your room is dark, using dark theme is easier on your eyes. If you read a lot on Dynalist, the sepia theme might be better for your eyes than the default theme.

This setting defaults to Default (yeah right).

#### List density

You can control how much margin you'd like between two items. Compact is the tightest setting, and Comfortable is the loosest setting.

This setting defaults to Cozy.

#### Tag background color

To make tags stand out a little, turn on this setting. A light blue background (in default theme) or a dark grey background (in dark theme) will be applied to all tags.

This setting is turned off by default.

#### Document border

Turn it off if you don't like the light grey border around your document.

This setting is turned on by default.

#### Highlight current item

Turn on this setting if you want to know which item you're editing right now. This can be hard as you have to look for the blinking caret. Turning on this setting will show a light background behind the current item, making it easy to find.

This setting is turned off by default.

#### Center align document

When the document is center aligned, there are significant margins on the left and right side of the document. If you want to fit more text on the same screen space, you can turn it off. The possible drawback is that longer lines are usually harder to read.

This setting is turned on by default.

#### Display images inline

Turn on this setting if you want image markdown to show up as an inline image rather than a previewable link.

The setting is turned off by default.

## Font options

#### Font size

Choose from Small, Medium, and Large. If it's still readable to you, you can set it to smaller to display more text on the same screen space.

This setting defaults to Medium.

#### Font

There are 8 built-in fonts in Dynalist right now. For serif font (think Times New Roman), go for Lora. For a monospace font for code, choose Consolas.

This setting defaults to Whitney.

#### Eastern-asian font

If you write in Chinese, Japanese, or Korean, you can make use of this option to make your characters look better. This font will only be used on non-English text, so don't worry about English looking ugly in the eastern-asian font.

There are two options for each language, with one being serif and the other being sans serif.

This setting defaults to Microsoft Yehei.

#### Font for dyslexia

If you have dyslexia, try out this option by choosing Open Dyslexic. It's designed to make reading easier for people with dyslexia.

If you like how it looks, you can [download this font for free](http://opendyslexic.org/).

This setting defaults to None.

## Input

#### Enable spell checker

Turning this on will enable your browser's built-in spell checker. When a typo is spotted, a red squiggly line will show up underneath it.

This settings is turned off by default, although we're strongly considering making it be on be default.

#### Keyboard layout

Because some languages have alternative keyboard layouts, it's impossible for people who use those layouts to use normal shortcuts. For example, the Clear Heading shortcut (`Ctrl+Alt+0`) will input "}" if you're using the Polish keyboard layout.

Right now there are four keyboard layout settings (in no particular order): English (United States), French (France), Polish (Poland), and German (Germany). If you find things not working with your keyboard layout, [let us know]({{ site.feedback_url }})!

To see what shortcuts are affected by choosing each layout, see [the keyboard shortcuts section](../locale-shortcuts/).

This setting defaults to English (United States).

## Date

#### Time format

Choose between seeing 12-hour clock times and 24-hour clock times. This format is used for displaying dates and also in the timepicker.

This setting defaults to 12-hour clock.

#### First day of week

Choose which day shows up as the first day in the date picker between Sunday and Monday.

This setting defaults to Sunday.

#### Date display format

This option is Pro-only and it allows you to change how date is displayed.

The format is the following:

||Token|Output|
|---|---|---|
|Month|M|1 2 ... 11 12|
||Mo|1st 2nd ... 11th 12th|
||MM|01 02 ... 11 12|
||MMM|Jan Feb ... Nov Dec|
||MMMM|January February ... November December|
|Quarter|Q|1 2 3 4|
||Qo|1st 2nd 3rd 4th|
|Day of Month|D|1 2 ... 30 31|
||Do|1st 2nd ... 30th 31st|
||DD|01 02 ... 30 31|
|Day of Year|DDD|1 2 ... 364 365|
||DDDo|1st 2nd ... 364th 365th|
||DDDD|001 002 ... 364 365|
|Day of Week|d|0 1 ... 5 6|
||do|0th 1st ... 5th 6th|
||dd|Su Mo ... Fr Sa|
||ddd|Sun Mon ... Fri Sat|
||dddd|Sunday Monday ... Friday Saturday|
|Day of Week (Locale)|e|0 1 ... 5 6|
|Day of Week (ISO)|E|1 2 ... 6 7|
|Week of Year|w|1 2 ... 52 53|
||wo|1st 2nd ... 52nd 53rd|
||ww|01 02 ... 52 53|
|Week of Year (ISO)|W|1 2 ... 52 53|
||Wo|1st 2nd ... 52nd 53rd|
||WW|01 02 ... 52 53|
|Year|YY|70 71 ... 29 30|
||YYYY|1970 1971 ... 2029 2030|
||Y|1970 1971 ... 9999 +10000 +10001|
|Week Year|gg|70 71 ... 29 30|
||gggg|1970 1971 ... 2029 2030|
|Week Year (ISO)|GG|70 71 ... 29 30|
||GGGG|1970 1971 ... 2029 2030|
|AM/PM|A|AM PM|
||a|am pm|
|Hour|H|0 1 ... 22 23|
||HH|00 01 ... 22 23|
||h|1 2 ... 11 12|
||hh|01 02 ... 11 12|
||k|1 2 ... 23 24|
||kk|01 02 ... 23 24|
|Minute|m|0 1 ... 58 59|
||mm|00 01 ... 58 59|
||Second|s|0 1 ... 58 59|
||ss|00 01 ... 58 59|
|Fractional Second|S|0 1 ... 8 9|
||SS|00 01 ... 98 99|
||SSS|000 001 ... 998 999|
||SSSS ... SSSSSSSSS|000[0..] 001[0..] ... 998[0..] 999[0..]|
|Time zone|z or zz||
||Z|-07:00 -06:00 ... +06:00 +07:00|
||ZZ|-0700 -0600 ... +0600 +0700|
|Unix Timestamp|X|1360013296|
|Unix Millisecond Timestamp|x|1360013296123|

For example, if you want your date to display as "2017/3/12 03:30pm", write "YYYY/M/D hh:mma".

> Your custom date format will always override our default, so you won't see dates show as "Tomorrow" or "In 2 days" any more. To use the default format, leave this option blank.

#### Show timezone

This decides whether timezone suffixes are generated by the date picker. They look like `-05:00` and are used to denote the difference between your timezone and UTC, the Coordinated Universal Time.

We recommend turning on this option if you're working people in other timezones to avoid your 7 pm time being understood as 7 pm in their timezone.

This setting is turned off by default.

#### Highlight overdue items in red

As the name suggests, this option allows you to highlight overdue items.

This setting is turned off by default.

## Control

#### Use bullet point to zoom in

When turned on, this option swaps the position of the zoom in option and the collapse/expand option. If other words, if you use zoom more often than collapse/expand, it might be a good idea to turn this on.

This setting is turned off by default.
