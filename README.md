<div id="top"></div>


<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="https://user-images.githubusercontent.com/80456274/169072439-df8464f7-d2ac-4582-bbac-387bc7ac4ca0.png" alt="Logo" width="550" height="380">   
    <h2 align="center">LSB based Image steganography using MATLAB</h2>
    <h3 align="center">Final projects</h3>
</div>

<!-- TABLE OF CONTENTS -->

  <summary>Table of Contents</summary>
  <ol>      
      <a href="#about-the-project">About The Project</a>         
  </ol>
  <ol>
    <li>
      <a href="#Part-I">Part I : </a>
         <ul>
              <li><a href="#"> </a></li>
              <li><a href="#"> </a></li>
              <li><a href="#"> </a></li>
           </ul>
    </li>
        <li>
            <a href="#Part-II">Part II :  </a>
            <ul> 
              <li><a href="# "> </a></li>
              <li><a href="# "> </a></li>
              <li><a href="# "> </a></li>
            </ul>
           </li> 
        <li><a href="#Part-III">Part III : </a></li>
   </ol>



<!-- ABOUT THE PROJECT -->
# About The Project
This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

1. [**How to install MATLAB in Windows**](https://www.youtube.com/watch?v=WdJ7OGOa4Jo)
2. **Clone the repo**
   ```sh
   git clone https://github.com/IlyasKadi/LSB-based-Image-steganography-using-MATLAB.git
   ```
 
<p align="right">(<a href="#top">back to top</a>)</p>

<div align="center">
    <img src="https://user-images.githubusercontent.com/80456274/152737429-ada47ee7-6b52-4803-8831-c5182fbce0b8.gif" alt="tuto-game" width="550" height="380">  
    <h5><font color='gris'>LSB based Image steganography</font></h5>
</div>



# Part-I 

# Image Steganography using LSB Algorithm
## Files

<pre>
In image steganography the information is hidden exclusively in images. The most common and popular method 
of modern day steganography is to make use of LSB (least significant bit) of picture's pixel information. 
This technique works best when the file is longer than the message file and if image is grayscale.

<div align="center"> 
<img src="https://user-images.githubusercontent.com/80456274/169081373-27614d4a-8c7a-44ee-9343-e7d4a8a4824c.png" alt="Program GUI"/>
</div>


Matlab program for Image Steganography using Least Significant Bit (LSB) Algorithm with the following features:
- Hiding text data in a selected  image.
- Extract text data from a selected image.
- Analyze and compare between the original and stego-image (PSNR and Histogram)
</pre>
## Files
<pre>
<b>LSB.m :</b> GUI for the program.
<b>LSB_HIDE.m :</b> Hide function.
<b>LSB_EXTRACT.m :</b> Extracting function.
<b>Calc_PSNR.m :</b> PSNR calculator function.
</pre>


# Part-II

## How to Run Program
<pre>
1. Download project.
2. Open MATLAB program.
3. Open the directory of the project.
4. Open <b>LSB.m</b> file and click Run button.

You will see this GUI:
<img src="IMG_SCREENSHOTS/Program GUI.jpg" alt="Program GUI" height="400"/>
</pre>

## How to Hide
<pre>
1. Run program.
2. Click on Hide tab.
3. Click on "Select Cover Image" button and select your original image.
4. Click on "Select a Text" button and select your text.
   (I have added examples of different 500, 4000 and 32000 character sizes for test).
5. Click on "Encrypt" button that will ask you for path to save.
5. You will see a PSNR will automatically.
6. Click on "Statistics" button for Histogram between the original and stege-image.

After Hiding <b>msg-4000ch.txt</b> you will see this:
<img src="IMG_SCREENSHOTS/Stego-with-4000ch.jpg" alt="Hide 500ch inside Image" height="400"/>
</pre>

## How to Extract
<pre>
1. Run program.
2. Click on Extract tab.
3. Click on "Select Stego-Image" button and select your stego-image.
4. Click on "Extract" button that will ask you for path to save.
5. You will see an Alert tell you "Extracted done".
6. Open the path then you will see your extracted file.

After Extracting <b>stego-img500.bmp</b> you will see this:
<img src="IMG_SCREENSHOTS/Extracted.jpg" alt="Extract Program" height="400"/>
Your extracted file <b>Recover-msg.txt</b>:
<img src="IMG_SCREENSHOTS/Recover-msg.jpg" alt="Extract" height="200"/>
</pre>

## Histogram
<pre>
<img src="IMG_SCREENSHOTS/Histogram-orig-32000ch.jpg" alt="Histogram between original and stego4=32000ch image" height="400"/>
<b>Histogram between original image and stego-image after hiding 32000 character:</b>
</pre>

# Last-words

## Notes
- The higher PSNR indicates that the quality of the stego-image is similar to the cover image.
- The larger image size, the more data you can hide.
- For a 24-bit color image as the cover image, you can store approximately 3/8th of the cover image size.
- For a grayscale image as the cover image, you can store approximately 1/8th of the cover image size.


-------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Our Team     : [AIT EL KADI Ilyas](https://github.com/IlyasKadi) - [AZIZ Oussama](https://github.com/ATAMAN0)  
 
   Project Link : [LSB based Image steganography using MATLAB](https://github.com/IlyasKadi/2048-Game)   
 
  > Encadré par  : [Mme.Mouhtadi Meryeme](https://github.com/IlyasKadi/LSB-based-Image-steganography-using-MATLAB)  
                                                                                             
<p align="right">(<a href="#top">back to top</a>)</p>

