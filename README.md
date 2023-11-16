# Simulation-of-an-OFDM-system-using-MATLAB
Orthogonal Frequency-Division Multiplexing



“Transforms single serial stream high-rate date into a parallel stream of many low-rate data”
	Divide the passband into several sub-bands.
	Each QAM symbol of the serial stream gets frequency translation to one of the sub-bands, i.e., multiplexing by complex exponential at a frequency

〖S(k)〗^ =∑_(m=0)^(N-1)▒〖a_m e^(j2π(mk/N)) 〗

(sum of frequency translated QAM symbols)

Where mk/N is the frequency of a subcarrier
	The above equation is an inverse discrete Fourier transform (IDFT) and can be implemented by using IFFT.
