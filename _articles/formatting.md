---
layout: article
title: Formatting
permalink: /formatting/
---

You can use Markdown to format text in Dynalist. Markdown is rendered whenever you're not focusing on an item. When you focus on an item, the plain text source behind the Markdown is displayed so that you can edit it.

Dynalist's Markdown syntax is identical to Markdown except that `*italic*` and `_italic_` doesn't work. Instead, `**bold**` and `__italic__` is used. The intention is to not surprise people who don't use Markdown, as it's common to have `*` or `_` surround text.

#### Bulk formatting

Most of the shortcuts work with multiple items. Simply drag to select the items you want and use the menu or press the shortcut.

#### Heading

You can emphasize an item by making it a heading. In the item menu, click on "H1" to make it a level 1 heading, and so on. There are 3 levels of heading.

To clear the current heading, click on its current heading option, which is marked by blue (e.g. to clear a level 2 heading, click on the "H2" again in the item menu).

The shortcut to set heading 1~3 is `Ctrl+Alt+1~3`. The shortcut to clear the current heading formatting is `Ctrl+Alt+0`.

#### Color labels

Visual thinkers can take advantage of color labels to quickly categorize things.

In the item menu, you'll see a bunch of "A"s on different background colors. Click on one to apply a color label. Click on the current color again will remove the color.

The shortcut to apply color label 1~6 is `Ctrl+Shift+1~6`. The shortcut to clear the current color label is `Ctrl+Shift+```.

#### Bold

You can make bold text `**like this**`. The associated keyboard shortcut is `Ctrl+B`.

#### Italic

You can make italic text `__like this__`. The associated keyboard shortcut is `Ctrl+I`.

#### Inline code

You can make inline code \``like this`\`. The associated keyboard shortcut is `Ctrl+`\`.

> Note: the character used here is not a quote character, but rather a grave accent. It's also called a backtick. You can find it above your `Tab` key.

#### Line-through

You can make line-through text `~~like this~~`. There's no associated keyboard shortcut.

#### Link

You can make a link `[like this](www.dynalist.io)`. There's no associated keyboard shortcut.

If you don't need the link to be named, pasting the URL is enough to make it clickable. No Markdown needed. 

> Note: if not using Markdown, please include the protocol (e.g. `http://` or `https://`) in your links, otherwise they won't display as links. The intention is to not mistake normal text as links. If you paste links from the browser, the protocol should be automatically included.

#### Image link

You can make an image link `![like this](example.com/kitten.jpg)`. There's no associated keyboard shortcut.

The difference between image links and normals is that image links have an image icon to mark it, and hovering on an image link would open a preview of the linked image inside Dynalist.

#### LaTeX

You can write LaTeX equations `$$like this$$`. The associated keyboard shortcut is `Ctrl+L`.

Dynalist uses KaTeX by Khan Academy to render LaTeX. It's faster than MathJAX but is still incomplete at this point. Their project is [open-source and hosted on GitHub](https://github.com/Khan/KaTeX). You're welcome to create an issue there if you feel like it's missing the functionalities you need.

To see all TeX functions supported by KaTeX, please refer to [this list](https://github.com/Khan/KaTeX/wiki/Function-Support-in-KaTeX).

#### Keyboard shortcuts

Some syntaxes have associated keyboard shortcuts. If you have selected text, using the shortcut will add or remove Markdown syntax around the text, depending on whether it's already surrounded by that syntax. If you're not selecting any text, using the shortcut will insert one side of the Markdown syntax for you (e.g. `**` for bold). You can use the shortcut again after you've finished writing what's inside the syntax.

We know it takes some practice to remember these syntaxes, that's why we built a formatting cheatsheet right into the Dynalist web app. Press `Ctrl+?` and you will see it pop up.

For a list of formatting shortcuts, see [the keyboard shortcuts section](../formatting-shortcuts/).
