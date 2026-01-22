This project detects brain tumors from MRI images using image processing techniques. The workflow includes preprocessing to enhance image quality, segmentation to isolate tumor regions, and refinement for accurate detection.

Steps Involved

MRI image dataset acquisition

Noise reduction using Anisotropic Diffusion Filtering (ADF) while preserving edges

Skull stripping to remove non-brain tissues

Tumor visibility enhancement using Top-hat filtering

Contrast improvement with Histogram Equalization (HE)

Binarization to extract relevant tumor features

Tumor segmentation using the Watershed algorithm

Refinement with Morphological operations to clearly define tumor boundaries

Performance evaluation using image-based metrics

This approach ensures efficient, accurate, and reliable tumor detection from MRI scans.
