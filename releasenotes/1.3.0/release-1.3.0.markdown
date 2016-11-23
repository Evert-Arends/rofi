# V1.3.0: Dan vs. Greg: The never ending story.


## Detailed Changelog

###	New Features

- Use randr for getting monitor layout. Fallback to xinerama if not available.
- Re-add fuzzy parser.
- Restructure internal code to use dynamic sizing widgets. (hbox, vbox and lists)
- Async mode for dmenu.
- Add theme selector script.
- Dynamically sizing window with content.
- When placed at bottom of screen re-order screen to have entry at bottom.

###	Improvements

- Create cache and run directory on startup. (#497)
- Fix uneeded redraws on cursor blinking. (#491)
- Improve time till grabbing keyboard. (#494)
- Better error message when failing to parse keybindings, also continue parsing on error.
- Fix problem with custom layouts (#485)
- Speedup drawing of screen. Works well now for 4k and 8k screens. (factor 1000+ speedup for the flipping of
buffer) (#496)
- DRun mode more compatible with specification.
- Debug output via g_log.
- Fix password entry cursor position.
- Use bash instead of sh for get_git_rev.sh (#445)
- Add Control+G for cancel (#452)
- Add padding option to textbox (#449)
- Ctrl-click does alternate accept entry. (#429)
- Hide window decoration in normal window mode. 
- Click to exit option. (#460)
- Fix cursor blinking on moving. (#462)
- Remove entry from history if fails to execute (#466)
- Fix margins. (#467)
- Improved documentation of functions in code.
- DRun: Set work directory when executing file. (#482)
- Memory leak fixes.
- Improve scrollbar behaviour.

###	Removals

- opacity option. The transparency support in the theme can do the same and more.