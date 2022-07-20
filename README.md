# Machine-Perception
Program to read and detect numbers on an image.

# 1) Description of Project
This project aims to use the library called OpenCV (open Computer Vision) in Python to locate numbers and then predict the number from an image an write it to an output file.

At the moment, the program works for white (light) coloured numbers with a black background. You can see the photos within the **"test"** folder and can even add your own images too!!

# 2) Getting started
To run the code in Python, first we need to get the environment. 

## NOTE:

- If you are using Linux, just open a directory and run the following commands. 
- If you using Windows, get the Linux Terminal from Microsoft Store (search up on Google if you don't know how to get around this).

## Follow the steps to get started:

#### i) Git clone the repository and extract the "train.zip" folder:

#### ii) Install Virtual Environment:
```shell
$ pip3 install virtualenv
```

#### iii) Activate the Virtual Environment:
```shell
$ python3 -m venv env
$ source env/bin/activate
```

#### iv) Install the required packages:
```shell
$ pip3 install -r requirement.txt
```

#### v) This step is for *Windows* users only (For Linux users, skip this step):
> When the Python file is run, it will display images. To view them, a software called Xming needs to be downloaded. 

> a) To download Xming, follow this link and click download: 
   - https://sourceforge.net/projects/xming/
> b) After Xming is downloaded, run the following command to see if it works:
```shell
$ xeyes
```
- If you see a small pop-up window with eyes, it works!
- if you don't see it, maybe try another version of Xming.

#### vi) Now to run the code:
```shell
$ python3 digit_extraction.py
```
> The code will take some time to run...
> Just press enter to run through the images, and you can see what number is detected in the "Output folder"!


# We are done! 








