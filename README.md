# Background Subtraction using Gaussian Mixture Models (GMM)

This project implements background subtraction using **Gaussian Mixture Models (GMM)**, a probabilistic approach for segmenting image and video frames into foreground and background components. It is particularly useful in tasks like motion detection, object tracking, and surveillance.

## Features
- **Background Modeling:** Utilizes per-pixel GMM to distinguish between background and foreground in training frames.
- **Foreground Detection:** Subtracts the background and applies thresholding to accurately isolate and detect foreground objects in test frames.
- **Flexibility:** Capable of handling dynamic scenes with varying lighting conditions and non-stationary backgrounds.
