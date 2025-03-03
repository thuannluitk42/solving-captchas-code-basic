# solving-captchas-code-basic
[How to break a CAPTCHA system in 15 minutes with Machine Learning](https://medium.com/@ageitgey/how-to-break-a-captcha-system-in-15-minutes-with-machine-learning-dbebb035a710)

## Installing

```
pip3 install h5py
```

### Before you get started

Let's install this library below

1. Python 3
2. Installed OpenCV 3. I think you follow https://www.pyimagesearch.com/opencv-tutorials-resources-guides/ 
3. Running "pip3 install -r requirements.txt"

### Step 1: Extract single letters from CAPTCHA images

Run:

python extract_single_letters_from_captchas.py

The results will be stored in the "extracted_letter_images" folder.


### Step 2: Train the neural network to recognize single letters

Run:

python train_model.py

This will write out "captcha_model.hdf5" and "model_labels.dat"


### Step 3: Use the model to solve CAPTCHAs!

Run: 

python solve_captchas_with_model.py