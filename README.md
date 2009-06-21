# Textpandable Plugin for jQuery

## About This Archive

This jQuery plugin was originally published on my blog in June 2009.  This plugin was used and modified for use in various personal and work-related projects, but was not maintained long-term.  

This repository was created for archival purposes.

## Original Blog Post Description

Just wrote my first jQuery plugin!  Textpandable is a plugin that enables textareas to auto-resize to fit content.  Just load jQuery and Textpandable, and include the following Javascript:  

```$(‘textarea’).textpandable();```

…and voilà!  All of your textareas are expandable, like this:

[Example of auto-expanding textarea](http://thomshouse.net/blog/wp-content/uploads/2009/06/textpandable-0-9.gif)

Textpandable in ActionTextpandable offers the following options:

- **lineHeight**: Specify the lineHeight of the textarea–as a Textpandable option or a CSS declaration.
- **minRows** and **maxRows**: Set limits to how small or big your textarea will expand to.
- **padding**: Set a number of extra rows to provide for “padding”.  1-2 rows is usually a good value.
- **width**: Number of characters to allow per line before adding an extra row.  If not set, Textpandable tries its best to determine safe values based on CSS declarations, col attributes, and/or pixel width.

Now, I’m calling this version 0.9 for a few reasons:  I haven’t tested this in IE yet, and I haven’t documented the code (although it’s really simple)…  but most of all, it’s not feature-complete: I want to get animations working.  Unfortunately, with animations turned on, any change in size causes the cursor position to skip to the end and/or lose focus.  I’m not experienced enough with the innards of jQuery to know why this would be happening.  

It works just fine with the default speed setting of ‘0’ (as I’ve short-circuited the animation script in this case).  Anyone who gets animation working will be my hero!  

[Download Textpandable v0.9 (Dual-Licensed MIT & GPL)](https://github.com/thomshouse/textpandable.js/blob/master/textpandable.js)