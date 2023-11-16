# Simulation-of-an-OFDM-system-using-MATLAB
Orthogonal Frequency-Division Multiplexing



“Transforms single serial stream high-rate date into a parallel stream of many low-rate data”
	Divide the passband into several sub-bands.
	Each QAM symbol of the serial stream gets frequency translation to one of the sub-bands, i.e., multiplexing by complex exponential at a frequency
 
![Capture](https://github.com/ChinmaiChowdary/Simulation-of-an-OFDM-system-using-MATLAB/assets/119433702/0dce5aa0-223c-4642-8c42-362ba180b089)

(sum of frequency translated QAM symbols)

Where mk/N is the frequency of a subcarrier
	The above equation is an inverse discrete Fourier transform (IDFT) and can be implemented by using IFFT.
