### Digital Signal Processing Toolkit
<br>
Digital Signal Processing is concerned with the representation of signals by a sequence of numbers or symbols and the processing of these signals. Digital signal processing and analog signal processing are subfields of signal processing. DSP includes subfields audio and speech signal processing, sonar and radar signal processing, sensor array processing, spectral estimation, statistical signal processing, digital image processing, signal processing for communications, control of systems, biomedical signal processing, seismic data processing, etc.<br>

The goal of DSP is usually to measure, filter and/or compress continuous real-world analog signals. The first step is usually to convert the signal from an analog to a digital form, by sampling it using an analog-to-digital converter (ADC), which turns analog signal into a stream of numbers. However, often, the required output signal is another analog output signal, which requires a digital-to-analog converter (DAC). Even if this process is more complex than analog processing and has a discrete value range, the application of computational power to digital signal processing allows for many advantages over analog processing in many applications, such as error detection and correction in transmission as well as data compression.<br>


### Signal Statistics<br>

This function calculates the following parameters:
<u>Arithmetic</u><u> </u><u>Mean</u> -  The sum of the values  of a variable divided by  the number of values is <br>
      called arithmetic mean.
<img alt="" src="images/Image_001.jpg" style="width:419px;height:47px"/><br>
<u>Variance</u> - The calculation of how far values lie  from the mean value  in any distribution curve is  done using variance.
<img alt="" src="images/Image_002.jpg" style="width:163px;height:48px"/><br>
 (Where X is any  random variable, or E[X] is  its mean and Var(X)  its variance.)</br>
 <u>Mode</u> - The value  that occurs most frequently in any distribution curve is called  its  mode.<br>
 <br>
<u>RMS</u> - The root mean square, also known as  the  quadratic mean,  is a statistical measure  of the magnitude of any  varying quantity.</br></br>
<u>Standard deviation</u> - It measures  how  much a distribution is spread.  It is the square root of variance.
<img alt="" src="images/Image_003.jpg" style="width:182px;height:29px"/>
Where x is any  random variable, µ or E(x) is  its  mean and its standard deviation.
<u>Skewness</u> - It is  a measure of the asymmetry of the  probability distribution of a random  variable.
<img alt="" src="images/Image_004.jpg" style="width:260px;height:70px"/>
Where x  is any random variable, µ or E(x) is mean and is third  standardized moment or  skewness.
<u>Kurtosis</u> - It is a measure of peakedness of any curve and is  normalized form of fourth  standardized moment.
<img alt="" src="images/Image_005.jpg" style="width:32px;height:39px"/>is fourth standardized moment.
<u>Median</u>- It is defined as  the  numeric value separating  the higher half of  a sample, from the lower half.<br>

### Convolution <br>

<u>Convolution </u> - It is a mathematical way of combining two signals  to form a third signal,
defined as the integral of the product of the two functions  after one is reversed  and shifted. Convolution  of 2 signals f and g is given  as:
<img alt="" src="images/Image_006.jpg" style="width:264px;height:47px"/>
<u>Cross Correlation</u> - In signal  processing, cross-correlation  is a measure of similarity of two waveforms  as a function of a  time-lag applied to one of  them. For continuous functions, f and g, the cross-correlation is defined as:
<img alt="" src="images/Image_007.jpg" style="width:276px;height:60px"/>
Where f  * denotes the complex  conjugate off.
<u>Autocorrelation </u> - It is the cross-correlation of a  signal with itself. Given a  signal f(t), the  continuous autocorrelation Rff is most often  defined as the continuous  cross-correlation integral of f(t) with itself, at lag.
<img alt="" src="images/Image_010.jpg" style="width:492px;height:48px"/><br>


### Power Spectrum <br>

Power Spectrum shows frequencies  containing the signal´s power,  by plotting  a distribution of power values  as a function of frequency, where "power" is considered to be the average of the signal². For a given  signal, the power spectrum gives a plot of the  portion of a signal's power  (energy<br>
per unit time) falling  within given frequency bins.  The  most common way of generating a power spectrum is by  using a discrete Fourier  transform, but other techniques  such as the maximum  entropy method  can also be used. </br>
<img alt="" src="images/Image_011.jpg" style="width:552px;height:397px"/> <br>

