# Manual Crop, Click Crop, and Auto Crop Time 


This is meant to illustrate how much time is saved between these cropping tools for scientific images. I will walk you step
by step on how to crop a photo in 3 ways, manually with the windows photo editor, using the click_crop program, and finally using the auto_crop python program. This will help illistrate the time that can be saved with these programs. Along with this, graphs and data to show the time saves between each method of cropping 


---

## Set Up
1. Make sure the folder crop_differences is downloaded and contains click_crop.py, auto_crop.py, cropped_image_data.csv, and auto_crop_image_data.csv
1. 
1. 

## Manual Crop
1. Go to file folder for this project
1. Open sampleimage.jpg 
1. click the button crop in the top menu 
1. size the box to fit just the leaf in the upper lefthand corner
1. Hit 'Save as copy'
1. Select the project folder to save it in 
1. Name the new image and hit save
- After each leaf the photo needs to be reopened and this process repeats for each leaf
- This is the process that would need to be done on all 10 leaves in all 100 photos
  - taking 30-45 seconds per leaf 

## Click Crop
1. Run click_crop.py
1. A dialogue box will pop up and ask you to select an image, select sampleimage.jpg and hit open
1. Find the leaf in the upper left hand corner 
1. Click first in the upper left hand corner of that leaf, then in the lower right hand corner capturing the entire leaf 
1. Close the image
1. The leaf has been cropped and saved, look in the project folder for the new image. Should be saved as crop_differences_sampeimage_1
- 4-5 seconds a leaf 

## Auto Crop
1. Run auto_crop.py
1. A dialogue box will pop up and ask you to select an image, select sampleimage.jpg and hit open
1. The program will take a second to detect the leaves in the image then display the segmented image 
1. See how the leaves are highlighted by the red boxes automatically by the program 
1. Close the program and wait around 5 seconds for the pictures to crop and save automatically 
1. Check the folder and see that there are now 10 new cropped photos as well as the black and white threshold photo teh computer used to find the leaves 
- .4 seconds a leaf 
