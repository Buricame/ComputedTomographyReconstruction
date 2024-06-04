<u>CT Image Reconstruction</u>

<u>Overview</u>

This project is a learning initiative focused on reconstructing CT images from raw data using Fourier transform-based algorithms and Filtered Back Projection (FBP).

<u>Steps</u>

- **Image Data:** Uses Shepp-Logan phantom and user-provided brain CT images.
- **Projection Angles:** Evenly spaced angles from 0 to 180 degrees.
- **Sinogram Calculation:** Creates sinograms by rotating images and summing projections.
- **Filtering Methods:** Applies Ramp, Shepp-Logan, Cosine, and Hamming filters.
- **Reconstruction:** Reconstructs images from filtered sinograms using FBP.
- **Visualization:** Displays original and reconstructed images using matplotlib.

<u>Software</u>

- **Google Colab:** Cloud-based coding platform.
- **Python Libraries:** NumPy, SciPy, Matplotlib, scikit-image, OpenCV, Seaborn, Plotly.
