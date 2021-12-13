# ![](img/bookmark_border-24px.svg) pdfoutline

A command line tool for adding an outline (a bookmark, or table of contents) to pdf files

### Prerequisites

Make sure you have `ghostscrict` installed. In Mac, you can use `homebrew`:

```
brew install ghostscript
```

### Sample output

<img src="img/demo-output.png" width="300" style="margin:auto">


### Sample Table of contents file: `sample.toc`

```
# this is a comment
First Chapter 1
    first section 1
        first subsection 1
    second section 4
    third section 5

# a command to fix a gap between pdf pages and content pages
+10

Second Chapter 10
    some entry 10
    some entry 11
```

### Usage

```
$ ./pdfoutline.py sample.pdf sample.toc sample-out.pdf
 |██████████████████████----------------------------| 118/263
```

