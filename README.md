

# Introduction
Our project establishes a solid and comprehensive foundation of expertise in the field of digital signal processing and communication systems. 

We take pride in fully meeting the requirements for "ADC modulation and demodulation," delivering a solution that ensures efficient signal conversion and transmission. 
<div align="center">  
<a href="Final_Report.pdf" target="_blank">
     <img src="https://img.shields.io/badge/Link_Report-808080?style=for-the-badge&logoColor=white" target="_blank" /> 
</div>

Matlab Version: R2016a 

## How the System Works

https://github.com/user-attachments/assets/1de7112b-d077-4bc2-9216-d66f3e682195

An analog sine wave signal is used as input, with the following parameters:
- Amplitude: 0.75
- Frequency: 0.035 Hz
- Period: 28.5 seconds

Sampling is done using a Zero-Order Hold block
- Amplitude: 0.55
- Pulse width: 60%.

Quantization of the signal into discrete levels.
- Quantization interval: 0.66

Encoding using a Uniform encoder
- Peak: 1
- Bits: 2
- Levels: 4

Modulation (0 and 1) to (+1 and -1) phase (0° and 180°).

Pass Through Noise Channel (AWGN)
- Initial seed: 67
- Es/No: 1e-6
- Signal Power: 1W

Demodulation restores binary data (0 and 1).

Error Rate Calculation to calculate the bit error rate (BER) to show the influence of noise and ADC conversion on signal quality.

