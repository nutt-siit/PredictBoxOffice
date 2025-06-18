# Predict BOX Office Project
## Python version
- Python 3.11

## Essential Library
- numpy 2.3.0
- pandas 2.3.0
- scikit-learn 1.7.0

<div style="flex: 1;">
<b>Install Command</b>
<pre><code>pip install numpy==2.3 pandas==2.3 scikit-learn=1.7</code></pre>
</div>

## Study Elements
- classify_rating.py <br>
To train the model such that the rotten tomatoes ratings are obtained
<div style="flex: 1;">
<pre><code>python classify_rating.py</code></pre>
</div>

**Input :** training-dataset.csv & testing-dataset.csv <br>
**Output :** training_neural.csv & testing_neural.csv

- neurual_proj.csv
To get the predicted film gross via ANN
<div style="flex: 1;">
<pre><code>python neurual_proj.py</code></pre>
</div>

**Input :** training_neural.csv & testing_neural.csv <br>
**Output :** finalresult.csv 