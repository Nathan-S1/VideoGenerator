# VideoGenerator
Video Generator in Python that processes images and text to produce dynamic video content using OpenCV. This project showcases video editing, frame generation, and multimedia processing capabilities using Python libraries.

## Author
Nathan Shorez

---

## Project Overview
This project implements a video generator in Python using libraries such as OpenCV and PIL. The objective is to generate dynamic video content by processing images and text, applying filters, and exporting the result as video files.

---

## Key Components
- **Video Generation:** Create video frames from images and text overlays.
- **Image Processing:** Apply filters and transformations to frames.
- **Video Export:** Compile frames into a single video file.

---

## Dependencies
- Python 3.x
- OpenCV
- PIL (Pillow)
- argparse

To install dependencies:
```bash
pip install opencv-python pillow
```

---

## Execution
1. **Navigate to the src directory:**
   ```bash
   cd src/
   ```
2. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook video_generator.ipynb
   ```

---

## Example Usage
- Generate a video from images:
  ```bash
  python video_generator.py --input "images/" --output "output_video.mp4"
  ```

---
