---
layout: minimal
title: Stitched Image Quality Assessment
subtitle: Postdoc at CMU / Software Engineer / and more
---
# Quality Assessment of Stitched Images

### Introduction
Virtual Reality (VR) refers to technologies that enable the virtual presence of an individual in a different environment. In recent days VR is gaining popularity due to its wide applications ranging from education, motion pictures, games to medicine and healthcare. VR aims to provide realistic and immersive experience in virtual environments to the users through panoramic images and videos. Panoramic images are typically viewed on head mounted displays (HMD) where the viewer can determine the desired view. In this work we design a dataset containing 264 panoramic images obtained using various stitching algorithms and conduct a large scale subjective study to collect around 25 human opinion scores for each image. The subjective study involves collecting human ratings when images are viewed on a HMD as applicable to virtual reality. The dataset as well as human ratings are used to train and evaluate objective QA models. We also design
the Stitched Image Quality Evaluator (SIQE) by devising statistical features using steerable pyramid decompositions. We hope that our database (images and subjective data) as well as the software associated with SIQE will serve as a valuable resource to enable the efforts of the research community to build better quality predictive models for stitched images and to benchmark their performance to advance the state-of-the-art in objective quality assessment of stitched images.

![alt text][logo]

[logo]: https://github.com/pavancm/stitched-qa/tree/master/img/404-southpark.jpg "Logo Title Text 2"

### Database Description
The goal of this study was to characterize the distortions that arise during the process of stitching and quantify them based on human perception. The IISc Stitched Image Quality Assessment (ISIQA) Database contains 264 stitched images obtained from multiple stitching algorithms from 26 different scenes. Each scene consists of around 5 images captured from differing viewpoints and having overlapping regions between them. Quality of stitched image is affected by the choice of the stitching algorithm. The images were evaluated by 35 subjects by viewing them on a Virtual Reality HMD to obtain human opinion scores.

Details of the content, design of the database and processing of human opinion scores can be found in:

P. C. Madhusudana and R. Soundararajan, "Subjective and Objective Quality Assessment of Stitched Images for Virtual Reality", June 2018.

### Database Download
We are making the ISIQA Database available to the research community free of charge. The database can be downloaded [HERE](http://ece.iisc.ac.in/~rajivs/databases/isiqa_release.zip). The database file isiqa_release.zip containes 2 folders and a text file.

- *Constituent Images:* images of 26 scenes captured from different viewpoints.
- *Stitched Images:* 264 stitched images obtained from multiple stitching algorithms.
- *MOS.txt:* contains mean opinion scores for each stitched image.

Please fill [THIS](https://goo.gl/forms/9ghT7Vu9pThhlNo93) form and the password will be mailed to you.

### Software Release
We are releasing the MATLAB implementation of SIQE. The codes can be downloaded [HERE](https://github.com/pavancm/Stitched-Image-Quality-Evaluator)

If you use the database or software in your research, we kindly ask that you reference our paper:

P. C. Madhusudana and R. Soundararajan, "Subjective and Objective Quality Assessment of Stitched Images for Virtual Reality", June 2018 

Please contact Pavan (pavan.madhusudana@gmail.com) if you have any questions.

### Investigators
The investigators in this research are:

- Pavan C M (pavan.madhusudana@gmail.com)
- Dr. Rajiv Soundararajan (rajivs@iisc.ac.in) -- Department of ECE at IISc Bangalore