### Histogram <br>

Histograms are used to plot density  of data, and  often for density  estimation: estimating the probability  density function of the  underlying variable. The total area  of a histogram used for probability  density is always normalized  to 1. If the length of the intervals on the x-axis are  all 1, then a histogram  is identical to a relative frequency plot.
<img alt="" src="images/Image_012.png" style="width:450px;height:295px"/><br>

### FFT (Fast Fourier Transform) <br>

An FFT  computes the DFT and  produces exactly  the same result as  evaluating the DFT definition directly;  the  only difference is that an FFT is  much faster. The basic idea is to break  up a transform of length into  two transforms of length using the identity.
<img alt="" src="images/Image_013.jpg" style="width:503px;height:60px"/><img alt="" src="images/Image_014.jpg" style="width:386px;height:62px"/>
Since the fourier transform gives the information about the frequency component of any signal, it is used for finding out what are the frequencies present in the signal if the signal is stationary i.e. the frequency component of the signal is not changing with time. <br>

### DCT (Discrete Cosine Transform) <br>

A <strong>discrete  cosine transform </strong>(<strong>DCT</strong>) expresses a sequence of finitely  many  <a href="http://en.wikipedia.org/wiki/Data_points">data points</a> in terms of a sum of <a href="http://en.wikipedia.org/wiki/Cosine">cosine</a> functions oscillating  at different  <a href="http://en.wikipedia.org/wiki/Frequency">frequencies.</a> DCTs  are important to numerous<br>
  applications in science  and engineering, from  <a href="http://en.wikipedia.org/wiki/Lossy_compression">lossy compression of</a>  <a href="http://en.wikipedia.org/wiki/Audio_compression_%28data%29">audio and</a> <a href="http://en.wikipedia.org/wiki/Image_compression">images</a> (where small  high-frequency components can  be discarded), to   <a href="http://en.wikipedia.org/wiki/Spectral_method">spectral methods</a> for the numerical  solution of <a href="http://en.wikipedia.org/wiki/Partial_differential_equations">partial differential equations.</a> The  use of <a href="http://en.wikipedia.org/wiki/Cosine">cosine</a> rather than  <a href="http://en.wikipedia.org/wiki/Sine">sine</a> functions  is critical in these applications: for compression, it turns out that  cosine functions are much more efficient (as explained<br>
  below, fewer are  needed to approximate a typical   <a href="http://en.wikipedia.org/wiki/Signal_%28electrical_engineering%29">signal),</a> whereas for differential equations the cosines express  a particular choice of  <a href="http://en.wikipedia.org/wiki/Boundary_condition">boundary conditions.</a></br></br>

<img alt="" src="images/Image_015.jpg" style="width:602px;height:361px"/>
The Discrete Cosine Transform DCT  {X}  of a sequence X is defined  by  the following equations:
<img alt="" src="images/Image_016.jpg" style="width:541px;height:62px"/>
Where N is  the  length of X, xn  is the nth element  of X,yk is the kth element of DCT {X}<br>
                             <br>
<strong>DST</strong>- The Discrete  Sine Transform DST  {X}  of a sequence X is  defined by the  following equations:</br></br>
<img alt="" src="images/Image_017.jpg" style="width:216px;height:80px"/>
Where N is the length of the  input sequence X,xn is the nth  element of the input sequence  X, and yk is the kth  element of the output  sequence DST {X}.<br>

### Hilbert Transform <br>

