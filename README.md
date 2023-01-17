## How to handle Large Datasets? → PCA comes to rescue!
<br>
Many satellites continuously roam around the earth and an important type of satellites is known as 
the ‘Earth observation Satellites’ [1] which observe the earth from the space using several sensors, 
such as cameras etc. This largely falls in the discipline of ‘Remote Sensing’ [2]. The images from the 
cameras onboard the satellites can be used for several purposes, and one important application is 
known as ‘land mapping’ [3], in which different areas on the land are mapped to different classes 
such as water, forests, crops, buildings, snow etc. Such information is useful in applications such as 
urban planning, water and crops monitoring, disaster management etc.
<br>
The earth observation satellites use different types of cameras to take pictures of the earth’s land 
cover. One type of camera, which is commonly used in earth observation, is the multispectral 
camera which takes multispectral images [4] of different locations on earth. Multispectral images are similar in nature to the normal colored images which we use in our everyday life, however instead of just 3 bands (Red, Green and Blue) which are in regular color images, there are more 
number of bands in a multispectral image (generally between 6 to 30 bands). The large number of 
bands allows one to distinguish between different land cover types (crops, forests, water, land, etc.) 
in a better manner as compared to using only the regular colored/RGB images. Landsat is one of the 
world’s largest satellite program for earth observation which is run by the US government. Some 
details about the Landsat program are also given in the introductory example of chapter 7 of your 
textbook, and more can be obtained from the references [4][5]. The Landsat program keeps an 
repository of the earth’s images taken and allow anyone to download the images for any location 
using its online platform https://earthexplorer.usgs.gov/ . The details on how to download data can 
be obtained from the link [7].
