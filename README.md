# Neon Sketch Reveal Engine

A real-time image processing and computer vision animation engine built using Python, OpenCV, and NumPy. It transforms any photograph into a multi-stage glowing neon line-art animation, complete with particle reveals, high-detail resolution refinement, floor reflections, and smooth crossfades.

## 🌟 Features

- **Particle & Mosaic Reveal**: Randomly places glowing neon particles/dots to form the outline of the image.
- **Resolution Refinement**: Smoothly sharpens mosaic blocks into fine neon line-art.
- **Realistic Neon Glow**: Uses bilateral filtering, Canny edge detection, and multi-scale Gaussian blurring in HSV color space.
- **Floor Reflection**: Dynamic bottom reflection effect with linear gradient opacity fading.
- **Smooth Crossfade**: Seamlessly transitions from glowing neon lines back into the full-color photo.
- **Auto Image Saving**: Saves high-resolution output files (`output_neon_sketch.png` & `output_clear_photo.png`) upon completion.