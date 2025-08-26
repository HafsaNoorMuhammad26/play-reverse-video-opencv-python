# Play-Reverse-Video-OpenCV-Python

A simple Python project that demonstrates how to play a video in reverse using OpenCV. This project exhibits frame extraction, reversal, and playback via a Jupyter Notebook implementation.

##  Overview

This repo contains a Jupyter Notebook (`54_Play a Video in Reverse Mode.ipynb`) showcasing the process of:

- Loading a video using OpenCV.
- Extracting each frame.
- Reversing the sequence of frames.
- Playing both forward and reverse playback.

##  Prerequisites

Ensure you have the following installed:

- Python 3.6 or above  
- OpenCV (`opencv-python`)  
- Jupyter Notebook (optional, for running the `.ipynb`)  

Install dependencies via pip:

```bash
pip install opencv-python notebook
````

## Usage

### Running within Jupyter Notebook

1. Clone this repository:

   ```bash
   git clone https://github.com/HafsaNoorMuhammad26/play-reverse-video-opencv-python.git
   cd play-reverse-video-opencv-python
   ```

2. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

3. Open `54_Play a Video in Reverse Mode.ipynb` and run the cells. Make sure to set the video file path correctly.

## How It Works

This approach reads every frame into memory, stores them in a list, and then iterates in both forward and reverse order to simulate playback. It's straightforward but may consume substantial memory for longer videos—great for short clips or educational purposes. ([geeksforgeeks.org](https://www.geeksforgeeks.org/python/python-play-video-reverse-mode-using-opencv/?utm_source=chatgpt.com))

## Limitations

* **Memory usage**: Storing all frames uses significant RAM, especially for high-resolution or long videos. As noted on Stack Overflow and other forums, buffering frames is one of the only practical methods, but large videos can quickly exhaust memory. ([stackoverflow.com](https://stackoverflow.com/questions/11260042/reverse-video-playback-in-opencv?utm_source=chatgpt.com))
* **Lack of audio**: This method focuses solely on video frames. Audio is not processed or preserved.

## Contributions

**Author**: Hafsa Noor Muhammad
* [LinkedIn](https://www.linkedin.com/in/hafsa-noor-muhammad-67b96331a/)
* [GitHub](https://github.com/HafsaNoorMuhammad26)

---

