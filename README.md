# ZICrossCorrelation
Cross correlation code for use in devices such as UHFLI and MFLI

UHFLI Cross Correlation code.ipynb is is to be used for a single UHFLI. All the parameters/settings are already parsed and set in the code to the daq handle, so the wiring setup should be the signal output 2 connected into signal input 1 and input 2 via bnc t-splitter. 

Of course, you can use any kind of wiring setup you wish and change the code as you please. 


Cross correlation validation.ipynb is the code used for the example in figure 1 from the blog https://blogs.zhinst.com/jithesh/2020/05/19/how-to-reduce-the-noise-floor-and-improve-the-snr-with-cross-correlation-techniques/

The wiring setup used can as seen in figure 2. This code will both capture the waves by triggering, perform the cross-correlation in the time-domain and frequency domain, and plot both for you. It also simulates the waves within Python and cross-correlates with a plot. You can then compare all the plots to see the difference; they are all similar.

Author: Jithesh Srinivas
