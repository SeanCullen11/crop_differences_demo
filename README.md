# Manual Crop, Click Crop, and Auto Crop Time 


This is meant to illustrate how much time is saved between these cropping tools for scientific images. I will walk you step
by step on how to crop a photo in 3 ways, manually with the windows photo editor, using the click_crop program, and finally using the auto_crop python program. This will help illistrate the time that can be saved with these programs. Along with this, graphs and data to show the time saves between each method of cropping 


---

## Intro to project
My name is Sean Cullen and I am currently a senior Computer Science major at NEIU. I've been working with Beth over the past 2 months to process leaf images from the Field Museum's herbarium and get them into the correct format to be fed into a neural network. This involves taking our images of 10 leaves and segmenting them into individual leaf images. This process can be done in many ways, but some ways are much more time efficient than others. This demo will help demonstrate those differences in time efficiency. 

## Intro to Github
Welcome to Github! This an environment very familiar to a Computer Science students such as myself but might not be for you. This is a website used for people to display and share programs they have made. Though using it can be intimidating at times, it's an excellent tool for developers and scientist to share their work. This project, crop_differences, is available to download so you can open and even run my code on your computer. Below will be instructions on how to execute each type of crop method

## Installing the repo
1. Find the green code button in the upper right area of the screen
2. click on the down arrow on the right
3. Click 'Download ZIP'
4. Open the ZIP file and extract it to a desired location on your computer 
5. The openable folder labeled 'crop_differences_demo-master' has all the needed files

## Manually Crop Images using Windows Photos
1. Open Windows Explorer and navigate to the crop_difference folder
1. Open sampleimage.jpg 
1. click the button crop in the top menu 
1. size the box to fit just the leaf in the upper lefthand corner
1. Hit 'Save as copy'
1. Select the project folder to save it in 
1. Name the new image and hit save
- After each leaf the photo needs to be reopened and this process repeats for each leaf
- This is the process that would need to be done on all 10 leaves in all 100 photos
  - taking 30-45 seconds per leaf 
  
Manual Crop Example: 
https://drive.google.com/file/d/15Ivv2Hdhk_74feMjDyNGZq72tNlGG4jK/view?usp=sharing

## Click Crop
* This is only executable with an instance of Python 3 installed on your local computer
1. In the command line interface (PowerShell on Windows, Terminal on a Mac), change your working directory to crop_differences_demo using 'cd (file path to your crop_difference folder)
   * example: 'cd C:\Users\Sean\PycharmProjects\crop_differences'
2. Type `pip -r requirements.txt` and wait for packages to install
3. Next type in `python click_crop.py sampleimage.jpg` and hit enter
4. A box will pop up with the sample image displayed
5. Find the leaf in the upper left hand corner 
6. Click first in the upper left hand corner of that leaf, then in the lower right hand corner capturing the entire leaf 
7. Close the image
8. The leaf has been cropped and saved, look in the project folder for the new image. Should be saved as crop_differences_sampeimage_1
- 4-5 seconds a leaf 

Click Crop Example: 
https://drive.google.com/file/d/1KdP3_PZqEYQFgo5P6pnLr6v2njChuLEh/view?usp=sharing 



## Auto Crop
1. Make sure you have the crop_difference folder downloaded 
1. Click Google Colab link below
1. Click the folder icon in the left sid eof the screen 
1. Click the "Upload to session storgae" button in the top left 
1. Go to your crop difference folder and select "sampleimage.jpg", wait for it to upload
1. Run the first code block of import statements
1. Run the second code block and scroll down to the bottom of the page to see the results 
1. You'll see the image displayed with each leaf selected and that each leave has been cropped and saved
1. Check the left hand side to see that all the new leaf images are saved there 

- .4 seconds a leaf 

Auto Crop Example: 
https://drive.google.com/file/d/11JnmifanwKmvVY4aW_9e8Ab_oU49vcaJ/view?usp=sharing 

Auto Crop Colab: 
https://colab.research.google.com/drive/1zo7i5ofDCsCv--TXrYBsewqW2q9ts7Ok?usp=sharing

## Graphs of crop times
![alt text](Crop_Differences_Per_Leaf_(secs).png)

![alt text](Crop_Times_for_100_leaf_images_with_10_leaves_(mins).png)

![alt text](Crop_Times_for_100_leaf_images_with_10_leaves_(hours).png)
