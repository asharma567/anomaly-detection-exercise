There a few (actually many) techniques for anomaly detection.  Lumped into this are also novelty and outlier detection.

### Use cases

* Fraud Detection
* Loan Application Processing
* Intrusion Detection
* Activity Monitoring
* Network Performance
* Fault Diagnosis
* Novelties in Images
* Novelty in Text (and topics)
* Misslabeled data in training data
* Time series monitoring
* [Medical Condition Monitoring](http://hortonworks.com/blog/improving-quality-of-care-with-apache-hadoop-at-uc-irvine-medical-center/)
* Satellite Image Analysis
* etc.
* etc.

### Static

#### Visual

* Histogram
* Box plot

#### Statistical

* Grubb's test
* Ordinary Least Squares

### Dynamic

#### Statistical

* Moving Average (+ STD)
* Poisson (or distribution based)

### Automated

#### Supervised
* Random Forest
* One class SVM
* Any other classifier really

#### Unsupervised
* Affinity Propagation
* DBSCAN
* K-means
* Adapted kNN

### More Robust

Use an [ensemble](https://speakerdeck.com/astanway/bring-the-noise-continuously-deploying-under-a-hailstorm-of-metrics) of anomaly detection techniques!

## References

* [Anomaly Detection: A survey](file:///Users/jonathandinu/Downloads/anomally_detection%20(1).pdf)
* [A Survey of Outlier Detection Methodologiess](http://eprints.whiterose.ac.uk/767/1/hodgevj4.pdf)
* [Trend and Event Detection in Social Streams](http://blogs.ischool.berkeley.edu/i290-abdt-s12/files/2012/08/Kostas_Trends_Sept_13_2012.pdf)