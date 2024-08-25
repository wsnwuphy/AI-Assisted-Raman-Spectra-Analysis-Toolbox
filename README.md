# AI-Assisted-Raman-Spectra-Analysis-Toolbox
 Introduction
-------
This software is developed based on Matlab R2022a, which uses the app designer function to design the original software interface and function buttons, and on this basis, it is encapsulated into an application plug-in that can be used on Matlab to improve portability. The software mainly includes three modules: data processing, machine learning and model usage.

Requirements
-------
Operating system: Windows 10/Windows 11, 64-bit system;
Operating environment: Matlab R2022a and above installed.

Installation
-------
Users need to pre-install R2022a or above version of matlab, first of all, in the matlab current folder area to find the downloaded application plug-in installation package (Al Assisted Raman Spectra Analysis Toolbox.mlappinstall ), click to install it and then you can find the software in the App toolbar of matlab and use it.

Use
-------
1. Input data: three variables including spectral intensity matrix (N×M), wave number variable (N×1) and compound measure (M×1) (where N denotes the number of spectral features and M denotes the total number of spectra, i.e., each column in the dataset denotes the observed spectra).
2. Data processing: it includes a series of functions such as wavelength interpolation, spectral preprocessing, data segmentation and data augmentation.
3. Machine Learning: The software provides four model fitting algorithms: back-propagation artificial neural network (BP-ANN), convolutional neural network (CNN), partial least squares regression (PLSR), and support vector regression (SVR), and the corresponding parameters of the algorithms can be set in the parameter settings.
4. Model use: the trained model will be used for subsequent prediction of compound measurements from spectral data.
Released under MIT license

Contact
-------
Wang Shuang: swang@nwu.edu.cn
