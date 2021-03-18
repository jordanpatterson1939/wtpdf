# wtpdf
Save webpage to pdf from the terminal
**Note: Requires wkhtmltopdf**

## Installation
```text
pip install wtpdf
```

## Usage
```text
wtpdf https://insert-url-here
```
> Navigate to $HOME/Downloads/WebToPDF, the file will be named after the title of the webpage


Todo:
> Some of the resulting pdfs are unreadable and the methods(libraries) 
> used for conversion are not always reliable. To fix this, rework the 
> script to open the link in the browser instead and take screenshots as 
> it scrolls down the page in fullscreen. After it has reached the bottom 
> of the page, the browser should be closed and the processing of images 
> into a single pdf file should be done. This will remove the need to use 
> external libraries and/or programs(wkhtmltopdf) when converting while also 
> achieving better resulting pdfs.
