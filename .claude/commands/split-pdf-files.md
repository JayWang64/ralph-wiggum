---
description: Split a PDF into individual pages with standardized naming
allowed-tools: ["Bash", "Read", "Write"]
---

Split the PDF file provided as input into individual pages.

Input file: $ARGUMENTS

## Requirements:
1. Create output folder: `./split-output/<original-filename-without-extension>/`
2. Name each page: `page-001.pdf`, `page-002.pdf`, etc. (zero-padded to 3 digits)
3. Use pdftk or qpdf to split (check which is available first)
4. Report total pages extracted when done

## Example:
Input: `binder.pdf`
Output folder: `./split-output/binder/`
Files: `page-001.pdf`, `page-002.pdf`, ...
