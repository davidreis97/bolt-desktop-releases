# BOLT Desktop — releases

Installers for the [BOLT](https://boltball.io) desktop client. Download the
latest version from [Releases](../../releases/latest); installed apps update
themselves from here automatically.

Source lives in a private repo. Releases are built by
[`.github/workflows/release.yml`](.github/workflows/release.yml):

```sh
gh workflow run release.yml -R davidreis97/bolt-desktop-releases
```
