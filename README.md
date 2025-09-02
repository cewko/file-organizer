# file-organizer

Organizes files in a directory by moving them into categorized folders based on their file extensions.

## Usage

```bash
file-organizer [option] [directory]
```

## Options

- `-h, --help` - show help message
- `-v, --verbose` - show detailed output
- `-n, --dry-run` - show what would be done without moving files
- `--version` - show version information

## File categories

Files are organized into folders based on extensions:

- **images** - jpg, jpeg, png, gif, bmp, svg, webp, tiff, heic, ico
- **videos** - mp4, mkv, mov, avi, flv, wmv, webm, mpg, mpeg, m4v, 3gp
- **audio** - mp3, wav, flac, aac, ogg, m4a, wma, opus
- **documents** - pdf, doc, docx, txt, rtf, odt, xls, xlsx, ppt, pptx, csv, md, tex
- **code** - py, js, java, cpp, c, cs, html, css, php, go, rb, swift, ts, sh, bash, zsh, fish, ipynb, sql, r, scala, kt
- **archives** - zip, rar, 7z, tar, gz, bz2, xz, iso, deb, rpm, pkg, apk
- **installers** - exe, msi, dmg, deb, rpm, pkg, apk, flatpak, snap, appimage
- **e-books** - epub, mobi, azw3, azw, fb2, lit
- **config** - ini, json, yaml, yml, log, cfg, toml, conf, xml, properties
- **fonts** - ttf, otf, woff, woff2, eot
- **3d-models** - obj, stl, ply, dae, fbx, blend
- **misc** - unknown extensions