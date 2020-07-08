# MiNiMAP
This repository just contains the masters thesis. You can view a video summary of MiNiMAP [here](https://youtu.be/Ff8oj5HhLFM). If you wish to obtain access to the code repositories used to create MiNiMAP, please contact me. The repositories are as follows:
## MiNiMAP - Networking
Contains all of the Raspberry Pi images and Python files that were used to create a network of AWR1642 millimeter wave (mmWave) radars. 
## MiNiMAP - Sensors
Contains all of the C code that was changed from Texas Instruments' (TI) implementation. The C code was flashed to each AWR1642 to enable multistatic radar operation. 
## MiNiMAP - Processing
Contains all of the MATLAB and Python code used to process the I/Q data received from each AWR1642. The output is a series of target state estimates that is compared with the true target states in order to assess the performance of Bayesian filtering algorithms.
