
_pretzel
========

Hi. Hi. I'm a starter theme called `_pretzel` based off of the `_s`, or `underscores` theme, if you like. I'm a theme meant for hacking so don't use me as a Parent Theme. Instead try turning me into the next, most awesome, WordPress theme out there. That's what I'm here for.

I contain a lot of the great stuff that the `_s` theme but will include a few additional pieces to better suit my particular needs as a starting boilerplate for a theme. This is a work in progress currently that will continue to evolve I'm sure but some key differences from the `_s` theme will likely be the inclusion of things like Bourbon https://github.com/thoughtbot/bourbon and Neat https://github.com/thoughtbot/neat and probably some vendor specific styling for things like the Divi Builder https://www.elegantthemes.com/plugins/divi-builder/

* A just right amount of lean, well-commented, modern, HTML5 templates.
* A helpful 404 template.
* Custom template tags in `inc/template-tags.php` that keep your templates clean and neat and prevent code duplication.
* A script at `js/navigation.js` that makes your menu a toggled dropdown on small screens (like your phone), ready for CSS artistry. It's enqueued in `functions.php`.
* Licensed under GPLv3 or later. :) Use it to make something cool.

Getting Started
---------------

If you want to set things up manually, download `_s` from GitHub. The first thing you want to do is copy the `_s` directory and change the name to something else (like, say, `megatherium`), and then you'll need to do a five-step find and replace on the name in all the templates.

1. Search for `'_pretzel'` (inside single quotations) to capture the text domain.
2. Search for `_pretzel_` to capture all the function names.
3. Search for `Text Domain: _pretzel` in style.css.
4. Search for <code>&nbsp;_pretzel</code> (with a space before it) to capture DocBlocks.
5. Search for `_pretzel-` to capture prefixed handles.

OR

* Search for: `'_pretzel'` and replace with: `'megatherium'`
* Search for: `_pretzel_` and replace with: `megatherium_`
* Search for: `Text Domain: _pretzel` and replace with: `Text Domain: megatherium` in style.css.
* Search for: <code>&nbsp;_pretzel</code> and replace with: <code>&nbsp;Megatherium</code>
* Search for: `_pretzel-` and replace with: `megatherium-`

Then, update the stylesheet header in `style.css` and the links in `footer.php` with your own information. Next, update or delete this readme.

Now you're ready to go! The next step is easy to say, but harder to do: make an awesome WordPress theme. :)

Good luck!
