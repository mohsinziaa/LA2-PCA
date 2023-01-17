## How to handle Large Datasets? → PCA comes to rescue!
<br>
Many satellites continuously roam around the earth and an important type of satellites is known as 
the ‘Earth observation Satellites’ [1] which observe the earth from the space using several sensors, 
such as cameras etc. This largely falls in the discipline of ‘Remote Sensing’ [2]. The images from the 
cameras onboard the satellites can be used for several purposes, and one important application is 
known as ‘land mapping’ [3], in which different areas on the land are mapped to different classes 
such as water, forests, crops, buildings, snow etc. Such information is useful in applications such as 
urban planning, water and crops monitoring, disaster management etc.
<br><br>
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
be obtained from the link [7].<br><br>

## Main Objective:
<br>
Your main objective is to perform principal component analysis (PCA)
[8] on a multispectral image and perform associated. analyses that image using any appropriate platform/language (Matlab, 
Python etc.) and give results on error increase/decrease with respect to different number of 
principal components chosen to represent that image. <br>

## Tasks:
<br>
[1]. Develop understanding of multispectral/multidimensional images, download a Landsat 
image of a location from USGS website (could be any location of interest in Pakistan, 
however, images for any 2 groups should not be same – this would be done by mentioning 
your chosen location on a shared MS Teams files) and perform basic operations (visualize 
different bands, crop size in any dimension, concatenate bands etc.) with the image in any 
suitable platform (Matlab, Python etc.)
<br><br>
[2]. Develop understanding of PCA, including how does it help in the processing of 
multidimensional images and how does PCA relates to the concepts from the course of 
Linear Algebra II, and apply PCA to your image such that you are able to demonstrate that 
PCA could be performed using any number of principal components by your code.
<br><br>
[3]. Perform an error analysis on the use of PCA on your image by choosing different number 
of Principal Components and calculate the resulting error in each case. You should be able 
to demonstrate the usefulness of the PCA approach in comparison to its non-usage based 
on the error analysis. Also recommend a suitable number of Principal Components to be 
used based on the error analysis. You can calculate the error by comparing the PCA 
resulting image with the original image and using any suitable difference metric e.g. mean 
square error etc.
<br><br>
[4]. CEP report, which your team will use to give a viva on your CEP as well. The report should 
be of standard format with no more than 5 pages in double-column format – preferably use 
the IEEE Word template for conferences [9]. The report should include the sections of Title, 
Authors, Abstract, Introduction, Methodology, Task distribution (this section should be 
reasonably explained as there is a dedicated CLO regarding it in this assignment), Results, 
Conclusion and References. Any item other than these can be put in the appendices. You 
can also make a separate PowerPoint presentation for your viva, if it suits you more, but it 
is not mandatory.
<br><br>

## References:
1.  https://en.wikipedia.org/wiki/Earth_observation_satellite
2.  https://en.wikipedia.org/wiki/Remote_sensing
3.  https://www.un-spider.org/links-and-resources/data-sources/daotm-landcover
4.  https://en.wikipedia.org/wiki/Multispectral_imaging
5.  https://en.wikipedia.org/wiki/Landsat_program
6.  https://landsat.gsfc.nasa.gov/
7.  https://gisgeography.com/usgs-earth-explorer-download-free-landsat-imagery/
8.  https://en.wikipedia.org/wiki/Principal_component_analysis
9.  https://www.ieee.org/conferences/publishing/templates.htm