I<a href="http://en.wikipedia.org/wiki/Mathematics">n mathematics</a> and in  <a href="http://en.wikipedia.org/wiki/Signal_processing">signal processing,</a> the Hilbert transform  is a  <a href="http://en.wikipedia.org/wiki/Linear_operator">linear operator</a> which takes a function, u(t), and produces a function,  H(u)(t), with the same  domain. The Hilbert transform is named after <a href="http://en.wikipedia.org/wiki/David_Hilbert">David Hilbert,</a> who first  introduced the operator  in order to solve a special case  of  the  <a href="http://en.wikipedia.org/wiki/Riemann%E2%80%93Hilbert_problem">Riemann–Hilbert problem</a> for  <a href="http://en.wikipedia.org/wiki/Holomorphic_function">holomorphic functions.</a> It is a basic  tool in <a href="http://en.wikipedia.org/wiki/Fourier_analysis">Fourier  analysis,</a> and provides  a concrete means for realizing  the <a href="http://en.wikipedia.org/wiki/Conjugate_function">conjugate of</a> a given function  or  <a href="http://en.wikipedia.org/wiki/Fourier_series">Fourier series.</a> Furthermore, in <a href="http://en.wikipedia.org/wiki/Harmonic_analysis">harmonic analysis,</a> it is an  example of a <a href="http://en.wikipedia.org/wiki/Singular_integral">singula</a>r  <a href="http://en.wikipedia.org/wiki/Singular_integral">integral operator,</a> and of a <a href="http://en.wikipedia.org/wiki/Multiplier_%28Fourier_analysis%29">Fourier multiplier.</a> The Hilbert transform is also  important in the field of signal  processing where it is  used to derive the <a href="http://en.wikipedia.org/wiki/Analytic_signal">analytic representation of</a> a signal u(t). The Hilbert transform can be thought of as  the  convolution of u(t) with the  function h(t)=1/(3.14*t), and is  given by:
<img alt="" src="images/Image_018.jpg" style="width:468px;height:48px"/>


### Wavelet Transform <br>

<a href="http://en.wikipedia.org/wiki/Numerical_analysis">In  numerical analysis</a> and <a href="http://en.wikipedia.org/wiki/Functional_analysis">functional analysis,</a> a discrete wavelet transform  (DWT) is any <a href="http://en.wikipedia.org/wiki/Wavelet_transform">wavelet transform for</a> which the <a href="http://en.wikipedia.org/wiki/Wavelet">wavelets</a> are discretely sampled. As with other wavelet transforms, a key advantage  it has over <a href="http://en.wikipedia.org/wiki/Fourier_transform">Fourier transforms is</a> temporal  resolution: it captures  both frequency and location  information (location in time).
The wavelet  transform replaces the  Fourier transform's sinusoidal waves  by  a family generated by translations and dilations  of a window called a  wavelet.It includes two types of wavelets:  orthogonal (Haar, Daubechies  (dbxx), Coiflets (coifx), Symmlets (symx)) and biorthogonal (Biorthogonal (biorx_x), including  FBI (bior4_4 (FBI))), where x indicates the order of the  wavelet.
The higher the order,  the smoother the wavelet.

### Chirp-Z Transform <br>

Bluestein's FFT algorithm  , commonly called  the chirp z-transform algorithm, is a Fast Fourier  transform (FFT)  algorithm that computes the Discrete Fourier  transform (DFT) of arbitrary  sizes (including prime sizes)  by re-expressing  the DFT as a convolution.<br>

### IR (Infinite Impulse Response) Filters <br>

<strong>Infinite impulse response (IIR)</strong><strong> </strong>is a property  of signal processing systems.  Systems with this property  are known as IIR systems  or, when dealing with <a href="http://en.wikipedia.org/wiki/Filter_%28signal_processing%29">filter</a> systems, as IIR filters. IIR systems  have an  <a href="http://en.wikipedia.org/wiki/Impulse_response">impulse response</a> function that is non-zero  over an infinite length  of time. This  is in contrast to  <a href="http://en.wikipedia.org/wiki/Finite_impulse_response">finite impulse response</a> (FIR) filters, which  have fixed-duration impulse  responses. The simplest  analog IIR filter is an <a href="http://en.wikipedia.org/wiki/Rc_circuit">RC</a> filter made  up  of a single  <a href="http://en.wikipedia.org/wiki/Resistor">resistor</a>feeding into a node  shared with a sing<a href="http://en.wikipedia.org/wiki/Capacitor">le capacitor (C).</a> This filter  has  an exponential impulse  response characterized by an <a href="http://en.wikipedia.org/wiki/RC_time_constant">RC time constant.</a>
IIR filters  may be implemented as either  analog or digital filters.Digital  filters are implemented in terms of the difference equation  as given below:
<img alt="" src="images/Image_019.jpg" style="width:432px;height:72px"/>
P is the feedforward  filter order,
bi the feedforward filter coefficients, Q is the  feedback filter order,<br>
ai are the  feedback filter coefficients, x[n] is the input signal and</br></br>
These are commonly  referred to as taps (the  number of inputs). y[n]  is the output signal


