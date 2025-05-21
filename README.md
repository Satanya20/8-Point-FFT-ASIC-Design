# 8-Point-FFT-ASIC-Design

The Fast Fourier Transform (FFT) is a fundamental algorithm in digital signal processing 
(DSP) used to convert time-domain signals into their frequency-domain representations. Hardware
based FFT engines are essential components in many real-time systems, including wireless 
communication, audio/video processing, biomedical instrumentation, and radar systems, where high
speed and low-power operation are critical. 
This project focuses on the design, implementation, and tapeout of an 8-point FFT engine as a 
custom Application-Specific Integrated Circuit (ASIC) using the Synopsys toolchain. The FFT design 
is based on the Radix-2 Decimation-in-Time (DIT) algorithm. The FFT engine is designed to process 
eight complex inputs (each with real and imaginary components) and output their frequency 
components. 
