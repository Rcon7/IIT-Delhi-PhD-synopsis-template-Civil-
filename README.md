# Synopsis
PhD Synopsis report

The department requires you to compress your synopsis report to 2.5 megabytes. This is a way to do it on your own system using Ghostscript

Shrink pdf size (GhostScript--in terminal; doesn't work in powershell):
gswin64 -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/printer -dNOPAUSE -dQUIET -dBATCH -sOutputFile="main_compressed.pdf" "main.pdf"
(https://transloadit.com/devtips/efficient-pdf-optimization-with-ghostscript-cli/)
