Conjure 2 Covert Comms
=

Contents
-
-static

-templates

-`app.py`

-`download.py`

-`encode.py`


Requirements
- 
- Must have Python3 installed
  - Must have the libaries `Flask` and `Pillow` installed (these usually
  come with Python, but if they are not downloaded run the command
  `pip3 install <library>` where <library> is the library to install)

Setup
-
- Have an image preferably in the jpg format

How to use
-
- **Encoding & decoding the image**
  - Linux
    - Run `python3 encode.py -e`
    - Type in your image name with the extension (this accepts 
    location information relative to `encode.py`)
    - Enter the string you want to be encoded
    - Enter the title of the post you will make (the key for the encryption)
    - Enter the name of your new image file (include the `.png` suffix)
  - Windows
    - Run `python.exe encode.py -e`
    - Type in your image name with the extension (this accepts 
    location information relative to `encode.py`)
    - Enter the string you want to be encoded
    - Enter the title of the post you will make (the key for the encryption)
    - Enter the name of your new image file (include the `.png` suffix)
- Decode
  - Linux
    - Run `python3 encode.py -d`
    - Type in your image name with the extension (this accepts 
    location information relative to `encode.py`)
  - Windows
    - Run `python.exe encode.py -e`
    - Type in your image name with the extension (this accepts 
    location information relative to `encode.py`)
- **Running the website**
  - Linux
    - `python3 app.py`
  - Windows
    - `python.exe app.py`
  - Access the website by visiting `localhost:5000` on any web browser

Credit
-
- Alan Middleton
- Nolen Shubin
- Quillen 'Q' Flanigan