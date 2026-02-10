# Mini-project-on-House-Price-Prediction-using-Linear-regression
<h1>🏠 House Price Prediction Project</h1>

<p><strong>Project By:</strong> B. Saiteja<br>
<strong>Last Updated:</strong> 10-02-2026<br>
<strong>Live Application:</strong>
<a href="https://mini-project-on-house-price-prediction-w5ju.onrender.com" target="_blank">
House Price Predictor
</a><br>
<strong>GitHub Repository:</strong>
<a href="https://github.com/saitejaBandiDataScientist/Mini-project-on-House-Price-Prediction-using-Linear-regression.git" target="_blank">
View Repository
</a>
</p>

<hr>

<h2>📑 Table of Contents</h2>
<ul>
  <li>Acknowledgements</li>
  <li>Project Overview</li>
  <li>Dataset Description</li>
  <li>Project Structure</li>
  <li>Technology Stack</li>
  <li>Implementation Steps</li>
  <li>Code Explanation</li>
  <li>Model Development</li>
  <li>Deployment Process</li>
  <li>Results and Output</li>
  <li>Challenges and Solutions</li>
  <li>Future Enhancements</li>
  <li>Conclusion</li>
  <li>References</li>
</ul>

<hr>

<h2>🙏 Acknowledgements</h2>

<h3>Dataset Source</h3>
<ul>
  <li><strong>Dataset Name:</strong> House Sales in King County, USA</li>
  <li><strong>Source:</strong> Kaggle</li>
  <li><strong>Contributor:</strong> Shreya Chaudhary</li>
  <li><strong>Description:</strong> House sale prices in King County (Seattle area) from May 2014 to May 2015</li>
</ul>

<h3>Tools & Libraries</h3>
<ul>
  <li>Flask</li>
  <li>Scikit-learn</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Pickle</li>
  <li>HTML & CSS</li>
  <li>Render</li>
  <li>Git & GitHub</li>
</ul>

<hr>

<h2>📌 Project Overview</h2>

<h3>Objective</h3>
<p>
Develop a machine learning web application that predicts house prices based on
location, size, condition, and temporal factors.
</p>

<h3>Key Features</h3>
<ul>
  <li>User-friendly responsive interface</li>
  <li>Real-time house price prediction</li>
  <li>17 different input features</li>
  <li>Deployed and accessible online</li>
</ul>

<hr>

<h2>📊 Dataset Description</h2>
<ul>
  <li><strong>Total Records:</strong> 21,613</li>
  <li><strong>Features:</strong> 18 columns</li>
  <li><strong>Location:</strong> King County, Washington, USA</li>
  <li><strong>Time Period:</strong> May 2014 – May 2015</li>
</ul>

<h3>Preprocessing Steps</h3>
<ul>
  <li>Checked for missing values</li>
  <li>Extracted year, month, day from date</li>
  <li>Encoded categorical variables</li>
  <li>Selected 17 relevant features</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
House-Price-Prediction/
│
├── app.py
├── MINI_PROJECT.pkl
├── requirements.txt
├── Procfile
├── templates/
├── static/
└── data.csv
</pre>

<hr>

<h2>🛠 Technology Stack</h2>

<h3>Backend</h3>
<ul>
  <li>Python</li>
  <li>Flask</li>
  <li>Scikit-learn</li>
  <li>Pandas</li>
  <li>NumPy</li>
</ul>

<h3>Frontend</h3>
<ul>
  <li>HTML5</li>
  <li>CSS3</li>
</ul>

<h3>Deployment</h3>
<ul>
  <li>Render</li>
  <li>Gunicorn</li>
</ul>

<hr>

<h2>⚙️ Implementation Steps</h2>

<h3>Environment Setup</h3>
<pre>
python -m venv venv
venv\Scripts\activate
pip install flask numpy pandas scikit-learn gunicorn
</pre>

<h3>Model Training</h3>
<ul>
  <li>Data preprocessing</li>
  <li>Train-test split</li>
  <li>Custom Linear Regression using SVD</li>
  <li>Model saved using Pickle</li>
</ul>

<h3>Flask Development</h3>
<ul>
  <li>Created routes for prediction</li>
  <li>Handled form input</li>
  <li>Displayed prediction results</li>
</ul>

<hr>

<h2>🧠 Model Development</h2>

<p><strong>Algorithm Used:</strong> Linear Regression</p>

<h3>Why Linear Regression?</h3>
<ul>
  <li>Simple and interpretable</li>
  <li>Efficient for continuous outputs</li>
  <li>Low computational cost</li>
</ul>

<h3>Performance Metrics</h3>
<ul>
  <li>R² Score</li>
  <li>Mean Squared Error (MSE)</li>
  <li>Root Mean Squared Error (RMSE)</li>
</ul>

<hr>

<h2>🚀 Deployment Process</h2>
<ul>
  <li>GitHub repository setup</li>
  <li>Render Web Service configuration</li>
  <li>Gunicorn used as production server</li>
  <li>Automatic deployment on push</li>
</ul>

<hr>

<h2>📈 Results and Output</h2>

<h3>Sample Prediction</h3>
<ul>
  <li><strong>Input:</strong> 4 Bedrooms, 4 Bathrooms, 1340 sqft</li>
  <li><strong>Output:</strong> ₹493,648.85</li>
</ul>

<h3>Performance</h3>
<ul>
  <li>Response Time: &lt; 2 seconds</li>
  <li>Availability: 24/7</li>
</ul>

<hr>

<h2>⚠️ Challenges and Solutions</h2>

<ul>
  <li><strong>Categorical Encoding:</strong> Solved using manual label encoding</li>
  <li><strong>Model Persistence:</strong> Pickle used for serialization</li>
  <li><strong>Deployment Errors:</strong> Fixed via proper requirements and Procfile</li>
</ul>

<hr>

<h2>🔮 Future Enhancements</h2>
<ul>
  <li>Random Forest & Gradient Boosting</li>
  <li>Hyperparameter tuning</li>
  <li>Prediction history & analytics</li>
  <li>Docker and scalability</li>
</ul>

<hr>

<h2>✅ Conclusion</h2>
<p>
This project demonstrates an end-to-end machine learning pipeline —
from data preprocessing to deployment — with a real-world use case.
</p>

<hr>

<h2>📚 References</h2>
<ul>
  <li><a href="https://flask.palletsprojects.com/" target="_blank">Flask Documentation</a></li>
  <li><a href="https://scikit-learn.org/stable/" target="_blank">Scikit-learn Documentation</a></li>
  <li><a href="https://render.com/docs" target="_blank">Render Documentation</a></li>
</ul>
