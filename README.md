
---

# Iris Recognition through Machine Learning Techniques

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Project Description

This project implements an iris recognition system using machine learning techniques. It utilizes the CASIA IRIS dataset and employs a Convolutional Neural Network (CNN) model for accurate person identification based on iris patterns. The project was developed as a minor project during the 4th semester of B.Tech.

## Features

- Iris feature extraction using the HoughCircles algorithm
- CNN model training on the CASIA IRIS dataset
- High accuracy person identification from iris images
- User-friendly interface for dataset loading and model generation
- Visualization of model accuracy and loss
- Ability to test the model with new iris images

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Screenshots/Media](#screenshotsmedia)
- [Authors](#authors)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Prerequisites

- Python 3.x
- Required Python libraries (specify versions if necessary):
  - TensorFlow
  - Keras
  - OpenCV
  - NumPy
  - Matplotlib
- Unzip utility (for extracting the CASIA1 dataset)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/iris-recognition-ml.git
   ```
2. Navigate to the project directory:
   ```
   cd iris-recognition-ml
   ```
3. Unzip the CASIA1 dataset:
   ```
   unzip CASIA1.zip
   ```
   Note: Ensure that the unzipped CASIA1 folder is in the root directory of the project.

4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

Before running the project, make sure you have unzipped the CASIA1 dataset as described in the Installation section.

For detailed instructions on how to run the project, please refer to the `Documentation.doc` file included in the project directory. This document provides step-by-step guidance on setting up and using the iris recognition system.

## File Structure

- `CASIA1.zip` - Compressed CASIA IRIS dataset (needs to be unzipped before use)
- `CASIA1/` - Contains the unzipped CASIA IRIS dataset
- `MODEL/` - Stores the trained CNN model
- `TESTSAMPLES/` - Includes test images for model evaluation
- `Documentation.doc` - Detailed project documentation and usage instructions
- `PPT.ppt` - Project presentation slides
- `MAIN.py` - Main Python source file
- `RUN.bat` - Windows batch file to run the project
- `TEST.png` - Sample test image
- `TEST.py` - Python script for testing the model
- `Final Output.png` - Image of the final output of the iris recognition system

## Screenshots/Media

![Final Output](https://github.com/user-attachments/assets/6b29f199-bdc5-4dda-a593-c426e8923811)

*Final output of the Iris Recognition system showing the identified person.*

## Authors

This project was developed by:
- ADUPALA NIKITHA (22H51A6665)
- BIJJARAPU KARUNYA (22H51A6672)
- DARSHAN S KAGI (22H51A6676)
- DOMAKONDA ANIRUDH (22H51A6678)

## Future Improvements

- Implement real-time iris recognition using a webcam
- Enhance the model's performance with transfer learning
- Develop a web-based interface for easier access
- Integrate the system with a database for storing and managing user identities

## Contributing

Contributions to improve the project are welcome. Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

- [CASIA Iris Image Database](http://biometrics.idealtest.org/) for providing the dataset
- Our project guide and coordinator for their valuable support and guidance

## Connect with Me

- LinkedIn: [Darshan Kagi](https://www.linkedin.com/in/darshan-kagi-938836255)
- GitHub: [DarshanKagi](https://github.com/DarshanKagi)
- Email: darshankagi04@gmail.com

---

Developed with ❤️ by Darshan S Kagi and team

---
