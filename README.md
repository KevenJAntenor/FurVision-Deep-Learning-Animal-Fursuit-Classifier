# 🧠 FurVision: Deep Learning Animal & Fursuit Classifier

## 🐍📜🤖 Python TensorFlow License

A custom-built Convolutional Neural Network (CNN) that pushes the boundaries of computer vision by accurately distinguishing between real animals and people in fursuits, while also identifying animal species. Built from scratch without relying on pre-trained models, this project demonstrates advanced deep learning techniques in image classification.

## 🌟 Key Features
- **Custom CNN architecture** designed from the ground up.
- **Dual classification system**: Animals vs. Fursuits.
- **Precise species identification** for animal images.
- **Comprehensive hyperparameter optimization** for robust results.
- Built using **pure Python** and modern deep learning frameworks.

## 🛠️ Tech Stack
- **Python**
- **TensorFlow/Keras**
- **OpenCV**
- **NumPy**
- **Matplotlib**

---

## 🚀 How to Run

Follow these steps to set up and execute the FurVision project:

### 1. **Clone the Repository**
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-repo/furvision.git
   cd furvision
```

2. Set Up the Environment
Ensure you have Python installed (version 3.7 or later). It is recommended to use a virtual environment:

```bash
python3 -m venv env
source env/bin/activate   # On Windows: .\env\Scripts\activate
```
3. Install Dependencies
Install the required Python libraries using the requirements.txt file:

```bash
pip install -r requirements.txt
```
4. Prepare the Dataset
Place your training and testing image datasets in a structured directory under dataset/:
```bash
dataset/
├── train/
│   ├── animals/
│   └── fursuits/
└── test/
    ├── animals/
    └── fursuits/
```
Replace animals and fursuits with subfolders for additional species/categories as needed.
5. Train the Model
Train the custom CNN model using the provided Jupyter Notebook:

```bash
jupyter notebook 5_Reseaux.ipynb
```
Open the notebook in your browser and follow the cells to train the network. Ensure the dataset path is correctly configured.

6. Test the Model
After training, use the Test module to evaluate the classifier on unseen data:

```bash
python Test/test_model.py
```
7. Visualize Results
Visualizations such as training metrics and classification results can be generated using Matplotlib:

Check the 5_Reseaux.ipynb notebook for live plots.
Alternatively, run:
```bash
python Test/visualize_results.py
```
8. Clean Up
Deactivate the virtual environment:

```bash
deactivate
```
 
