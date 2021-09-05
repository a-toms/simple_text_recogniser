# Simple text recogniser

Simply recognise text in png images using Python.

## Install
0. Clone the repo and enter it.
1. Create a new virtual env and activate it:
`python3 -m venv env` and `source env/bin/activate`
2. Install python dependencies:
a) `pip install -r requirements.txt`
3. Install the tesseract binary:
`brew install tesseract` or try `brew install tesseract-lang` if using an M1 macbook.


## Run
0. Make sure that your virtual environment is activated.
1. `python3 main.py path_to_image_file_with_text.png`


![](./example.gif)
