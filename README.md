Computed Tomography Reconstruction

This project involves creating projection data (sinograms) from computed tomography (CT) images and reconstructing images from these data using various filtering methods. The main steps and functions used in the project are as follows:

Image Data:
A sample CT image is generated using the Shepp-Logan phantom.
A user-provided brain image is included in the project.

Projection Angles:
Projection angles are determined, evenly spaced between 0 and 180 degrees.

Sinogram Calculation:
Sinograms are created by rotating the images at specified angles and summing the projections.

Filter Functions:
Sinogram projections are filtered using Ramp, Shepp-Logan, Cosine, and Hamming filters.

Filter Application and Image Reconstruction:
Sinograms are filtered using each filter, and images are reconstructed from these filtered sinograms.
A combined filter using all the filters is also applied to filter the sinograms and reconstruct the images.

Visualization:
Original sinograms, filtered sinograms, and reconstructed images are visualized using matplotlib.

This project is designed to aid in understanding the fundamental techniques used in computed tomography image processing.
