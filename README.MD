### Lite Flame
This is basically me ripping off the idea and look of https://github.com/pawelmalak/flame
to make a plain html file that does basically the same thing without needing a 300mb docker
image/container running with node.js.

Overall, it provides a single page home page where you can list apps and links (works on Mac OS X to open apple news, VNC, folders, etc). A nice way to customize your start page.

I made some changes too for my own needs:
- Removed the weather feature
- Changed the search to search the page rather than hit a search engine (I'd rather just use the built-in address bar search since it provides autocomplete against search engines)

When the page first loads, just start typing to filter. If you get down to 1 item, hit enter and the page will just load the app/bookmark.

To use this:
1. Clone the repo
2. Edit the index.html file and fill in the config object at the top.

The rest should just work then.

Demo:
![Demo](https://github.com/rizwanjiwan/liteflame/raw/main/demo.gif)