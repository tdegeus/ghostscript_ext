# ghostscript_ext

 Wrappers around GhostScript

 ## Contents

<!-- MarkdownTOC -->

- [Modify PDF](#modify-pdf)
    - [`pdfcombine`](#pdfcombine)
    - [`pdfpages`](#pdfpages)
    - [`pdfsafe`](#pdfsafe)
    - [`pdfshrink`](#pdfshrink)
    - [`pdfmeta-set`](#pdfmeta-set)
- [Modify PNG](#modify-png)
    - [`pngcrop`](#pngcrop)
- [Convert file-format](#convert-file-format)
    - [`makepdf`](#makepdf)
    - [`makeeps`](#makeeps)
    - [`makepng`](#makepng)

<!-- /MarkdownTOC -->

## Modify PDF

### `pdfcombine`

Combine several PDFs to a single PDF.

### `pdfpages`

Extract one or more pages from a PDF.

### `pdfsafe`

Remove all characters from a PDF to, as far as possible, ensure correct printing of the PDFs.

### `pdfshrink`

Try to remove the file-size by reducing the resolution of the graphics in the PDF.

### `pdfmeta-set`

Set the author and title in the meta-data of the PDF.

## Modify PNG

### `pngcrop`

Crop PNG-images and optionally remove the background.

## Convert file-format

### `makepdf`

Convert a file to an PDF-file.

### `makeeps`

Convert a file to an EPS-file.

### `makepng`

Convert a file to an PNG-file.

