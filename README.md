# Switcheroo

A Chrome extension for fuzzy-finding and switching between tabs.

## Installing

1. Clone this repository
2. In Chrome, navigate to `chrome://extensions`
3. Tick the "Developer Mode" checkbox
4. "Load Unpacked Extension", select the folder into which you cloned.

By default Switcheroo binds to Ctrl+Shift+K which is terrible. In the likely case you want to change it to something sane, like Ctrl+P:  Scroll to the bottom of `chrome://extensions`, hit "Keyboard Shortcuts", change the "Do the ol' switcheroo" shortcut to whatever you like.

It's not bound there by default because extensions cannot bind to already bound or possibly bound keys.

## Uninstalling

:(

1. Navigate to chrome://extensions
2. Hit the trash icon next to Switcheroo
3. Delete local files

## Using

Navigate to any page, hit the shortcut (default Ctrl+Shift+K, you should really change it), and start typing! The tab url and tab title are searched.

Hit Enter to navigate, Up/Down/Home/End to select from the list. Esc to quit.

Note that Switcheroo will *not* search incognito tabs. This is by design.

## Why?

Let's say you have 20 open tabs. Navigate to tab 14 please. Or to that YouTube video.

Got too many tabs that you can only make out the favicons, and blindly end up trying to jump between them?

Want to go full-screen?

## Why isn't this in the web store?

Several reasons:
* You must have a Google account
* You can't publish anonymously
* They charge $20
* They honour sanctions on countries (so an Iranian or North Korean cannot publish there)
* I cbf right now.

## TODOs
* Sort tabs by activity
* Add PgUp/PgDown navigation
* Make searching Incognito tabs an option?
* When there's a selected item and you filter on, the list scrolling follows the selected item, even if it's really far down the list. Make it fall-back to the first item?
* --- Option to create tab if search looks like a url ---
* Get/make/steal an icon
* *yo mama joke*

## License
Everything *I* write is under [WTFPL](http://www.wtfpl.net/).

New Tab icon by [Google](https://github.com/google/material-design-icons), licensed under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/).

String scoring by [Joshaven Potter](https://github.com/joshaven/string_score), licensed under MIT.
