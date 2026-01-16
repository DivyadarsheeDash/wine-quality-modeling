<h1>Wine Quality Prediction using Classical Machine Learning</h1>

<p>
This project applies classical machine learning methods to predict wine quality using measurable physicochemical properties.
The goal is to understand how different features influence quality and to compare the effectiveness of linear and ensemble models.
</p>

<hr>

<h2>📌 Problem Statement</h2>
<p>
Wine quality evaluation is usually based on human sensory judgment, which can be subjective.
This project formulates the task as a supervised regression problem, where wine quality scores are predicted
from physicochemical measurements.
</p>

<hr>

<h2>📊 Dataset</h2>
<p>
The dataset is sourced from the <b>UCI Machine Learning Repository</b> and contains expert-assigned quality scores
for red and white wines.
</p>

<ul>
  <li>Data type: Tabular</li>
  <li>Samples: ~6,500</li>
  <li>Features: 11 physicochemical attributes</li>
  <li>Target: Wine quality score (numeric)</li>
</ul>

<p>
The features include acidity levels, residual sugar, sulfur dioxide concentration, alcohol content, and density.
</p>

<hr>

<h2>⚙️ Methodology</h2>
<ul>
  <li>Initial data inspection and cleaning</li>
  <li>Exploratory analysis to study feature distributions</li>
  <li>Feature scaling where required</li>
  <li>Train–test split</li>
  <li>Model training and evaluation</li>
  <li>Analysis of prediction errors and feature importance</li>
</ul>

<hr>

<h2>🤖 Models Implemented</h2>
<ul>
  <li>Linear Regression (baseline)</li>
  <li>Random Forest Regressor</li>
  <li>XGBoost Regressor</li>
  <li>LightGBM Regressor</li>
</ul>

<p>
These models were chosen to compare linear assumptions against tree-based ensemble methods.
</p>

<hr>

<h2>📈 Evaluation</h2>
<ul>
  <li>Root Mean Squared Error (RMSE)</li>
  <li>Mean Absolute Error (MAE)</li>
  <li>R² score</li>
</ul>

<p>
Cross-validation is used to assess generalization performance.
</p>

<hr>

<h2>🔍 Results</h2>
<p>
Ensemble models outperform linear regression, indicating the presence of non-linear relationships between
physicochemical properties and wine quality.
Alcohol content and sulfur-related features show strong influence on predictions.
</p>

<hr>

<h2>🧠 What I Learned</h2>
<ul>
  <li>How feature–property relationships appear in real scientific data</li>
  <li>Strengths and limitations of different regression models</li>
  <li>Importance of proper evaluation and error analysis</li>
  <li>Interpreting feature importance in tree-based models</li>
</ul>

<hr>

<h2>🚀 Possible Extensions</h2>
<ul>
  <li>Hyperparameter tuning using GridSearchCV</li>
  <li>Prediction uncertainty analysis</li>
  <li>Applying the same workflow to other chemistry or materials datasets</li>
</ul>

<hr>

<h2>🛠️ Tools & Libraries</h2>
<ul>
  <li>Python</li>
  <li>scikit-learn</li>
  <li>XGBoost</li>
  <li>LightGBM</li>
  <li>NumPy, Pandas, Matplotlib</li>
</ul>

<h2>📜 License</h2>
<p>
This project is intended for academic and educational use.
</p>
