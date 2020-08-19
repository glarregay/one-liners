## Useful One-liners

A collection of one-liners (or few-liners) to solve common issues I've had to deal with.

---

## PDF Related

### Remove PDF printing protection (from [here](https://superuser.com/questions/367184/removing-pdf-usage-restrictions))

`pdftk in.pdf output out.pdf allow AllFeatures`

### Show PDF information (from [here](https://www.cyberciti.biz/faq/linux-unix-view-technical-details-of-pdf/))

`pdfinfo {file.pdf}`

### Combine NxM PDF pages in one (from [here](https://0x2a.at/blog/2011/02/pdf_manipulation_on_the_cli/))

`pdfjam --nup 2x2 file1.pdf --outfile output.pdf`

---

## Video related

### Convert from WebM to MP4 (from [here](https://stackoverflow.com/questions/18123376/webm-to-mp4-conversion-using-ffmpeg))

`ffmpeg -i input.webm -c copy output.mp4`