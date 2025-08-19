🖼️ Image to Grayscale Conversion using Python

**This project demonstrates how to convert a color image (RGB) into a grayscale image using Python, NumPy, and Matplotlib. The grayscale conversion is based on luminance perception (weighted RGB channels) along with gamma correction to enhance accuracy.**

📌 Features

-Reads an image using Matplotlib

-Splits image into RGB color channels

-Applies gamma correction

-Converts the image to grayscale using luminance coefficients:

-Red weight: 0.2126

-Green weight: 0.7152

-Blue weight: 0.0722

**Displays both the original image and the grayscale image side by side**

⚙️ Installation

-Clone the repository and install required dependencies:

**git clone https://github.com/your-username/image-to-grayscale.git
cd image-to-grayscale**


**Install required Python libraries:**

-pip install matplotlib numpy

🚀 Usage

**Save your image in a local folder (e.g., kid_madara.jpg) and update the file path inside the script:**

-input_image = imread("D:/Python/Picture To Grayscale myenv1.0/kid madara.jpg")


-Run the script:

-python grayscale_converter.py

📊 Code Workflow

-Import libraries: Matplotlib & NumPy

-Read input image using imread()

-Extract R, G, B channels

-Apply gamma correction (gamma = 1.04)

-Convert to grayscale using:

-grayscale_image = r_const * (r ** gamma) + g_const * (g ** gamma) + b_const * (b ** gamma)


-Display images using Matplotlib subplots

🖼️ Output Example

**The program displays:**

-Left: Original RGB Image

-Right: Converted Grayscale Image

📈 Applications

-Preprocessing images for Machine Learning / Computer Vision

-Enhancing visibility in medical imaging

-Artistic and aesthetic transformations

-Reducing computational complexity in image processing
