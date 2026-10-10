# دوس يا أسطى — legal pages

Privacy policy and account deletion pages for Dos Ya Osta (Nourbyte), served by GitHub Pages.

`config.json` is the game's version gate. A build whose versionCode is below `minVersionCode` is blocked until the
player updates; a build below `latestVersionCode` gets a dismissible "new version" prompt. Raise `latestVersionCode`
after each Play release, and raise `minVersionCode` only when old builds must stop working.
