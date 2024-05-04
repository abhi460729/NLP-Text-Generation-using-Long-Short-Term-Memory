# NLP-Text-Generation-using-Long-Short-Term-Memory
NLP Text Generation using Long Short-Term Memory

In this project, I developed a text generation model using a Long Short-Term Memory (LSTM) architecture to predict and generate sequences of text. The workflow involved the following key steps:

#### Data Collection and Preprocessing
I obtained the text data from Project Gutenberg and preprocessed it by converting the text to lowercase and creating a list of sentences.
I tokenized the text data, where each unique word was assigned a unique numerical index, allowing for easier processing by the neural network.
I created input sequences from the text, ensuring consistent sequence lengths by padding shorter sequences with zeros.
#### Model Building and Training
I built an LSTM-based model with a Bidirectional LSTM layer for better context comprehension and an embedding layer for word representations.
The model was compiled using the Adam optimizer and categorical cross-entropy loss, and I employed an early stopping callback to prevent overfitting.
I trained the model on the prepared sequences, using the last word in each sequence as the target label and all previous words as the input data.
#### Text Generation and Model Evaluation
I tested the model by generating new text based on a seed input and predicted subsequent words to create a story-like output.
To evaluate model performance, I plotted the loss and accuracy metrics over the training epochs, allowing for an assessment of the model's learning progression and the effectiveness of early stopping.
Overall, this project demonstrated proficiency in natural language processing, deep learning, and LSTM architectures for text generation, showcasing the ability to build a practical text-based application and evaluate its performance.
