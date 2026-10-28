# InkDo releases

Signed macOS builds of InkDo, a calm, keyboard-first Markdown editor.

This repository holds release files only, no source code. Each release has:

- `InkDo_<version>_aarch64.dmg`: download and drag InkDo to Applications.
- `InkDo.app.tar.gz` and its `.sig`: what the in-app updater downloads.
- `latest.json`: the version, notes and signature the updater checks once a day.

Every update is signed with InkDo's own minisign key, and the app refuses any file whose signature doesn't match the public key built into it.

No release has been published yet.
