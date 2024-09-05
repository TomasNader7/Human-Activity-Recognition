<h1>Machine Learning Model for Human Activity Recognition</h1>

<p>This project builds a classification model to predict human activities based on sensor data collected from smartphones. We used various machine learning algorithms, such as <strong>Perceptron</strong>, <strong>Random Forest</strong>, and <strong>Support Vector Machine (SVM)</strong>, to classify the activities. The dataset includes multiple features that represent different motion signals.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#model-evaluation">Model Evaluation</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributors">Contributors</a></li>
</ul>

<h2 id="overview">Overview</h2>
<p>The goal of this project is to predict the type of physical activity (e.g., walking, standing, running) based on sensor data (accelerometer and gyroscope). Three models are trained and evaluated for performance based on <strong>accuracy</strong>, <strong>precision</strong>, <strong>recall</strong>, and <strong>F1-score</strong>.</p>

<h2 id="dataset">Dataset</h2>
<p>The dataset contains time-series data from wearable sensors. Each observation is labeled with an activity type.</p>
<ul>
    <li><strong>Features:</strong> A variety of motion signals (e.g., acceleration, angular velocity) collected from smartphone sensors.</li>
    <li><strong>Labels:</strong> Activities such as walking, running, sitting, and standing.</li>
</ul>

<h2 id="installation">Installation</h2>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/your-repo/human-activity-recognition.git
cd human-activity-recognition
        </code></pre>
    </li>
    <li>Install the required dependencies:
        <pre><code>pip install -r requirements.txt
        </code></pre>
    </li>
    <li>Download the dataset from the provided link and place it in the appropriate directory.</li>
    <li>Run the main script to train and evaluate the models:
        <pre><code>python main.py
        </code></pre>
    </li>
</ol>

<h2 id="model-evaluation">Model Evaluation</h2>
<p>We used the following classifiers:</p>
<ul>
    <li><strong>Perceptron</strong></li>
    <li><strong>Random Forest Classifier</strong></li>
    <li><strong>Support Vector Machine (SVM)</strong></li>
</ul>

<h3>Performance Metrics:</h3>
<ul>
    <li><strong>Accuracy</strong></li>
    <li><strong>Precision</strong></li>
    <li><strong>Recall</strong></li>
    <li><strong>F1-score</strong></li>
</ul>
<p>The models were evaluated using cross-validation as well as a separate testing set. The evaluation results for different training sizes are plotted and compared.</p>

<h2 id="results">Results</h2>
<p>The following is a comparison of the models' performance:</p>

<table>
    <thead>
        <tr>
            <th>Model</th>
            <th>Accuracy (Test)</th>
            <th>Precision (Test)</th>
            <th>Recall (Test)</th>
            <th>F1-score (Test)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Perceptron</td>
            <td>92%</td>
            <td>95%</td>
            <td>94%</td>
            <td>94%</td>
        </tr>
        <tr>
            <td>Random Forest</td>
            <td>93%</td>
            <td>93%</td>
            <td>92%</td>
            <td>92%</td>
        </tr>
        <tr>
            <td>SVM</td>
            <td>95%</td>
            <td>95%</td>
            <td>94%</td>
            <td>95%</td>
        </tr>
    </tbody>
</table>

<p>For more detailed plots and analysis, refer to the visualization section in the main script.</p>

<h2 id="usage">Usage</h2>
<ul>
    <li>To train the models with different training sizes, modify the <code>training_sizes</code> list in the script.</li>
    <li>The results for each model are saved and can be further analyzed using tools like Pandas and Seaborn.</li>
</ul>

<h2 id="contributors">Contributors</h2>
<ul>
    <li><strong>Your Name</strong> - <a href="https://github.com/your-profile">GitHub Profile</a></li>
</ul>
