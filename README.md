# ThoughtBar releases

Signed, notarized builds of **ThoughtBar**, the macOS menu bar app for
[thought-central](https://github.com/brancusi/thought-central), with its own `thc` command line tool.

**[Download the latest ThoughtBar (DMG)](https://github.com/brancusi/thought-central-releases/releases/latest/download/ThoughtBar.dmg)**

Apple silicon, macOS 14 or later. Open the DMG and drag ThoughtBar to Applications.

From a terminal (installs the app and links `thc`; checks the signature and notarization first):

```sh
curl -fsSL https://github.com/brancusi/thought-central-releases/releases/latest/download/install.sh | bash
```

Installed copies update themselves. The update feed is
`https://github.com/brancusi/thought-central-releases/releases/latest/download/appcast.xml`.

This repository only holds release files. The source is in
[brancusi/thought-central](https://github.com/brancusi/thought-central).
