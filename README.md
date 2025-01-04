# Tweet Emotion Recognition

This project aims to build a model that can recognize the emotion expressed in a tweet using Natural Language Processing (NLP) techniques and TensorFlow.

## Dataset

The project utilizes the [Tweet Emotion Dataset](https://github.com/dair-ai/emotion_dataset). It contains tweets labeled with various emotions, such as joy, sadness, anger, fear, and surprise.

## Methodology

1. **Data Preparation:** The dataset is loaded and split into training, validation, and test sets.
2. **Text Processing:** Tweets are tokenized, and sequences are padded/truncated for uniform length.
3. **Label Encoding:** Text labels (emotions) are converted into numerical labels.
4. **Model Building:** A deep learning model is built using TensorFlow's Keras API, incorporating embedding, LSTM, and dense layers.
5. **Model Training:** The model is trained on the training data and validated using the validation set.
6. **Model Evaluation:** The trained model's performance is assessed on the test dataset using accuracy and a confusion matrix.

## Usage

1. Install the necessary libraries: `pip install tensorflow numpy matplotlib nlp`
2. Run the code in a Google Colab environment or Jupyter Notebook.
3. The code will train the model, evaluate its performance, and visualize the results.

## Results

The model achieves an accuracy of 87.65% on the test dataset. The confusion matrix provides a detailed breakdown of the model's performance across different emotions.

## Acknowledgments

This project was inspired by the guided project [Tweet Emotion Recognition with TensorFlow](https://www.coursera.org/projects/tweet-emotion-tensorflow).
