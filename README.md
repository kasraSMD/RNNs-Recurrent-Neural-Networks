# RNNs
# Recurrent Neural Networks (RNNs)

A practical collection of **Recurrent Neural Network (RNN)** examples and experiments implemented with deep learning frameworks.

This repository provides hands-on examples covering different types of recurrent architectures, including **Simple RNNs, LSTMs, GRUs, Seq2Seq models, and Attention-based models**. The notebooks progress from fundamental sequence modeling concepts to more practical applications in text, time series, computer vision, and natural language processing.

## 📚 Contents

The repository includes the following topics and projects:

| #  | Topic                                         | Description                                                      |
| -- | --------------------------------------------- | ---------------------------------------------------------------- |
| 01 | **Simple RNN**                                | Introduction to recurrent neural networks and sequence modeling  |
| 02 | **RNN with Different Sequence Lengths**       | Working with sequences of different lengths                      |
| 03 | **Cryptocurrency Prediction**                 | Time-series prediction using recurrent neural networks           |
| 04 | **CNN + LSTM**                                | Combining convolutional and recurrent architectures              |
| 05 | **Video Action Recognition**                  | Using CNNs for feature extraction and RNNs for temporal modeling |
| 06 | **Word Embeddings & Analogies**               | Exploring semantic relationships using word embeddings           |
| 07 | **Text Classification — Emojify**             | Text classification using recurrent architectures                |
| 08 | **Shahnameh Text Generation**                 | Character/text generation using an RNN-based language model      |
| 09 | **Seq2Seq — Number Addition**                 | Sequence-to-sequence learning with recurrent networks            |
| 10 | **Neural Machine Translation with Attention** | Date-format conversion using Seq2Seq and Attention               |
| 11 | **NMT with Attention**                        | Neural machine translation using attention mechanisms            |
| 12 | **Image Captioning with Attention**           | Generating natural-language descriptions for images              |

## 🧠 Models Covered

### Simple RNN

The basic recurrent neural network architecture for processing sequential data.

RNNs maintain a hidden state that allows information from previous time steps to influence future predictions.

### LSTM

**Long Short-Term Memory (LSTM)** networks are designed to better capture long-term dependencies and reduce problems such as vanishing gradients.

### GRU

**Gated Recurrent Units (GRUs)** provide a simpler alternative to LSTMs while maintaining the ability to model long-term dependencies.

### Seq2Seq

Sequence-to-sequence models are used for tasks where both the input and output are sequences, such as:

* Machine translation
* Sequence transformation
* Text generation
* Time-series forecasting

### Attention

Attention mechanisms allow a model to dynamically focus on the most relevant parts of an input sequence when generating an output.

This repository includes examples of attention-based models for **machine translation and image captioning**.

---

## 🗂️ Repository Structure

```text
RNNs/
│
├── images/
│
├── 01_simple-RNN.ipynb
├── 02_1_simple-RNN-diffrent-sequence-length.ipynb
├── 02_2_simple-RNN-diffrent-sequence-length.ipynb
│
├── 03_1_Cryptocurrency-predicting.ipynb
├── 03_2_Cryptocurrency-predicting.ipynb
│
├── 04_simple-CNN-LSTM.ipynb
│
├── 05-1-video-action-recognition-train-extract-features-with-cnn.ipynb
├── 05-2_video-action-recognition-train-rnn.ipynb
│
├── 06_analogy-using-embeddings.ipynb
├── 07_text-classification-Emojify.ipynb
├── 08_shahnameh-text-generation-language-model.ipynb
│
├── 09_add-numbers-with-seq2seq.ipynb
├── 10_Neural-machine-translation-with-attention-for-date-convert.ipynb
├── 11_nmt-with-attention.ipynb
├── 12_image-captioning-with-attention.ipynb
│
├── TimeDistributed.ipynb
├── crypto_data.zip
├── shahnameh.txt
└── LICENSE
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kasraSMD/RNNs.git
cd RNNs
```

### 2. Create a virtual environment

Using `venv`:

```bash
python -m venv .venv
```

Activate it on Linux/macOS:

```bash
source .venv/bin/activate
```

On Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

Install the required Python packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

Depending on the notebook, additional packages may be required.

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open any of the `.ipynb` files and run the cells sequentially.

> ☁️ **No local setup?** Upload any notebook to [Google Colab](https://colab.research.google.com/) and run it there with a free GPU.
---

## 🛠️ Technologies

The notebooks primarily use the Python deep learning ecosystem, including:

* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📓 Notebooks

Each notebook is designed as a self-contained experiment or tutorial.

You can browse the notebooks directly from the repository:

**[RNNs on GitHub](https://github.com/kasraSMD/RNNs)**

---

## 📌 Notes

* Some notebooks may require additional datasets or dependencies.
* Training time can vary depending on the model, dataset, and available hardware.
* For GPU-based training, make sure your TensorFlow environment is configured correctly.
* The notebooks are intended primarily for **learning, experimentation, and understanding recurrent neural networks**.

## 📖 Topics

`RNN` · `LSTM` · `GRU` · `Seq2Seq` · `Attention` · `Deep Learning` · `NLP` · `Time Series` · `Machine Translation` · `Image Captioning` · `Video Classification` · `TensorFlow` · `Keras`

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.

---

<div align="center">

⭐ If you find this repository useful, please consider giving it a star! ⭐

Made with ❤️ by [kasraSMD](https://github.com/kasraSMD)

</div>



