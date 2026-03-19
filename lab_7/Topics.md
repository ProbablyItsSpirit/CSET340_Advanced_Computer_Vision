### Lab 7 – Frequency-Domain Filtering

1. FFT & IFFT Exploration
- Convert sample RGB images (Cat) to grayscale and compute centered FFT magnitude spectra.
- Design rectangular low- and high-frequency masks, perform inverse FFT, and visualize separated components.

2. Low-Pass Filters (LPF)
- Load `penguine.jpg` and construct Ideal, Gaussian, and Butterworth LPFs in the frequency domain.
- Compare spatial reconstructions for varying cutoff radii to highlight smoothing characteristics and ringing artifacts.

3. High-Pass Filters (HPF)
- Apply Ideal, Gaussian, and Butterworth HPFs to `cameraman.jpg` to emphasize edges and fine details.
- Discuss the trade-offs between sharpness and noise amplification across filter types and orders.

4. Gaussian Smoothing & Homomorphic Filtering
- Perform spatial Gaussian smoothing before transitioning to log-domain frequency processing.
- Implement a homomorphic filter with tunable `gH`, `gL`, `c`, and `D0` to balance illumination and contrast.
- Normalize and visualize original, smoothed, and enhanced outputs to evaluate illumination correction.
