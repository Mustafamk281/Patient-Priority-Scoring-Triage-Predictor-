Patient Priority Scoring (Triage Predictor)

This project is a PyTorch-based neural network designed to predict patient urgency levels (Low, Medium, High) using vital signs and symptom data.

The model architecture consists of:

    Input Layer: Patient features (vitals + symptoms)

    Hidden Layer 1: 35 neurons, tanh activation

    Hidden Layer 2: 20 neurons, ReLU activation

    Output Layer: Softmax for 3-class probability distribution

Key features include:

    Manual gradient descent implementation

    L2 regularization for better generalization

    Step-by-step forward & backward propagation

    Controlled hyperparameters for experimentation

This project serves as both a learning exercise in building neural networks from scratch and a foundation for future work, such as integrating CNNs, RNNs, or deploying the model as a real-world medical triage assistant.
