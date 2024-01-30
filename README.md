### Wind Turbine Blade (WTB) Thermal Images -- Dataset 1

Our team gathered a dataset of 1000 thermal images, each processed to achieve uniformity and consistency throughout the collection. This involved several key steps:

- Cropping, centering, and resizing each image to a consistent resolution of `320x320` pixels.
- Classifying the images as either **healthy** or **faulty** for WTB inspection.

The dataset is evenly divided, containing:

- 500 images of healthy WTB blades.
- 500 images of faulty WTB blades.

This ensures a balanced representation of both categories. The faulty images include a range of defect types such as cracks, erosion, and holes, providing a comprehensive overview of common faults in wind turbine blades.

During the preprocessing phase, our focus was on techniques particularly suitable for thermal images:

- **Normalization**: Ensuring uniform pixel intensity across all images.
- **Augmentation Techniques**: Including random rotation, flipping, noise addition, and blurring, to mimic the challenging conditions of real-world aerial photography.
