# Slide Template

Template of presentation slide by LaTeX.


## デモ / Demo

<img src="image/demo_0001.jpg" width="300" align="middle"> <img src="image/demo_0002.jpg" width="300" align="middle">
<img src="image/demo_0003.jpg" width="300" align="middle"> <img src="image/demo_0004.jpg" width="300" align="middle">
<img src="image/demo_0005.jpg" width="300" align="middle"> <img src="image/demo_0006.jpg" width="300" align="middle">
<img src="image/demo_0007.jpg" width="300" align="middle"> <img src="image/demo_0008.jpg" width="300" align="middle">
<img src="image/demo_0009.jpg" width="300" align="middle"> <img src="image/demo_0010.jpg" width="300" align="middle">
<img src="image/demo_0011.jpg" width="300" align="middle"> <img src="image/demo_0012.jpg" width="300" align="middle">
<img src="image/demo_0013.jpg" width="300" align="middle"> <img src="image/demo_0014.jpg" width="300" align="middle">
<img src="image/demo_0015.jpg" width="300" align="middle"> <img src="image/demo_0016.jpg" width="300" align="middle">
<img src="image/demo_0017.jpg" width="300" align="middle">


## 🏯 ビルド / Build

### 🍊 Makefile

```bash
# Rebuild all & Remove a part of generated files.
make all
# Build all
make build
# Rebuild all.
make rebuild
# Print debug messages after building.
make debug
# View PDF/PostScript file.
make preview
# Remove a part of generated files.
make clean
# Remove all generated files.
make distclean
# Print help.
make help
```

### 🍌 Latexmk

```bash
# Build all.
latexmk
# Remove all generated files.
latexmk -C
# View PDF file, compiling when the files changed.
latexmk -pvc
```

### 🥝 GitHub Actions

After pushing tag to remote repository,
GitHub Actions compiles this documents,
and releases it to GitHub Releases Page.

```bash
# Add a tag.
git tag -a v0.0.0 -m 'tag comment'
# Share a tag.
git push origin v0.0.0
```


## 🍋 License / ライセンス

Copyright (c) 2021-2022 k5-mot All Rights Reserved.

"k5-mot/slide-template" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

