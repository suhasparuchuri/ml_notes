
- Ensemble model: The models which combine different smaller models into one large model. 

- We can't generally train models on strings. We definitely need to convert them into some numbers.

- `pd.get_dummies()` is a function in pandas that is used to perform one-hot encoding on categorical data. It converts categorical variables into a binary matrix (0s and 1s).

ML UDEMY COURSE
- Feature scaling is only applied on columns (basically whole feature)
- Feature scaling:
    - Normalization : (X-Xmin)/(Xmax-Xmin) , Range: [0,1]
    - Standardization : (X-mean)/SD , Range is mostly [-3,3] as ~99.7% values lie in b/w this range in normal distribution. Values out of this range are outliers.
