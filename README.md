# catfamilyencoders
THIS REPO IS OUTDATED

A class to encode categorical features in multiple but related ways using network analysis. Together the family of multiple encodings serve as a numerical vector for every level of a categorical feature. The class transforms a group of categorical features into corresponding numerical features which can then be used either in unsupervised learning or predictive analytics. To assist in unsupervised learning, the class has methods to save a categorical feature as network graphs and plot them.
The class has methods to extract unit vectors (numerical) for every level of a categorical feature to help, for example, in understanding relationshsips between various levels. Extracted numerical vectors can directly be used in plotting for example in tensorflow's Embedding Projector. 
Class provides methods to get categories encoded for large datasets; one can take a sample of data at a time, have categories encoded, then take another sample and have categories similarly encoded. After a number of iterations, take either a mean or median to get final category-wise vectors. 
As the encodings are calculated using a group of network analysis operations, the family of encodings is extensible. The class provides one way, but a limited one to extend it.

