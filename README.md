# Image Caption Generator Application

This is a Flask web application that generates captions for uploaded images using a pre-trained deep learning model. The model uses a convolutional neural network (CNN) to extract features from the image, and then uses a recurrent neural network (RNN) with long short-term memory (LSTM) cells to generate the caption.

The pre-trained model was trained on the Flickr8k dataset, which consists of 8,000 images with 5 captions each. The model was trained for 30 epochs, achieving a validation loss of 2.6.

## Requirements

- Python 3.x
- Flask
- TensorFlow
- Keras
- NumPy
- Pillow (PIL)

## Usage

1. Clone this repository or download the files.
2. Install the required packages using pip: `pip install flask tensorflow keras numpy pillow`
3. Download the pre-trained model from this [Google Drive link](https://drive.google.com/file/d/1aChnqpLEAchJN8p5KfzFJ5gr2WK5z-39/view?usp=sharing) and save it in the `models` folder.
4. Run the application with the following command: `python app.py`
5. Open a web browser and navigate to `http://localhost:5000`

## Demo

A live demo of this application is available at [https://image-caption-generator-app.herokuapp.com/](https://image-caption-generator-app.herokuapp.com/).

## License

This code is released under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

This application was inspired by the following resources:

- [Show and Tell: A Neural Image Caption Generator](https://arxiv.org/abs/1411.4555) by Oriol Vinyals, Alexander Toshev, Samy Bengio, and Dumitru Erhan.
- [Image Caption Generator with Keras](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/) by Jason Brownlee.
- [Flask Web Development with Python Tutorial - Full Course](https://www.youtube.com/watch?v=MwZwr5Tvyxo) by Tech With Tim.
