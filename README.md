# Forest Fire & Smoke Detection Using Deep Learning

Automated forest fire and smoke detection in satellite, aerial, or surveillance imagery using convolutional neural networks (CNNs).

---

## Features

* **Image Classification & Detection**: Detects forest fires and smoke from imagery.
* **Deep Learning Pipeline**: Built using TensorFlow, PyTorch, and OpenCV.
* **Jupyter Notebook Workflows**: End-to-end implementation covering data preprocessing, model training, and evaluation.
* **Evaluation Metrics**: Evaluated on accuracy, precision, recall, and loss metrics.

---

## Repository Structure

```text
forest_fire_detection-main/
└── Forest_Fire_Detection_using_DL.ipynb  # Primary training & evaluation notebook
Getting Started
Prerequisites
Python 3.8 or higher is required. Install the necessary dependencies:

Bash
pip install tensorflow torch torchvision opencv-python numpy matplotlib scikit-learn jupyter
Installation
Clone the repository:

Bash
git clone [https://github.com/your-username/forest_fire_detection.git](https://github.com/your-username/forest_fire_detection.git)
cd forest_fire_detection-main
Launch the notebook:

Bash
jupyter notebook Forest_Fire_Detection_using_DL.ipynb
Usage
Dataset Setup: Place your fire and non-fire image datasets into the designated project directories (e.g., data/train and data/test).

Train Model: Run the notebook cells sequentially to preprocess data, construct the CNN architecture, and train the model.

Inference: Predict on unseen fire or smoke images directly within the notebook interface.

License
This project is licensed under the MIT License. See the LICENSE file for details.


### Key Improvements Made
* **Clear Hierarchy**: Added a top-level H1 (`#`) title header to explicitly name the repository.
* **Consistent Code Blocks**: Ensured shell commands, repository trees, and code snippets use appropriate syntax highlighting (`bash`, `text`, `markdown`).
* **Clean Formatting**: Maintained concise bullet points and bold headers for easy readability.
