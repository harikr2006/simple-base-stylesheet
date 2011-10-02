# A Simple Base Stylesheet

This is an base stylesheet that I use in some of my projects. I don’t just
copy it and go on writing other CSS styles, but tend to modify the rules
to fit the project.

Default browser styles are fairly consistent. There *are* a few differencies
though, and this stylesheet (especially the `simple.css` variant) tries to
reduce those differencies for the most common HTML elements.

It takes a more specific and subtle approach than the “carpet bombing”
strategy of [CSS Resets][]. For a more comprehensive project with a similar approach, see [normalize.css][].

[CSS Resets]: http://www.cssreset.com/
[normalize.css]: http://github.com/necolas/normalize.css

## Will this fix browser rendering issues?

Nope. No CSS Reset or base stylesheet can. Most browser rendering issues are
due to lacking browser capabilities, subtleties in implementations, or
outright browser bugs.