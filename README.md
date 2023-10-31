# Handwriting Recognition using Feed-Forward Neural Networks

Welcome to our Handwriting Recognition project repository! This project is divided into two key phases: Phase 1 involves building a feed-forward neural network **from scratch** to recognize handwritten numbers, and Phase 2 focuses on implementing a similar network using `Keras` and `TensorFlow` for recognizing handwritten alphabets.

## Phase 1: Handwritten Numbers

In this phase, we dive deep into the fundamentals of neural networks. We have constructed a feed-forward neural network from the ground up using the powerful `Numpy` library. Our approach involves flattening each handwritten number image into a vector and feeding it into the network. The network then adjusts its layer connections' weights, creating intricate nonlinear combinations. This process minimizes errors and enables accurate predictions of the corresponding handwritten numbers.

### Objectives

Our Phase 1 objectives include:

- **Data Visualization and Preprocessing:** This step involves crucial tasks like min-max normalization and one-hot encoding of labels, laying the foundation for accurate model training.
  
- **Activation Functions:** We've implemented a variety of activation functions including `Identical`, `Relu`, `LeakyRelu`, `Sigmoid`, `Softmax`, and `Tanh`, understanding their impact on the network's performance.

- **Loss Function:** The implementation of the `CrossEntropy` loss function is vital for evaluating the model's performance and making necessary adjustments.

- **Components Implementation:** We've meticulously coded the `Layer` and `FeedForwardNN` components, ensuring the neural network functions seamlessly.

- **Testing and Evaluation:** Rigorous testing of data classification is performed. We've delved into analyzing the impact of various factors such as network weighting methods, learning rate, activation functions, and batch size on the model's accuracy.

## Phase 2: Handwritten Alphabets

In Phase 2, we harness the power of high-level libraries `Keras` and `TensorFlow` for recognizing handwritten alphabets. Leveraging these libraries streamlines the process, enabling us to focus on optimizing the model for accuracy and efficiency.

### Objectives

Our Phase 2 objectives include:

- **Data Preprocessing:** Tasks like image grayscaling and one-hot encoding of labels are carried out, ensuring the data is in the optimal format for training.

- **Neural Network Implementation:** Utilizing the robust `Keras` and `TensorFlow` libraries, we've created a neural network model. This phase emphasizes the importance of choosing the right optimizer, determining the optimal number of epochs, selecting appropriate loss functions, and incorporating regularization techniques for model refinement.

- **Data Visualization:** We explore dimensionality reduction techniques, enabling intuitive data visualization, providing insights into the underlying patterns within the data.

Thank you for exploring our Handwritten Image Recognition project! If you have any questions or suggestions, please feel free to reach out. Let's innovate and learn together! 🚀
