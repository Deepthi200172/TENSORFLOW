# TensorFlow.js Transfer Learning Project

This project demonstrates how to use TensorFlow.js for transfer learning with a MobileNet model. We classify different people in real-time using the webcam feed. The project includes three main files: `index.js`, `webcam.js`, and `res-dataset.js`. The training and predictions are performed directly in the web browser.

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)


## Overview
This project uses transfer learning to classify images of three different people: Deepthi, Shyam, and Mathi. The base model is MobileNet, and some of its layers are frozen during training. The training process occurs in the web browser, utilizing TensorFlow.js. After training, the model can predict the class of a person in real-time using webcam input.

## Getting Started
To get started with this project, clone the repository and open `index.html` in a web browser. Ensure that you have an active internet connection to load TensorFlow.js and other necessary libraries.

### Prerequisites
- A web browser with support for WebGL.
- An active internet connection to load TensorFlow.js and other libraries.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Deepthi200172/TENSORFLOW.git
    ```
2. Open the `index.html` file in a web browser.

## Project Structure
- `index.js`: Main JavaScript file that handles model loading, training, and prediction.
- `webcam.js`: Manages webcam access and captures frames for training and prediction.
- `res-dataset.js`: Utility for managing the dataset, including adding examples and handling data preparation.

## Usage
1. Open `index.html` in your web browser.
2. Allow the browser to access your webcam.
3. Capture images for each class (Deepthi, Shyam, Mathi) by clicking the respective buttons.
4. Train the model by clicking the "Train" button.
5. After training is complete, the model will start making predictions on the live webcam feed and display the predicted class.

## Dependencies
- [TensorFlow.js](https://www.tensorflow.org/js)
- [Webcam-easy](https://github.com/bensonruan/webcam-easy) (for easy webcam handling)

These libraries are included in the `index.html` file through CDN links.

## Contributing
Contributions are welcome! Please submit pull requests or open issues to discuss changes.

### Steps to Contribute
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
- TensorFlow.js team for creating and maintaining the library.
- The contributors of the MobileNet model.
- Webcam-easy library for simplifying webcam integration.

---

This README provides an overview of the project, instructions for getting started, and details on the project structure and usage. For any further questions or issues, please feel free to contact the project maintainers or open an issue on GitHub.

