# texstudio-build-setup

Settings:

under Commands:
add '-output-dir=build' at PdfLaTeX
add 'build/%.pdf' at External Pdf Viewer
add 'build/%.aux' at BibTeX

under Build:
at the bottom "Addtional Search Paths"
add 'build' at Pdf File

Project structure

```
build/
source/
    symlink ../build
.git/
```
