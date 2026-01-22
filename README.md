This project detects brain tumors from MRI images using image processing techniques. The workflow includes preprocessing to enhance image quality, segmentation to isolate tumor regions, and refinement for accurate detection.

**STEPS INVOVLED**

1. MRI image dataset acquisition
2. Noise reduction using Anisotropic Diffusion Filtering (ADF) while preserving edges
3. Skull stripping to remove non-brain tissues
4. Tumor visibility enhancement using Top-hat filtering
5. Contrast improvement with Histogram Equalization (HE)
6. Binarization to extract relevant tumor features
7. Tumor segmentation using the Watershed algorithm
8. Refinement with Morphological operations to clearly define tumor boundaries
9. Performance evaluation using image-based metrics

This approach ensures efficient, accurate, and reliable tumor detection from MRI scans.
