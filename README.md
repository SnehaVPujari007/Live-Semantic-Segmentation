# Live Semantic Segmentation with Image Capture

This project performs live semantic segmentation using K-Means clustering via a webcam feed. It allows users to segment the scene into meaningful regions and capture the processed frames as images on command.

## Features

### Live Semantic Segmentation:
- Uses K-Means clustering to segment the scene into visually distinct regions.
- Outputs a blended visualization of the original feed and its segmented version.

### Capture on Command:
- Save the segmented frame to a file when you press the `c` key.

### Real-Time Interaction:
- See the segmentation results live and quit anytime by pressing `q`.

## Installation

### Prerequisites
- Python 3.x
- Required Python libraries:
  - `opencv-python`
  - `numpy`

### Install Dependencies
Run the following command to install the necessary libraries:
```bash
pip install opencv-python numpy

```

## Customization

### Adjust K-Means Clusters:
Change the value of `k` in the script to modify the number of segments:

```python
k = 4  # Default value, adjust as needed
```
## License

This project is licensed under the MIT License. 

## Contributions

Contributions are welcome! If you have ideas to enhance the project, feel free to create a pull request or open an issue.


 
