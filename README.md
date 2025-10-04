# PDF to PNG Converter (GUI)

This is a simple Python desktop application that allows you to convert all PDF files in a selected directory into PNG images using a graphical user interface (GUI) built with `tkinter`.

##  Features

- Select a folder containing PDF files.
- Converts each page of each PDF into PNG format using `pdf2image`.
- Saves output images in a newly created `toPNG` folder inside the selected directory.
- Automatically opens the output folder after conversion.
- User-friendly interface with minimal clicks.

##  Requirements

- Python 3.x
- [poppler](https://github.com/oschwartz10612/poppler-windows/releases/) (Ensure it's placed inside a `bin` folder in the same directory as the script)
