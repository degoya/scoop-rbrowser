# rBrowser for Scoop

The Scoop bucket of [rBrowser](https://github.com/degoya/rBrowser), a development browser that shows
every breakpoint of a site at once, for Windows x86-64.

```powershell
scoop bucket add rbrowser https://github.com/degoya/scoop-rbrowser
scoop install rbrowser
```

rBrowser is in the Start menu and on the `PATH` as `rbrowser`. `scoop update rbrowser` brings the
next release; rBrowser installed through Scoop does not replace itself. Its settings and profiles
live in the user's folders (`%APPDATA%\rBrowser`, `%LOCALAPPDATA%\rBrowser`), not in Scoop's app
folder, so an update or reinstall keeps them.

Current version: 0.9.6. The manifest is written by the release workflow of
[degoya/rBrowser](https://github.com/degoya/rBrowser) with every release - issues and changes go there,
not here. The handbook's installation page:
<https://github.com/degoya/rBrowser/wiki/installation>.
