## Audio Dataset Analysis for Laplacian Noise estimation
This study explores the analysis of audio datasets for Laplacian noise estimation.
With noise being a significant concern in audio applications, we propose techniques to estimate Laplacian noise parameters directly from audio data.
Our framework includes parameter estimation, correlation analysis, alongside statistical modeling and joint probability density evaluation methodologies used to estimate the Laplacian noise of audio dataset are all thoroughly investigated in this research.

## Technologies used:
Python, Google Collab

## Methods Used :

1. Distribution Models 
We employed various distribution models to characterize the probability distribution of Laplacian noise. These models include: 
**Gaussian Distribution:** Also known as the normal distribution, this model assumes a symmetric, bell-shaped curve. 
**Gamma Distribution:** Used for continuous, positive-valued variables, the Gamma distribution is characterized by its shape and scale parameters. 
Inverse Gamma Distribution:This distribution, the reciprocal of the Gamma distribution, is suitable for modelling positive-valued variables with a right-skewed distribution.
**Exponential Distribution:** Describing the time between events in a Poisson process, the Exponential distribution is commonly used for modelling waiting times. 
**Rayleigh Distribution:** Frequently used to model the magnitude of vectors, such as wind speeds or wave heights, the Rayleigh distribution is characterized by a right-skewed shape.

2. Parameter Estimation 
We compared two estimation techniques to determine the parameters of the selected distribution models: 
Maximum Likelihood Estimation (MLE): This method estimates the parameters that maximize the likelihood of observing the given data, assuming a particular distribution model. 
Method of Moments (MOM): MOM estimates the parameters of a distribution by equating sample moments (e.g., mean and variance) to theoretical moments. 

3. Correlation Analysis 
To understand the relationship between the two components of audio data namely skewness and kurtosis, we conducted correlation analysis using appropriate correlation coefficients.
4. Joint Probability Density Assessment 
We evaluated the joint probability density function (PDF) of magnetometer data by comparing it with the product of the individual PDFs of each component. This assessment provides insights into the joint distribution of the data, highlighting any deviations from the product of individual PDFs.
