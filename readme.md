Multimodal Fake News Detection Using Early Fusion

Project Structure

The project contains the following files:

Project/
│
├── early.ipynb
├── requirements.txt
└── README.md

The Jupyter Notebook contains the complete implementation, including data preprocessing, feature extraction, feature projection, fusion operations, model training and evaluation.

3. Requirements

The project requires:

Python 3.10 or later (use the Python version tested with the notebook).

Jupyter Notebook or JupyterLab.
PyTorch.
Transformers.
Torchvision.
Scikit-learn.
Pandas.
NumPy.
Matplotlib.
Seaborn.
Pillow.

A CUDA-compatible NVIDIA GPU is recommended to accelerate feature extraction and model training. CPU execution may also be possible but will take considerably longer.

- Installation

Step 1: Download and clone the project

Download the project folder and extract it to your preferred directory.

git clone https://github.com/AaribAzfar/Study-of-Feature-Level-Fusion-Operations.git

Step 2: Create a virtual environment (recommended)

Open a terminal in the project directory and run:

python -m venv .venv

Activate the environment.

Windows:

.venv\Scripts\activate

Linux / macOS:

source .venv/bin/activate

Step 3: Install dependencies

Install the required Python libraries using:

pip install -r requirements.txt

For GPU execution, ensure that the installed PyTorch version is compatible with your NVIDIA GPU, CUDA environment and drivers. Follow the official PyTorch installation instructions if a different installation is required.

Step 4: Launch Jupyter Notebook

Run:

jupyter notebook

Open Project_Notebook.ipynb in your browser.

- Dataset Preparation

This project uses the Fakeddit multimodal dataset.

The dataset included in the github repo.

- Running the Notebook

Once the dependencies and dataset are prepared:

Open Project_Notebook.ipynb.

Select the Python environment containing the installed dependencies.

Execute the notebook cells sequentially, starting from the first cell.

Allow the notebook to perform data loading and preprocessing.

Execute feature extraction using mBERT and ResNet50.

Run the training and evaluation sections for the three fusion methods.

Review the resulting evaluation metrics and confusion matrices.

The notebook contains the complete experimental workflow.

Important: The pretrained mBERT model and required model weights may be downloaded automatically when first used, depending on the notebook configuration. An internet connection may therefore be required during the initial execution.


Sheikh Muhammad Aarib Azfar

Project Capstone – Multimodal Fake News Detection

Research Focus: Comparative Analysis of Feature-Level Early Fusion Operations.
