# Image Segmentation Using K-Means Clustering

This project implements image segmentation using the K-Means clustering algorithm. It groups the pixels of an image into different clusters based on their color or intensity, allowing for efficient segmentation of objects within the image.

## Features
- Segments images into a specified number of clusters using K-Means.
- Supports grayscale and RGB images.
- Visualization of clustered images.
- Easy-to-use implementation for beginners and researchers.

## Prerequisites
To run this project, you need the following installed:

- Python 3.6+
- Required Python libraries:
  - `numpy`
  - `opencv-python`
  - `matplotlib`

You can install the required dependencies using:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ayushmohta7/Image-Segmentation-Using-K-Means-Clustering.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Image-Segmentation-Using-K-Means-Clustering
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place the image you want to segment in the project directory.

2. Run the script with the following command:
   ```bash
   python kmeans_segmentation.py --image <image_name> --clusters <number_of_clusters>
   ```
   Replace `<image_name>` with the name of your image file and `<number_of_clusters>` with the desired number of clusters (e.g., 3).

3. The segmented image will be displayed and saved in the project directory as `segmented_<image_name>`.

### Example
```bash
python kmeans_segmentation.py --image example.jpg --clusters 4
```

## Directory Structure
```
Image-Segmentation-Using-K-Means-Clustering/
├── kmeans_segmentation.py    # Main script for image segmentation
├── requirements.txt          # Required Python libraries
├── README.md                 # Project documentation
├── example.jpg               # Sample image (optional)
└── output/                   # Directory for saving segmented images
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements or suggestions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to the contributors and the open-source community for their support and inspiration.
