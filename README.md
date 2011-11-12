HTML is awesome because it's declarative. Unfortunately, the DOM API is mostly imperative.

Templating languages are pretty cool because you get to use a declarative language to make some DOM elements. But they either don't give you the full expressiveness of a decent functional language, or they do and it's a bunch of arbitrary stuff stuck in some ugly tags - which I am still way too lazy to learn, when I already have a decent functional language (JavaScript).

The right thing to do here is to just make a functional wrapper for the DOM API, which is what `h.js` does. There are already things like [Jaml](http://edspencer.net/2009/11/jaml-beautiful-html-generation-for-javascript.html), but by my tastes they overcomplicate it.

This is a quick implementation of the basic principles. It depends on [Underscore.js](http://documentcloud.github.com/underscore/).