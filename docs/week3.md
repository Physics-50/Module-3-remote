# Week 3

This week you will continue your investigation of the wavelength of your laser. We would like you to follow an identical procedure to last week. However, instead of making use of the 500 lines/mm gratings you should now collect data with the 1000 lines/mm gratings. Take a moment to reflect on expectations before diving into the experiment. How will the diffraction pattern change when the 1000 lines/mm grating is used?


#### Miniquestion 1: How do the diffraction patterns from the differently spaced diffraction gratings compare
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLScOvf4fEdEk5cotRGrTle0iitt7onz0DmTOdhuNL47lh2ifqA/viewform?){:target="_blank"}*

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScOvf4fEdEk5cotRGrTle0iitt7onz0DmTOdhuNL47lh2ifqA/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

## Resolution Uncertainty

In module 1 we gave you a rule of thumb for resolution uncertainty, namely "one half of the smallest digit you can measure". This rule of thumb is useful but it is not absolute. For situations such as a digital scale it is a very good rule of thumb, but there are situations where in practice our resolution uncertainty might be larger or smaller. In particular, for a ruler that rule-of-thumb estimate works best if we are measuring an object with a sharp edge.

What about when you are trying to measure the distance to the center of the red spots on the wall from your laser? This is not a nice object with a sharp edge, but a red blob that is bigger than your rule-of-thumb "resolution uncertainty"! In this case, it is okay to **estimate the resolution uncertainty as ~1/4 to 1/2 the width of the bright spot**. i.e. the resolution uncertainty is a gauge of how accurately you can do the measurement. 

## Data collection

With this in mind please go ahead and collect an analogous to the data you collected last week but now using the 1000 line/mm grating(s). This will give you the necessary data to complete this week's checkpoint.

As a reminder (repeat of last week's instructions):

To collect your complete $$x$$ vs. $$L$$ dataset, make sure to do the following:

+ Choose five values of $$L$$. Last week we recommended a range of L values from about 30 cm to about 1 m. You may find this more difficult when working with the 1000 line/mm gratings as the $$x$$ values will be larger. You should still choose five L values over as wide a range as you can in the space you have available. A range of $$L$$ values from 15 cm to 0.5 m will give you a similar range of $$x$$ values to last week.

+ Collect five measurements of $$x$$ for each $$L$$ value, being sure to reset all the parameters you determined you needed to in  [Miniquestion 3 from Week 1](https://docs.google.com/forms/d/e/1FAIpQLSe-Bcw3iqEcmblnBnsOJOqSbfHVNrXckA4mVs9VEvzOXHvZQQ/viewform){:target="_blank"} between each measurement of $$x$$. If you found in Week 1 that $$x$$ depended sensitively on which diffraction grating you used, then you should switch diffraction gratings between measurements, being sure to **only use the 1000 line/mm diffraction gratings.** 

+ For each $$L$$ value, compute the mean value of $$x$$ from your five trials and the random uncertainty as measured by the SEM. Then combine the random uncertainty with your resolution uncertainty in $$x$$ according to the [method for combining independent sources of uncertainty from Module 1](https://physics-50.github.io/Module-1/uncertainty-introduction#combining-uncertainties){:target="_blank"} to determine your total uncertainty in $$x$$, which we call $$\delta x$$.

+ Enter your $$x\pm \delta x$$ and $$L$$ data into the MATLAB curve fitting script called "curve_fitting_demo.m" from the [curve fitting guide](curve-fitting){:target="_blank"} and run the code to perform a best fit analysis.

+ You should make use of your data, the best fit analysis and the provided theory to determine the wavelength of your laser. You will need to use the methods you have been taught in the previous units to propagate your uncertainty and determine the uncertainty in your final result. 

-----------------------------------
## Comparison of results from 500 lines/mm and 1000 lines/mm gratings

After you have collected and analyzed your data for the 1000 lines/mm grating we would like you to compare these results with the results you obtained last week using the 500 lines/mm grating. Using MATLAB please prepare a plot of the calculated wavelength v.s. grating spacing. This plot will consist of two data points with uncertainty. The two data points will be your estimated wavelength (with uncertainty) from your cummulative results for the 500 line/mm and 1000 lines/mm gratings. You can use the MATLAB script from the module 1 deliverable, with appropriate modifications to the axis labels.


-------------

## Checkpoint 3

If you had any issues with Checkpoint 2 we recommend coming to office hours before completing your checkpoint this week as it is very similar.

You should submit the following on Gradescope:

+ The plot used to determine the wavelength of your laser. This plot must include the uncertainties on your data points and include a line of best fit that has been determined with a weighted fit. As always, make sure to include units on your axis labels. You will be asked to upload this plot 3 times. You should upload the same plot each time. You do not need to write a caption.

+ A link to a spreadsheet with your experimental data.

+ The slope you obtained from your plot, including the uncertainty. 

+ The wavelength you have determined for your laser, with uncertainty.

+ A plot of calculated wavelength v.s. diffraction grating spacing (two data points, with uncertainty). This plot will combine your data from this week and from checkpoint #2 (wavelength determined using the 500 lines/mm grating(s))

+ A response to the brief questions on Gradescope regarding your results

It may be that you have done very careful experimental work and your results still are not in agreement. We will explore this more next week.

## Grading rubric

This checkpoint will be graded out of 14 points. 

+ The grading rubric for the first three questions (results for the 1000 lines/mm grating) will be analogous to those for checkpoint #2. Please come talk to office hours and ask question if there is anything you are unsure about. 

+ Question 4 (comparison of results from two different grating spacings) will be graded on both your results and figure mechanics

+ Question 5 (agreement of results). We are only looking for a single sentence indicating whether your wavelengths are in agreement.


## Mini-questions:

And to double-check, make sure you have finished all of this week's mini-questions by [checking here](mini-questions#week-3){:target="_blank"}