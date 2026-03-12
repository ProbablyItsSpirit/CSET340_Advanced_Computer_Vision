### Lab 6 – Color Models & Enhancements

Color Model Conversion:
- Convert sample RGB images (e.g., Lena, Face) into HSV, YCbCr, CMY, and CMYK representations.
- Visualize each color space side-by-side to compare channel emphasis and dynamic ranges.

Pseudo Color Image Processing:
- Perform 2-slice and 8-slice intensity slicing on `medical2.jpeg`, assigning distinct color palettes per slice.
- Build a dedicated two-color coding scheme (binary mapping) driven by a threshold at intensity 128.
- Apply multi-color intensity coding (e.g., OpenCV color maps) to other grayscale assets such as `Lena_grey`, `map`, and `bag`.

Intensity-to-Color Transforms:
- Implement log, gamma (power-law), and piecewise-linear transforms on grayscale images.
- Merge transformed channels into composite BGR outputs to highlight different intensity characteristics.

Color Image Enhancements:
- Generate negative, logarithmic, gamma, smoothing, sharpening, and tone-mapped variants for RGB images (Lena, Face, Pyramid).
- Discuss how each enhancement alters contrast, detail, and perceived color richness.
