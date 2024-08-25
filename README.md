<h1>Diabetes Prediction Using Machine Learning</h1>

<p>This repository contains a comprehensive Python implementation for predicting the onset of diabetes using a dataset originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The primary objective is to develop and evaluate various machine learning models to accurately predict whether or not a patient has diabetes based on certain diagnostic features.</p>

<h2>Dataset Overview</h2>
<p>The dataset consists of several medical predictor variables and one target variable, <code>Outcome</code>, which indicates whether the patient has diabetes (1) or not (0). The predictor variables include:</p>
<ul>
    <li><strong>Pregnancies:</strong> Number of times the patient has been pregnant.</li>
    <li><strong>Glucose:</strong> Plasma glucose concentration.</li>
    <li><strong>BloodPressure:</strong> Diastolic blood pressure (mm Hg).</li>
    <li><strong>SkinThickness:</strong> Triceps skinfold thickness (mm).</li>
    <li><strong>Insulin:</strong> 2-Hour serum insulin (mu U/ml).</li>
    <li><strong>BMI:</strong> Body mass index (weight in kg/(height in m)<sup>2</sup>).</li>
    <li><strong>DiabetesPedigreeFunction:</strong> A function that scores the likelihood of diabetes based on family history.</li>
    <li><strong>Age:</strong> Age of the patient in years.</li>
</ul>
<p>All patients in the dataset are females at least 21 years old of Pima Indian heritage.</p>

<h2>Project Features</h2>

<h3>1. Data Exploration and Visualization</h3>
<ul>
    <li>Explore the dataset with summary statistics and check for missing values.</li>
    <li>Visualize relationships between features using pair plots, scatter plots, and correlation heatmaps.</li>
</ul>

<h3>2. Data Preprocessing</h3>
<ul>
    <li>Handle missing values and scale features using <code>StandardScaler</code>.</li>
    <li>Split the dataset into training and testing sets for model evaluation.</li>
</ul>

<h3>3. Model Building</h3>
<ul>
    <li>Train multiple machine learning models including:</li>
    <ul>
        <li><strong>Logistic Regression</strong></li>
        <li><strong>Decision Tree Classifier</strong></li>
        <li><strong>Random Forest Classifier</strong></li>
    </ul>
    <li>Evaluate model performance using accuracy, confusion matrix, classification report, and ROC-AUC score.</li>
</ul>

<h3>4. Model Evaluation</h3>
<ul>
    <li>Compare the accuracy and performance of different models.</li>
    <li>Visualize the ROC curve for the best-performing model.</li>
</ul>

<h2>Installation</h2>
<p>To run the code in this repository, you'll need to have Python installed along with the following libraries:</p>
<pre><code>pip install pandas numpy matplotlib seaborn scikit-learn</code></pre>

<h2>How to Use</h2>
<ol>
    <li><strong>Clone the repository:</strong></li>
    <pre><code>git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction</code></pre>
    <li><strong>Run the code:</strong></li>
    <p>You can run the Python script in any Python environment (e.g., Jupyter Notebook, PyCharm, VS Code). The script will load the dataset, preprocess it, train the models, and display the results.</p>
    <li><strong>Analyze the Results:</strong></li>
    <p>Review the output and visualizations to understand how the models perform in predicting diabetes.</p>
</ol>
