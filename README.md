# Predictive Yield Curve Modeling in Reduced Dimensionality
The term structure of interest rates (“yield curve”) is a representation that plots bonds of the same type (e.g. credit quality, sector) in terms of their prices, expressed as yields, over different maturity dates. This project sets out to study the yield curve dynamics in reduced dimensionality. In literature Principal Component Analysis (PCA) is a known application to this use case.

After a successful yield curve decomposition the following steps can be considered:

@Supporting the interpretation of the first 3 principal components (PCs) in accordance with traditional (shift,slope,curvature) factors
@Testing out-of-sample fit for model yield curves, generated from reduced principal components set
@Derivation of non-linear stress scenarios for each component (1-month ahead 95% confidence)
@Testing predictability with an autoregressive timeseries model
