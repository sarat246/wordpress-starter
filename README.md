WordPress Starter
==================

This Compass extension provides support for creating WordPress Themes using Sass.

Installing
==========

    [sudo] gem install wordpress-starter

To install a theme into your existing compass project, add the following to your compass configuration file:

    require 'wordpress-starter'

Or, just run this command:

    compass -r wordpress-starter -f wordpress /path/to/installation

What this does is call `compass`, requires the wordpress-starter extension, uses the framework wordpress, sets the Sass output to be compressed and finally ends with you setting the theme name.

Available patterns
==================

There are some available patterns:

The default pattern creates a basic theme
-----------------------------------------

	compass -r wordpress-starter -f wordpress /path/to/installation

this theme comes bundled with a few features that makes easier to start:

- Full HTML5+CSS3 markup
- Build with [Compass](http://compass-style.org/) and Susy grid framework [http://susy.oddbird.net/](http://susy.oddbird.net/)
- The theme is bundled with the [Slightly Modded Options Framework SMOF](http://aquagraphite.com/2011/09/29/slightly-modded-options-framework/), and include some known filters and actions that cleans and improves the output generated by WordPress

The foundation pattern contains a basic theme based on Zurb's Foundation framework
---------------------------------------------------------------------------------

	compass -r wordpress-starter -f wordpress/foundation /path/to/installation

this theme comes bundled with a few features that makes easier to start:

- Full HTML5+CSS3 markup
- Build with [Compass](http://compass-style.org/) and Zurb's Foundation framework 3.2 [http://foundation.zurb.com/](http://foundation.zurb.com/)
- The theme is bundled with the [Slightly Modded Options Framework SMOF](http://aquagraphite.com/2011/09/29/slightly-modded-options-framework/), and include some known filters and actions that cleans and improves the output generated by WordPress

The starter pattern contains the Automattic starter theme _s [http://underscores.me/](http://underscores.me/)
------------------------------------------------------------

	compass -r wordpress-starter -f wordpress/starter /path/to/installation

- The theme has been adapted to work with sass.

All the code included tries to follow the [WordPress coding standards](http://codex.wordpress.org/WordPress_Coding_Standards)

Dependencies
============

- compass >= 0.12.2
- sass >= 3.2.0
- zurb-foundation >= 3.2.2
- susy ~> 1.0.5

Note on Patches/Pull Requests
==============================

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Copyright
===========

Copyright (c) 2012 Alex Sancho. See LICENSE for details.
