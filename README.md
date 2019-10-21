# Practicing End-to-End Machine Learning projects!

## Context
You are working in a Real Estate company and your boss requested a ML model
to predict house prices.
Your boss tells you that your ML system will be a component in a larger system
that provides advices, therefore, it is critical to revenue.
After some interview loops, you realize that the desired ML system addresses a Regression
problem and offline learning is sufficient given that the data fits in a regular machine
(otherwise, you would have to consider, e.g., distributed processing and _off-the-core_ learning,
where the ML model uses online learning to ingest and update itself incrementally untill all data
has been processed).

## Troubleshooting

#### SSL Error
If you execute some piece of Python code that touches `urllib` (e.g., `fetch_housing_data`),
you might face some SSL error:

```
<urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate...
```

Running `pip install -U certifi` should be enough to fix the issue

## References
* Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. 2nd Edition. O'Reilly, 2019.
  * Chapter 2. End-to-End Machine Learning Project