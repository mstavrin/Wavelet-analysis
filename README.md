Wavelet-analysis
================

Using complex morlet function to analyze any kind of data. 

It has been used for EEG datasets but it has been checked on artificial simple sinuoisidal signals and it works well!
Initial parts were taken from 4-D toolbox of Ole Jensen. Personal communication with him (at the time this was writen) gave the correct value of the parameters. These functions can be found in the toolbox "Fieldtrip". 

Due to the contribution of Luca Cancietta (scientific programmer at ITAB, University G. D' Annunzio, in 2003) a point-by-point convolution in time domain is given as an option (energyvec2.dll and energyvec3.dll functions). The simple Fourier invoking convolution is given with the energyvec.m function.

It has been used in 3 of mine publications in this or other forms. Here a simple version is given where an artificial signal is given as an input. The user can change the frequencies of those two basic signals as he wants!


