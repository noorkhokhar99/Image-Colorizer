# Image-Colorizer
Transform black and white images into beautifully colored images using Deep Learning.


# Requirement
- Python
- OpenCV 
- Numpy
  

# Usage

- Clone this Repository
```
git clone https://github.com/noorkhokhar99/Image-Colorizer.git
cd ImageColorizer
```

- **[Important]** Download the model from the following [link](https://drive.google.com/drive/folders/1hNvYYq9i7XYMhv9AtH9bFXRpxP8YcGo_?usp=sharing) and place it in the `model` folder

- Now execute the following command -
```
python imagecolorizer.py --image <path_to_image>
```
This script requires one argument to be passed to the script directly from the terminal, i.e. **--image** or **-i** which is the path to our input black/white image. All the colorized images will be saved in the `output` fold
