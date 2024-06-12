# Number-MNIST-Classifier

Please click the following link to try out the predictions interactively:

###[Number MNIST Classifier](https://sfbernado.github.io/Number-MNIST-Classifier/)

## Overview

The Number MNIST Classifier is a web-based application designed to demonstrate the capabilities of machine learning for image recognition tasks. It utilizes a Convolutional Neural Network (CNN) model, built with TensorFlow, to classify handwritten digits from the MNIST dataset. Users can interact with the classifier through a simple web interface, providing a digit image from the input and indirectly receiving the model's prediction.

## Features

- Interactive Web Interface: Users can interactively test the classifier by inputting handwritten digit images on the website.
- TensorFlow Model: Implements a CNN using TensorFlow, optimized for high accuracy in digit classification. The model achieved 95% accuracy from 20 epochs of training and testing.
- Predictions: Experience the capability of direct digit classification with immediate feedback.

## Prerequisites

- JavaScript
- TensorFlow JS

## Installation

1. Clone the repository:
```bash
git clone https://github.com/sfbernado/Number-MNIST-Classifier.git
```

2. Navigate to the project repository:
```bash
cd Number-MNIST-Classifier
```

3. Start a local server:
- If you have Python installed, then:
  ```bash
  python -m http.server
  ```

- If you prefer Node.js, then:
  ```bash
  npx http-server
  ```

- Or you can use Web Server for Chrome. The tutorial can be followed by clicking the following link: https://simplewebserver.org/

4. Visit the web-based application:
```
Open your web browser and navigate to http://localhost:8000 or the port provided by your server.
```

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- MNIST Dataset: [Images](https://storage.googleapis.com/learnjs-data/model-builder/mnist_images.png) and [Labels](https://storage.googleapis.com/learnjs-data/model-builder/mnist_labels_uint8)
- [JavaScript](https://www.javascript.com/) documentation
- [TensorFlow.js](https://www.tensorflow.org/js) documentation

## Author

Stanislaus Frans Bernado

[![Gmail Badge](https://img.shields.io/badge/-stanislausfb@gmail.com-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:stanislausfb@gmail.com "Connect via Email")
[![Linkedin Badge](https://img.shields.io/badge/-Stanislaus%20Frans%20Bernado-0072b1?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/stanislausfb/ "Connect on LinkedIn")
