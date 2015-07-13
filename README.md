pdfjs-googledrive
-----------------

Alter the directory structure of [pre-built pack of PDF.js](https://mozilla.github.io/pdf.js/getting_started/#download) so that it can be quickly deployed to [Google drive hosting](https://support.google.com/drive/answer/2881970?hl=en).

Deploy to google drive hosting
------------------------------

1. Set up a Google drive folder that can expose itself to the world ([as instructed here](https://support.google.com/drive/answer/2881970?hl=en)).
2. Upload index.html and `pdfjs` directory to the google drive folder.
3. Upload some PDF files to that folder as well.
4. Visit `http://www.googledrive.com/<folderId>?file=<PDF file name>#page=<page to show>&zoom=<zoom%>,<x>,<y>` to open up the specified PDF file in a specific page and specific point (x, y).
