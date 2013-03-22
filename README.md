Small HTML 2011
===============

This is the winning entry for the [small html competition](http://www.gathering.org/tg11/en/creative/competitions/small-html/) at The Gathering 2011. 
We were given [this sample image](http://haeric.github.com/small-html-2011/sample.png) and asked to create it with 
the smallest possible amount of code. 

### The winning entry
[View the winning entry](http://haeric.github.com/small-html-2011/entry_minified.html) at 361 bytes. It will take a minute to load; thankfully the only criteria was filesize, not rendering speed!

The code utilizes `createLinearGradient` to create a gradient at the very top of the canvas, 
which is then used as a palette for the rest of the canvas, using a bit of trigonometrics to get the bubbles.

### The improved version
[The improved version](http://haeric.github.com/small-html-2011/improved_minified.html) at 325 bytes is the currently smallest version I've been able to make after the competition, but it's rather ugly as it
only works when the file is minified, due to the onload hack, so no unminified version is provided.
