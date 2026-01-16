<h1>Wine Quality Prediction using Classical Machine Learning</h1>

<p>
This project uses classical machine learning techniques to predict wine quality from measurable
physicochemical properties. The focus is on understanding feature–quality relationships and
comparing two tree-based ensemble regression models.
</p>

<hr>

<h2>📌 Problem Statement</h2>
<p>
Wine quality assessment is commonly based on human sensory evaluation, which can be subjective.
This project formulates the task as a supervised regression problem, where wine quality scores
are predicted using physicochemical measurements of wine samples.
</p>

<hr>

<h2>📊 Dataset</h2>
<p>
The dataset is obtained from the <b>UCI Machine Learning Repository</b> and consists of red and white
variants of Portuguese “Vinho Verde” wine with expert-assigned quality scores.
</p>

<ul>
  <li>Data type: Tabular</li>
  <li>Total samples: ~6,500</li>
  <li>Input features: 11 physicochemical attributes</li>
  <li>Target variable: Wine quality score (numeric)</li>
</ul>

<p>
The features include acidity measures, sulfur dioxide concentrations, residual sugar,
alcohol content, density, and pH.
</p>

<hr>

<h2>⚙️ Methodology</h2>
<ul>
  <li>Data loading and basic cleaning</li>
  <li>Exploratory analysis of feature distributions</li>
  <li>Train–test split</li>
  <li>Model training using ensemble regression methods</li>
  <li>Hyperparameter tuning with GridSearchCV</li>
  <li>Performance evaluation using regression metrics</li>
</ul>

<hr>

<h2>🤖 Models Implemented</h2>
<ul>
  <li>Gradient Boosting Regressor (final selected model)</li>
  <li>LightGBM Regressor (comparative evaluation)</li>
</ul>

<p>
These models were selected to capture non-linear relationships between physicochemical
properties and wine quality scores.
</p>

<hr>

<h2>📈 Evaluation Metrics</h2>
<ul>
  <li>Root Mean Squared Error (RMSE)</li>
  <li>Mean Absolute Error (MAE)</li>
  <li>R² Score</li>
</ul>

<p>
Model selection was based on performance on a held-out test set.
</p>

<hr>

<h2>🔍 Results & Observations</h2>
<p>
The Gradient Boosting Regressor achieved lower prediction errors and higher explanatory power
compared to LightGBM for this dataset. This indicates that gradient boosting provides a better
bias–variance tradeoff for the given data size and feature set.
</p>

<p>
Alcohol content and sulfur-related features were observed to have strong influence on wine
quality predictions.
</p>

<hr>

<h2>🧠 Key Learnings</h2>
<ul>
  <li>How ensemble tree-based models handle non-linear scientific data</li>
  <li>Importance of choosing evaluation metrics appropriate for regression</li>
  <li>Empirical model selection based on performance rather than model complexity</li>
  <li>Interpreting feature importance in boosting-based models</li>
</ul>

<hr>

<h2>🚀 Possible Extensions</h2>
<ul>
  <li>Uncertainty estimation in regression predictions</li>
  <li>Feature selection and correlation analysis</li>
  <li>Application of the same workflow to other chemical or materials datasets</li>
</ul>

<hr>

<h2>🛠️ Tools & Libraries</h2>
<ul>
  <li>Python</li>
  <li>scikit-learn</li>
  <li>LightGBM</li>
  <li>NumPy, Pandas, Matplotlib</li>
</ul>

<hr>

<h2>📜 License</h2>
<p>
This project is intended for academic and educational purposes only.
</p>
