---
title: "<a href='https://github.com/CharlesNaylor/reversible_ca'>Celtic Knots based on Cellular Automata</a>"
excerpt: "Simple code for generating reversible cellular automata, then converting the pattern into nodes and edges suitable for Knotter<br/><img src='/images/ca.png'>"
background-image: url(neg\_boolean.png)
collection: portfolio
---

In _A New Kind of Science_, Stephen Wolfram demonstrates reversible one-dimensional cellular automata. Using these, you can create a chaotic pattern that resolves into a regular geometric shape, before dissolving again forever more into chaos.

I have a weirdly narrow hallway in my house that needs a custom-sized rug to prevent my toddlers getting splinters. You can use this code to create a long, narrow pattern that looks a bit like a Persian rug in the center, and chaos at either end. This is how my two-year-old learned the words 'order' and 'chaos'.

<img src='/images/ca.png'>

To make things more interesting, the basic binary pattern can be translated into XML nodes and edges and fed into <a href="https://sourceforge.net/projects/knotter/">Knotter</a>, provided you're willing to take the risk of downloading something from SourceForge.

There's also a module to draw the pattern with any given svg object, which will be rotated and replicated as appropriate. I have not had much luck making anything attractive that way, but somebody with a better creative sense than I have might find something to do.

The final picture I generated for my hallway was huge, and too big to upload here. I had it printed to a vinyl banner to check that I like the color scheme in real life, but that's as far as I got. The carpet printer I'd engaged told me it crashed his computer (maybe add some RAM?). If you're curious, you can download the final scheme off Dropbox <a href="https://www.dropbox.com/s/vxos13c6j56jq29/boolean_1.png?dl=0">here</a>. This was designed to be about 20 feet long in real life, so you have to zoom in to get an idea of the underlying knot pattern. 

Maybe someday I'll find a use for the vinyl banner...

