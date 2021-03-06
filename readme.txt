=== WP Engine Advanced Cache ===

Contributors: ethankennedy, stevenkword
Tags: wpengine, cache, headers, last-modified
Requires at least: 3.5
Tested up to: 4.7.4
Stable tag: 0.0.1

This plugin is a tool that leverages some specific WP Engine tools, as well as general web options for increasing the cacheability of a WordPress site.

== Description ==

This plugin is a tool that leverages some specific WP Engine tools, as well as general web options for increasing the cacheability of a WordPress site.

== Known Issues ==

== Changelog ==

0.4.1 - Added a few more comments/doc blocks
			- Updated code to be functional, pending more testing

0.4.0 - Options refactor to a single value stored in wp_options

0.3.6 - Code refactor to use filters.
			- Refactored code to add headers.

0.3.5 - Heavy documentation improvements.

0.3.4 - More code improvements and documentation updates.

0.3.3 - General code improvements, and other documentation improvements.
			- Added support for non-wpengine installs.

0.3.2 - Added global_last_modified function and various calls that could affect all requests to the server.

0.3.1 - Added additional functionality around last_modified headers in respect to most recent comment.

0.3.0 - Added last_modified headers to requests based on get_the_modified_date.
			- Added Smarter Cache Functionality.

0.2.1 - Added validation to the ajax purge tool.

0.2.0 - Added Ajax purge tool.

0.1.2 - Added better logic to managing cache times globally

0.1.1 - Added menu page to manage those functions.

0.1.0 - Added functionality to add cache headers to requests.
