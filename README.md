<h1 align="center">✈️ NASA Turbofan Engine Remaining Useful Life Prediction</h1>

<p align="center">
🔧 Predictive maintenance project using the NASA CMAPSS turbofan engine dataset
<br>
📊 Machine learning model to estimate Remaining Useful Life of aircraft engines from sensor telemetry
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
Aircraft engines produce large volumes of sensor data during operation.  
These measurements contain valuable information about engine health and degradation patterns over time.
</p>

<p>
This project focuses on predicting the <b>Remaining Useful Life (RUL)</b> of turbofan engines using the NASA CMAPSS dataset.  
The goal is to estimate how many operational cycles remain before an engine reaches failure.
</p>

<p>
Accurate prediction of RUL enables predictive maintenance which improves reliability, reduces maintenance cost, and enhances operational safety.
</p>

<hr>

<h2>📂 Dataset</h2>

<p>
The dataset used in this project is the <b>NASA CMAPSS Turbofan Engine Degradation Simulation Dataset</b>.
</p>

<p>
Each engine unit begins with different levels of wear and gradually degrades over time.  
Sensor readings and operational settings are recorded at every operational cycle.
</p>

<p><b>Dataset files included in this repository</b></p>

<ul>
<li>📄 train_FD001.txt : training engine trajectories until failure</li>
<li>📄 test_FD001.txt : test engine trajectories that stop before failure</li>
<li>📄 RUL_FD001.txt : true remaining useful life values for the test engines</li>
</ul>

<p><b>Dataset characteristics</b></p>

<ul>
<li>🛠 Multiple engine units</li>
<li>⏱ Cycle based time series data</li>
<li>⚙ Three operational settings</li>
<li>📡 Twenty one sensor measurements</li>
<li>📉 Progressive degradation until failure</li>
</ul>

<hr>

<h2>🔬 Project Workflow</h2>

<h3>📥 Data Preparation</h3>

<ul>
<li>Load CMAPSS dataset files</li>
<li>Assign descriptive column names</li>
<li>Merge cycle information for each engine</li>
<li>Compute Remaining Useful Life target values</li>
</ul>

<h3>📊 Exploratory Data Analysis</h3>

<ul>
<li>Visualize sensor behavior across operational cycles</li>
<li>Identify sensors that show degradation patterns</li>
<li>Analyze trends related to engine wear</li>
</ul>

<h3>⚙ Feature Engineering</h3>

<ul>
<li>Rolling mean features</li>
<li>Rolling standard deviation features</li>
<li>Temporal degradation indicators</li>
<li>Sensor trend representations</li>
</ul>

<h3>🤖 Model Development</h3>

<ul>
<li>Random Forest regression model</li>
<li>Training using engineered sensor features</li>
<li>Prediction of remaining useful life for each engine cycle</li>
</ul>

<h3>📈 Model Evaluation</h3>

<ul>
<li>Mean Absolute Error evaluation</li>
<li>NASA scoring function designed for predictive maintenance tasks</li>
</ul>

<hr>

<h2>🗂 Repository Structure</h2>

<pre>
Time-Series-Implementation-NASA

CMAPSS_TimeSeries_Evaluation.ipynb
train_FD001.txt
test_FD001.txt
RUL_FD001.txt
Damage Propagation Modeling.pdf
README.md
</pre>

<hr>

<h2>🛠 Technologies Used</h2>

<ul>
<li>🐍 Python</li>
<li>📊 Pandas</li>
<li>🔢 NumPy</li>
<li>📉 Matplotlib</li>
<li>📈 Seaborn</li>
<li>🤖 Scikit Learn</li>
</ul>

<hr>

<h2>📊 Results</h2>

<p>
The machine learning model learns degradation signals from multiple sensors and predicts the remaining operational cycles of turbofan engines.
</p>

<p>
This demonstrates how machine learning can transform raw sensor telemetry into actionable maintenance insights for aerospace systems.
</p>

<hr>

<h2>🚀 Applications</h2>

<ul>
<li>✈️ Predictive maintenance in aviation</li>
<li>🏭 Industrial equipment monitoring</li>
<li>📊 Reliability engineering</li>
<li>⏳ Time series machine learning systems</li>
</ul>

<hr>

<h2>🔭 Future Improvements</h2>

<ul>
<li>Advanced survival analysis approaches</li>
<li>Gradient boosting models</li>
<li>Sensor importance analysis</li>
<li>Deep learning based temporal models</li>
</ul>

<hr>

<h2>📚 References</h2>

<p>
NASA Prognostics Center of Excellence  
CMAPSS Turbofan Engine Degradation Simulation Dataset
</p>

<hr>

<h2>👨‍💻 Authors</h2>

<p>
<b>Arjun Vinod Patil & Anuj Dalvi</b>
</p>

<p> 
Machine Learning and Data Science
</p>

<p>  
Remote
</p>
