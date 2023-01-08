# PDF Cordinate Finder

### How it works?

It is a flask application with a simple user interface. We can upload a file in landing page. While we uploading image the PDF will be converted into image and stored on static folder. Then we will navigate to another page. In this page, we will load this image on a canvas with the help of [konva.js](https://konvajs.org/). We can draw rectangle on canvas, then it will return bounding box like shown below:

    (x0, y0)-----------------------------
            |                           |
            |                           |
            |                           |
            -----------------------------(x1, y1)

### Installation

1. Enable virtual environment:
   1. This step depends on your operating system. If you are new please follow [this guide](https://www.geeksforgeeks.org/creating-python-virtual-environment-windows-linux/)
2. Install requirements with the help of command `pip install -r requirements.txt`
3. Run development server using: `python run.py`. **Remember it is not a production ready server.**