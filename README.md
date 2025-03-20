# 🔮 LSTM-RNN Next Word Predict

A Long Short-Term Memory Recurrent Neural Network (LSTM-RNN) model trained on Shakespeare's Hamlet to predict the next word in a sequence.

![Shakespeare](https://img.shields.io/badge/Trained%20on-Hamlet-blueviolet)
![Accuracy](https://img.shields.io/badge/Accuracy-71%25-green)
![Python](https://img.shields.io/badge/Python-3.6%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)

## 📝 Project Overview

This project implements an LSTM-RNN architecture to predict the next word in a sequence based on previous words. The model is trained on Shakespeare's "Hamlet", a linguistically rich and complex text that provides a challenging dataset for natural language prediction tasks.

The current model achieves **71% accuracy** after training for `50 epochs`, with potential for improvement by extending the training duration or adjusting hyperparameters.

## 🚀 Getting Started

### Prerequisites

- Python 3.6+
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/NickBwalley/LSTM-RNN-Next-Word-Predictor.git
   cd LSTM-RNN-Next-Word-Predictor
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Usage

### Running the Model

Open and run the `experiments.ipynb` Jupyter notebook:

```bash
jupyter notebook experiments.ipynb
```

This notebook contains:

- Data preprocessing steps
- Model architecture
- Training process
- Evaluation metrics
- Text generation examples

### Improving the Model

To achieve higher accuracy, you can:

- Increase the number of training epochs (try 100 epochs)
- Adjust the LSTM layer configuration
- Experiment with different learning rates
- Add more layers or dropout for regularization change from 0.2 to 0.3 text the results.

## 🧪 Experiments

The default configuration achieves 71% accuracy with 50 epochs. Here are some suggested experiments:

| Configuration | Epochs | Expected Accuracy |
| ------------- | ------ | ----------------- |
| Default       | 50     | 71%               |
| Extended      | 100    | ~80%              |
| Custom        | \*     | \*                |

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request. Here's how:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Contact

Nick Bwalley - [nickbiiybwalley@gmail.com](mailto:nickbiiybwalley@gmail.com)

Project Link: [https://github.com/NickBwalley/LSTM-RNN-Next-Word-Predictor.git](https://github.com/NickBwalley/LSTM-RNN-Next-Word-Predictor.git)

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Nick Bwalley

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🌟 Acknowledgements

- Thanks to William Shakespeare for providing the challenging linguistic dataset
- Special thanks to all contributors who help improve this project
