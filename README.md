# readline

GNU Readline 8.2 line editing library (with history)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install readline
```

| | |
|---|---|
| Version | 8.2 |
| Licence | GPL-3.0+ |
| Upstream | https://tiswww.case.edu/php/chet/readline/rltop.html |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc), [`ncurses`](https://github.com/Artfical/tpkg-ncurses) |
| Needs tOS build | 615 or newer |
| Size | 595598 bytes (1698321 unpacked) |
| SHA-256 of the `.tpkg` | `c09f25b3782d94fd739bdc3103b41dea5e8336626489d2ba9e2c27ea3e31f83f` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`readline-8.2.tpkg`) and the sources it was built from are the assets of the
[v8.2 release](https://github.com/Artfical/tpkg-readline/releases/tag/v8.2).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `readline-8.2.tar.gz`

Check a download: `sha256sum readline-8.2.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0+. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
