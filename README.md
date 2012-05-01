ExpressionEngine DRY Example
============================

Example templates illustrating a DRY/MVC/Partial (name your poison) approach when building an ExpressionEngine site.

These files are to support Episode 68 of the EE Podcast, "DRY+EE w/John Rogerson."

For the original article on Template Partials see John D Wells' [Homegrown plugin to create template "partials" for ExpressionEngine](http://johndwells.com/blog/homegrown-plugin-to-create-template-partials-for-expressionengine). The Stash plugin is available from [devot:ee](http://devot-ee.com/add-ons/stash).

These files are provided to give those interested a working but rudimentary and high level conceptual example of achieving both DRY + MVC nirvana in your EE templates. At least that's my interpretation. YMMV.

There are 3 templates:
----------------------

1. `index.html` (Logic template for homepage)
2. `page.html` (Logic template for interior page)
3. `view.html` (View template for all pages)

There are 4 snippets:
---------------------

1. `sn_channel_markup.html` (View Snippet for exp:channel:entries output)
2. `sn_head.html` (Snippet for `<head>`)
3. `sn_header.html` (Snippet for `<header>`)
4. `sn_footer.html` (Snippet for `<footer>`)

Note: Snippets 2 thru 4 are unnecessary in this particular example, as we only have one "view" template, but are included for clarity.