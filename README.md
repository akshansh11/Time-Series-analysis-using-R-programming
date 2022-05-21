# Process of creating the Random Time Series using R Programming
A time series is a collection of data sets that appear in a specific order throughout time. Cross-sectional data, on the other hand, captures a single moment in time.

A time series in investing follows the movement of selected data points, such as the price of an asset, over a specific time period with data points captured at regular intervals. There is no set period of time that must be included, permitting the information to be collected in a way that offers the information that the investor or analyst looking into the activity is looking for.

In order to create the time series objects, ‘ts’ function is used. The ts() function creates an R time series object from a numeric vector. ts(vector, start=, end=, frequency=) is the format, where start and end are the times of the first and last observations, and frequency is the number of observations per unit time.

Let’s see an example for creating the time series object. In this example, I will take some 625 random numbers and plot them by using the Normal Distribution function i.e. ‘rnorm’. Now we need to add the time component in order to make the time series. Let’s say we have a monthly dataset that starts from November 1902.

Firstly, an object ‘x’ is created which is the cumulative sum of the randomly distributed numbers 625. Secondly, a time series object ‘y’ is created as shown below in the code.


The starting point is the November month of the year 1902 with a frequency of 12 i.e. monthly distribution. The simple plot of the time series obtained is shown below.


The lattice version of the above curve is shown below which provides a more advanced solution to the problem. Inspired by Trellis graphics, Lattice is a powerful and elegant high-level data visualization framework for R. It is built with multivariate data in mind, and it enables simple conditioning to make “small multiple” graphs. Lattice is capable of handling most standard graphics requirements while also being flexible enough to accommodate most nonstandard requirements.

