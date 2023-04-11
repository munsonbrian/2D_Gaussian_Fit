# 2D_Gaussian_Fit
2D Gaussian Fit for use in Image Detail Enhancement 

LmFit, a curve fitting package for python, was utilized to fit a 2D gaussian distrubution a slide illuminated by a Argon Ion laser.
Because laser is known to emit a gaussian wave front, a mutivariate gaussian distrubution was chosen to be a good fit of the data.

Current iteration of this tool failed to eliminate background adequately. Further assesment of performance can be done by conplaing the intensity profiles of the image histograms before and after subtraction of the best fit gaussuan distrubution.

Further improvements will incliude the use of a FFT to further reduce noise after optimising the fitment of a 2D gaussian distrubution and exploring fititng tools provided by SciKit Learn.
