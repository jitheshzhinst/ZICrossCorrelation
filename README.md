# Zurich Instruments: Cross Correlation
# Author: Jithesh Srinivas
# https://blogs.zhinst.com/jithesh/2020/05/19/how-to-reduce-the-noise-floor-and-improve-the-snr-with-cross-correlation-techniques/
## ** 26/05/2020 The Cross-Correlation code for the two MFLIs is being fixed and will be uploaded soon ##

Manual Cross Correlation code in Python Notebook (.ipynb) format. The code will do all the work for you, and all you have to do is set your device name and follow the wiring setup; or you can do your own experiment! This is specifically for the UHFLI and MFLI devices (UHF-QA can work too).

Cross Correlation validation.ipynb demonstrates the validation of the cross-correlation code in the frequency domain, this was written and tested using a single UHFLI. See the wiring example required for this: https://blogs.zhinst.com/jithesh/files/2020/05/figure2-e1589970333493.png

UHFLI Cross Correlation code.ipynb is the main cross-correlation code which can now be repeated many times. Many more of the parameters here changed for eg. no. of repeats, signal amplitude, input range, etc. See the wiring example required for this: https://blogs.zhinst.com/jithesh/files/2020/05/figure5-e1589970237381.png

Of course, you can use any kind of wiring setup you wish and change the code as you please. 
