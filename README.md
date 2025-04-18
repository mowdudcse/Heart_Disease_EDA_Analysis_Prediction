<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

<h2>🫀 Heart Disease Prediction: EDA and ML Modeling</h2>

<p>This project focuses on <strong>Exploratory Data Analysis (EDA)</strong> and <strong>Machine Learning modeling</strong> to predict the presence of heart disease using a publicly available dataset. It walks through the entire process from data preprocessing, visualization, to building and tuning a classification model.</p>

<hr />

<h3>📂 Project Structure</h3>

<ul>
  <li><code>Heart Disease EDA Analysis Prediction.ipynb</code> – Main Jupyter notebook containing code, visualization, and model development.</li>
  <li><code>heart.csv</code> – The dataset used for analysis (must be uploaded at runtime in Google Colab).</li>
  <li><code>README.md</code> – Project overview and documentation.</li>
</ul>

<hr />

<h3>📊 Dataset Overview</h3>

<ul>
  <li><strong>Source</strong>: <a href="https://www.kaggle.com/code/farzadnekouei/heart-disease-prediction/input">Kaggle Heart Disease Dataset</a></li>
  <li><strong>Size</strong>: 303 rows, 14 columns</li>
  <li><strong>Target Variable</strong>: <code>target</code> (1 = disease, 0 = no disease)</li>
</ul>

<hr />

<h3>🔍 Exploratory Data Analysis (EDA)</h3>

<p>The notebook includes thorough EDA using <strong>Seaborn</strong> and <strong>Matplotlib</strong>, including:</p>

<ul>
  <li><strong>Dataset Info & Null Check</strong></li>
  <li><strong>Feature Type Conversion</strong></li>
  <li><strong>Univariate Analysis</strong> (distributions of continuous features)</li>
  <li><strong>Bivariate Analysis</strong> (categorical vs target, numerical vs target)</li>
  <li><strong>Boxplots, Countplots, and Histograms</strong></li>
</ul>

<hr />

<h3>🧹 Data Preprocessing</h3>

<p>Preprocessing steps include:</p>

<ul>
  <li>Identification and transformation of categorical vs numerical features</li>
  <li>Normalization using <code>StandardScaler</code></li>
  <li>Transformation with <code>Box-Cox</code> for skewed distributions</li>
  <li>Splitting data using <code>train_test_split</code> for training and testing</li>
</ul>

<hr />

<h2 id="gallery">🖼️ Gallery</h2>

<h3>📌 Distribution of Categorical Variables</h3>
<img src="https://github.com/user-attachments/assets/d2bd7baa-550a-41ee-8ad2-94b2bbacb8cf" width="600" height="400">

<h3>📌 Categorical Features vs Target Stacked Barplots</h3>
<img src="https://github.com/user-attachments/assets/540b7d21-5e15-4e01-a4d9-ce617fbbdffe" width="600" height="400">

<h3>📌 All Category EDA</h3>
<img src="https://github.com/user-attachments/assets/f0cb9f96-1ef6-440e-b918-2d5857c0db9f" width="600" height="400">

<h3>🛠️ Training and Testing Accuracy for Models</h3>

<h3>📌 KNN CLassification</h3>

<img width="316" alt="image" src="https://github.com/user-attachments/assets/05a75f67-6a24-437e-89b5-5bf12a735776" />

<br>

<h3>🤖 Model Building</h3>

<h4>K-Nearest Neighbors (KNN)</h4>

<ul>
  <li>Implemented a KNN classifier from <code>sklearn</code></li>
  <li>Model evaluated using:
    <ul>
      <li>Accuracy Score</li>
      <li>Classification Report</li>
    </ul>
  </li>
  <li>Hyperparameter tuning via K loop to choose optimal <code>k</code> value</li>
  <li>Visual analysis of accuracy vs number of neighbors</li>
</ul>

<h4>Support Vector Machine (SVM)</h4>

<ul>
  <li>Explored SVM model using default parameters</li>
  <li>Accuracy score and classification report displayed</li>
</ul>

<hr />

<h3>📈 Results Summary</h3>

<ul>
  <li><strong>KNN achieved reasonable accuracy</strong>, showing trends in model performance with different <code>k</code> values.</li>
  <li><strong>SVM performed well</strong> but wasn't the main focus of tuning.</li>
  <li>Visualizations clearly demonstrate the importance of features like <code>thalach</code>, <code>oldpeak</code>, and <code>cp</code>.</li>
</ul>

<hr />

<h3>🧪 Requirements</h3>

<p>This notebook is best run on <strong>Google Colab</strong> with the following libraries:</p>

<pre><code>pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
</code></pre>

<hr />

<h3>▶️ How to Run</h3>

<ol>
  <li>Open the notebook in Google Colab.</li>
  <li>Upload the <code>heart.csv</code> dataset when prompted.</li>
  <li>Run all cells sequentially to reproduce results.</li>
</ol>

<hr />

<h3>📌 Key Learnings</h3>

<ul>
  <li>Effective EDA helps uncover patterns prior to modeling</li>
  <li>Proper preprocessing (scaling, transformation) greatly impacts model performance</li>
  <li>KNN can be a strong baseline classifier when tuned correctly</li>
</ul>

<hr />

<h3>📚 References</h3>

<ul>
  <li>Dataset: <a href="https://www.kaggle.com/code/farzadnekouei/heart-disease-prediction/input">Kaggle - Heart Disease Prediction</a></li>
  <li>EDA Techniques: Seaborn & Matplotlib documentation</li>
  <li>ML Modeling: scikit-learn</li>
</ul>

</body>
</html>
