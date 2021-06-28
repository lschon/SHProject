# SHProject
For the 4th Year Physics Senior Honours Project: Sequential Image Analysis in a Bayesian Framework by Lucas Schön.
This is a Jupyter Notebook .ipynb project with associated (compressed) TEM colloid images for the SH project.

The code reads in the folder and the file to be analysed can be selected by the user.
The image is then watershedded to determine the areas of the particles and these are made into a list and converted into radii.
The radii are plotted using a histogram and this histogram is fitted with Gaussian and Lorentzian functions.
This produced optimised values and errors for the peak value x_0 and the standard deviation/HWHM sigma/gamma.
These are plotted along with the reduced chi squared values for each fit.
Then the posterior ratio is calculated and plotted, using an equation defined in the paper for this project.
Repeated over as many trials as one wishes.

Enquire at s1718492@ed.ac.uk for more information.
