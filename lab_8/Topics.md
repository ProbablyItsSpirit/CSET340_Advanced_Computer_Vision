### Lab 8 – Compression & Watermarking

1. Lossless Compression Techniques
- Implement run-length encoding on `cameraman.jpg`, reconstruct, and report MSE/PSNR parity with the source.
- Build Huffman codes from grayscale histograms, encode/decode, and compare fidelity and storage implications.

2. Lossy Compression via DCT
- Perform full-image DCT/IDCT reconstruction without quantization to show perfect recovery.
- Apply block-wise (8×8) DCT with JPEG-style quantization and zig-zag ordering to observe PSNR degradation versus bitrate savings.

3. Comparative Image Compression Study
- Compress `face.jpg` at low and high JPEG quality factors; measure resulting file sizes.
- Export `Butterfly.png` with minimal and maximal PNG compression levels to contrast lossless size trade-offs.
- Summarize results in a table for quick visual comparison.

4. Digital Watermarking (Visible & Invisible)
- Embed a visible BU logo overlay into `penguine.jpg` via weighted ROI blending and recover it by cropping.
- Inject an invisible watermark by modifying mid-frequency DCT coefficients; demonstrate extraction through inverse DCT differencing.
- Discuss robustness versus perceptual impact for both watermarking strategies.