### FIR (Finite Impulse Response)  Filters <br>

Finite Impulse  Response filters  are  one of the primary types of filters  used in Digital  Signal  Processing. FIR filters are  said to be finite because they  do  not have any feedback. To study any Filter  we plot 2 graphs - the Magnitude  response curve (magnitude vs. frequency curve)  and Phase response curve  (phase vs. frequency curve).
<img alt="" src="images/Image_020.jpg" style="width:396px;height:156px"/>
The difference equation that  defines the output of an FIR filter in terms of  its input is:
<img alt="" src="images/Image_021.jpg" style="width:420px;height:35px"/>
x[n] is the input signal, y[n]  is the output signal, 
bi are the filter coefficients,  also known as tap weights, and N is the filter order - an Nth-order filter has (N + 1) terms on the right-hand  side.</br>

### Window Implementation <br> 

<img alt="" src="images/Image_022.jpg" style="width:575px;height:345px"/><br>

### Signal Filtering <br>

Signal filtering involves addition of noise to input signal and then filtering the distorted signal with the help of previous discussed filters.<br>


### Median Filter <br>

The median filter is a nonlinear  digital filtering technique, often  used to remove noise. The Median  Filter obtains the elements of Filtered  X using  the following equation:
yi = Median(Ji) for i = 0, 1, 2, …,  n - 1,
Where Y represents the output  sequence filtered X, n is the number of elements in the input sequence X,
Ji is a subset of the  input sequence X centered  about the ith element  of X, and the indexed elements outside  the range of X equal zero.</br>


### Smoothing Filter <br>

Smoothing filters are also called low-pass  filters because they let  low  frequency components pass  and reduce the high frequency components. The impulse response of a normal  low-pass filter implies  that all the coefficients of the mask should be  positive. Low-pass filtering in effect blurs the image and removes speckles of high frequent  noise. Larger masks will result in more blurring effect. To avoid a  general amplification or damping of the data the sum of the  filter coefficients should be 1.0.
Many different  algorithms are used in smoothing. One of the most common algorithms is the "moving average", often  used to try to capture  important trends in repeated statistical surveys.
Given a series of  numbers and a fixed subset  size, the moving  average can be obtained by first taking the average of the  first subset. The fixed subset size is then shifted forward,  creating a new subset of numbers, which is  averaged. This process is repeated over  the entire data series.  The  plot line connecting all the (fixed) averages is the moving  average. Thus, a moving  average is not a single number,  but it is a set of numbers,  each of which is  the average of the corresponding  subset of a larger  set  of data points. A moving  average may also use unequal weights for  each  data value in the subset  to emphasize particular values in the  subset.<br>


### Compression <br> 

Acquires a large number of data points  and compresses  the data points into a smaller number of points by applying reduction methods to  input signal on basis of value contained  in  each segment.
Consider for example:  An input sine wave of  frequency 30 Hz and amplitude 5V is  given to a median filter. Let the reduction factor be 25. This means at a time, 25 data  points are taken and  the average is taken.  Again, this point is plotted  and the  next 25 data points are considered and the average is  taken. This process goes on repeating itself to get the  compressed data.<br>
The value -1.00978 specifies  the instantaneous mean of the current reduction  factor size.</br>
