## Methodology

![method](assets/method.png)<!-- .element: class="plain"  -->

--!
###Data Extraction

**May represent up to 80% of the time spent in the project**

- Heterogeneous Data sources (DB, text files, xls, API, ...)
- Internal and external data sources
- Structured / Unstructured
- Stream Data

--!
###Data Exploration

**Descriptive analysis**

<div class="side-by-side">
  <div class="side">
    <a href="http://topepo.github.io/caret/visualizations.html" rel="">![scatterplot](assets/desc2.png)</a>
    <p> Scatterplot and smoothing </p>
  </div>
  <div class="side">
    <a href="http://topepo.github.io/caret/visualizations.html" rel="densityplot">![densityplot](assets/desc3.png)</a>
    <p> Density plot </p>
  </div>
</div>


--!
###Data Preparation

- Imputation policies (NaN / Empty data)
- Near-zero variance detection
- Remove correlated variables
- Transformation (distribution)
- ...

--!
<!-- .slide: data-transition="zoom" data-background="#e29191" -->
Why would I use Principal Components Analysis or Multiple Correspondence Analysis?

<iframe src="//giphy.com/embed/l4hmWKVDDUpiq355K" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="http://giphy.com/gifs/black-men-man-dormtainment-l4hmWKVDDUpiq355K"></a></p>

--!
<!-- .slide: data-transition="zoom" data-background="#91d87b" -->

####To reduce the dimension of the problem!

<a href="http://archive.cnx.org/contents/02ff5dd2-fe30-4bf5-8e2a-83b5c3dc0333@10/dimensionality-reduction-methods-for-molecular-motion" rel="pca">![pca](assets/pca.jpg)</a>

--!
###Enrichment

- Additive/Multiplicative/Polynomial variables combination
- Lag variables
- Aggregated variables (mean,sum,max,...)

--!
###Modelling

See [previous section](../#/3)

--!
###Data Validation (Regression)

- Coefficient of determination (R^2)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)  

![rmse](assets/rmse.png)<!-- .element: class="plain" width="45%"  -->

--!
###Data Validation (Classification 1/4)

<a href="https://www.youtube.com/watch?v=AOIkPnKu0YA" rel="confusionmat">![confusionmat](assets/confusionmatrix.jpg)</a>

--!
###Data Validation (Classification 2/4)
####[Measures](https://blogs.msdn.microsoft.com/andreasderuiter/2015/02/09/performance-measures-in-azure-ml-accuracy-precision-recall-and-f1-score/)
- *Accuracy*: (True Positives + True Negatives)/Total
- *Precision*: True Positives / (True Positives + False Positives)
- *Recall*: True Positives / (True Positives + False Negatives)
- *F1 score*: 2 (precision \* recall) / (precision + recall)
--!
###Data Validation (Classification 3/4)

AUC / ROC Curve  
![roc](assets/ROC-curve.png)<!-- .element: class="plain" width="60%"  -->

--!
###Data Validation (Classification 4/4)

Gain/Lift Chart  
![gainchart](assets/gainchhrt.png)<!-- .element: class="plain" width="60%"  -->

--!
###Distribution / Industrialization

####Results are
- Reports
- Static Dashboard
- Dynamic Dashboard
***
####Served with
- Pdf, Email
- Desktop Application
- **WebApps** [interactive]

---
## Data Science Tools
(Non exhaustive -- missing at least [DSS](https://www.dataiku.com/dss/))  
<a href="http://www.slideshare.net/machinepulse/predictive-analytics-an-overview" rel="market">![market](assets/market-predictivetools.jpg)<!-- .element:width="60%"  --></a>

---
## Data Science Languages
(Non exhaustive)  
<div class="side-by-side">
  <div class="side">
    <a href="https://www.r-project.org/" rel="r">![R](assets/Rlogo.png)<!-- .element: class="plain" width="60%"  --></a>
  </div>
  <div class="side">
    <a href="https://www.python.org/" rel="python">![Python](assets/python.png)<!-- .element: class="plain" width="60%"  --></a>
  </div>
  <div class="side">
    <a href="http://www.scala-lang.org/" rel="scala">![scala](assets/scala-logo.gif)<!-- .element: class="plain" width="80%"  --></a>
  </div>
  <div class="side">
    <a href="http://www.w3schools.com/js/" rel="javascript">![js](assets/js.png)<!-- .element: class="plain" width="80%"  --></a>
  </div>
</div>

---
## Data Science Libraries
(Non exhaustive)  
<div class="side-by-side">
  <div class="side">
    <a href="http://topepo.github.io/caret/" rel="caret">![caret](assets/caret.png)<!-- .element: class="plain" width="100%"  --></a>
  </div>
  <div class="side">
    <a href="http://scikit-learn.org/stable/index.html" rel="scikit">![scikit](assets/scikit.png)<!-- .element: class="plain" width="80%"  --></a>
  </div>
  <div class="side">
    <a href="http://spark.apache.org/" rel="spark">![spark](assets/spark.png)<!-- .element: class="plain" width="80%"  --></a>
  </div>
  <div class="side">
    <a href="https://www.tensorflow.org/" rel="tensorflow">![tf](assets/tensorflow.png)<!-- .element: class="plain" width="80%"  --></a>
  </div>
  <div class="side">
    <a href="https://d3js.org/" rel="d3js">![d3js](assets/d3js.png)<!-- .element: class="plain" width="80%"  --></a>
  </div>
</div>
