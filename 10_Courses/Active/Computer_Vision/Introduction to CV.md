# Lecture 1 – Introduction to Computer Vision

* **Course:** Design and Development of Robots – Computer Vision
* **Date:** 2026-03-24
* **Lecture #:** 1
* **Location / Format:** In-person

---

## Key Points

* CV is inherently a noisy problem — real-world images are affected by lighting, occlusion, motion blur, and sensor noise
* Vision allows robots to:
  * Recognize traffic lights and signs
  * Detect obstacles and people
  * Inspect products in manufacturing
  * Identify objects for manipulation
* CV helps a robot detect objects, estimate position, navigate, and interact with the environment
* Cameras provide rich information at relatively low cost compared to other sensors (e.g., LiDAR)
* The Microsoft Kinect was revolutionary for its ability to capture depth information using structured infrared light — enabling low-cost 3D perception

---

## Definitions

* **Computer Vision (CV):** A branch of AI that enables computers to interpret and make decisions based on visual data, analogous to how humans process images and videos
* **Pixel:** The smallest unit of a digital image; each pixel stores a color or intensity value
* **Grayscale image:** One value per pixel (0 = black, 255 = white)
* **RGB image:** Three values per pixel (Red, Green, Blue channels); requires 3× more storage than grayscale
* **Spatial resolution:** Number of pixels in an image (e.g., 1920×1080)
* **Bit depth:** Number of intensity/color levels per pixel; 8-bit = 256 levels per channel, 24-bit RGB → millions of colors

---

## CV Workflow

Image Acquisition → Preprocessing → Feature Extraction → Decision Making → Visualization

---

## Applications

Healthcare · Agriculture · Insurance · Manufacturing · Banking · Automotive · Sports · Surveillance

---

## Summary

* A computer does not see "objects" directly — it processes images as numerical matrices of pixels
* CV is the bridge between raw visual data and meaningful robot behavior
* Choosing grayscale vs. RGB is a practical tradeoff between computational cost and color information needed

---

## Connections to Other Notes

* See also:
* 