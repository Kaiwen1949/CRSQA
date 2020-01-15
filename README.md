# CRSQA Dataset

This repository is to provide the relative tools for the research about 360 omnidirectional stitching images quality assessment.

About the study report, our lab cvteam had published the paper 《Cross-Reference Stitching Quality Assessment for 360 Omnidirectional Images》 on ACM Multimedia 2019.

[//]:#![Motivation](https://github.com/Kaiwen1949/CRSQA/blob/master/Motivation.PNG)

## Introduction
Cross-Reference Omnidirectional Stitching data Set (CROSS) is a large dataset for 360 omnidirectional images stitching quality assessment.
<table>
    <tr>
        <td><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Motivation.PNG" >Motivation</center></td>
        <td><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/pipeline.PNG" >Pipeline</center></td>
    </tr>
</table>

There is in total 16 senses divided into indoor and outdoor two categories. The dataset is organized as follow:
* Indoor: Meeting room、Class room and Reading room,etc.
* Outdoor: Park、Street and Court,etc.
320 groups quaternion images in total, each group is combined by 7 algorithm stitching results and 4 raw double-fisheye images.

## Functions
The dataset can be used in omnidirectional image stitching quality assessment and stitching algorithm evaluation.
* Add specific immersive image in quaternion group images, you can get the relative quality result among the images.
* User utilizes a new stitching algorithm or your own method stiched result get the algorithm quality rank. (The average quality may better.)

Each group images are composed by fisheye image and 7 omnidirectional stitching images which are as follow:
<table>
    <tr>
        <td ><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/360_0792_lowresolution.JPG" >Fisheye</center></td>
        <td ><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/samsung_lowresolution.jpg">samsung</center></td>
       <td><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/opensource_lowresolution.jpg">opensource</center></td>
       <td ><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/weimethod_lowresolution.jpg">weimethod</center></td>
</tr>
            
<tr>
        <td><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/SVP_lowresolution.jpg">SVP</center></td>
        <td><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/manmethod_lowresolution.jpg">manmethod</center></td>
        <td><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/IP_lowresolution.jpg"> IP</center></td>
        <td><center><img src="https://github.com/Kaiwen1949/CRSQA/blob/master/Images/EP_lowresolution.jpg"> EP</center></td>
</tr>
</table>

## Download dataset
Link: https://pan.baidu.com/s/1fpCnGoFRfEb9Zfab_WnFHQ
