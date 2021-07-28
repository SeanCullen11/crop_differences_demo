# Manual Crop, Click Crop, and Auto Crop Time 


This is meant to illustrate how much time is saved between these cropping tools for scientific images. I will walk you step
by step on how to crop a photo in 3 ways, manually with the windows photo editor, using the click_crop program, and finally using the auto_crop python program. This will help illistrate the time that can be saved with these programs. Along with this, graphs and data to show the time saves between each method of cropping 


---


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
  
Manual Crop Example: 
https://drive.google.com/file/d/10po35P8ZXJkW8gyPmAgYHNLQhpCvUnPN/view?usp=sharing

## Click Crop
1. Run click_crop.py
1. A dialogue box will pop up and ask you to select an image, select sampleimage.jpg and hit open
1. Find the leaf in the upper left hand corner 
1. Click first in the upper left hand corner of that leaf, then in the lower right hand corner capturing the entire leaf 
1. Close the image
1. The leaf has been cropped and saved, look in the project folder for the new image. Should be saved as crop_differences_sampeimage_1
- 4-5 seconds a leaf 




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
https://drive.google.com/file/d/192qQT0Du4cn2HgSw_onQ4DUiYVHIAFmP/view?usp=sharing 

Auto Crop Colab: 
https://colab.research.google.com/drive/1zo7i5ofDCsCv--TXrYBsewqW2q9ts7Ok?usp=sharing