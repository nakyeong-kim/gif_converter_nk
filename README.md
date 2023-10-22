# pygifconvt

## Table of Contents
  * [Installation](#installation)
  * [Quick start](#quick-start)
  * [Features](#features)
  
## Installation

Download using pip via pypi.

```bash
$ pip install gif-converter-nk --upgrade
  or
$ pip install git+https://github.com/nakyeong-kim/gif_converter_nk.git
```
(Mac/homebrew users may need to use ``pip3``)


## Quick start
```python
 >>> from gif_converter_nk.gif_converter import GifConverter
 >>> c = GifConverter("your original images path", 'your gif output path', (320,240))
 >>> c.convert_gif()
```

## Features
  * Python library to convert single oder multiple frame gif images
  * OpenCV does not support gif images.
