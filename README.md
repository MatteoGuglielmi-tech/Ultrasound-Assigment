# Table of contents
1. [Ultrasound techiniques for medical applications assigment](#title)
  1. [Project statement](#state)
  2. [Results](#res)
  
# Ultrasound techiniques for medical applications assigment <a name="title"></a>
## Problem Statement <a name="state"></a>
In this specific repository, you can find a possible solution to characetrize the acoustic properties of an unknown medium. The experiments were conducted inside the [ULTRa Labortory](https://sites.google.com/view/drlibertariodemi/ultrasound-lab) in University of Trento, Italy. In particular, the code is meant to carry out the following requests :
- compute an estimation of the acoustic SOS in the medium
- estimate the attenuation coefficient of the gelatine as a function of depth and frequency

## Results <a name="res"></a>
The estimated speed of sound, averaged across 5 files to smooth out some noise, turned out to be $1514 m/s$ with a variance of $~23m/s$.  
Concerning the coefficient attenuation, the most suitable model turned out to be the one with an expontential kernel. The fitted curve tells that with the increase in frequency, the attenuation coefficient tends to increase which is reasonable since the wavelengths of sound at higher frequency are shorter, i.e. the sound waves have a higher number of cycles in a given distance. This makes it easier for the sound waves to be absorbed or scattered by the particles in the medium, leading to a greater amount of attenuation.
