# Real Copy

Chrome extension to copy selected text from webpage without allowing the page
to inject anything to the clipboard. See <https://security.love/Pastejacking/>
and <https://github.com/dxa4481/Pastejacking> for more context.

![Screenshot](http://i.imgur.com/IvvOWUY.png)

Made with disgust and 5 minutes during my lunch break.

### Installation

- clone repo
- go to chrome://extensions/
- enable developer mode
- select "Load Unpacked Extension" and point to the cloned directory

Now at any page you can select some text and click on the new copy icon in the
top bar of the page to copy the text.

It uses the `window.getSelection` API to get the selected text and then copies
it with a non-evil(TM) script.

### Why not Firefox too?

Good question. I don't know really. Maybe it works with FF as is with the new
webextensions API. If it does, please let me know since I use FF as well :P

### License

WTFPL

### Author

Awal Garg
