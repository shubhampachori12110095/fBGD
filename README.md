Suggest you go to https://github.com/fajieyuan/fBGD-version2



fBGD: Learning Embeddings From Positive Unlabeled Data with BGD

You can run FBGD_MF, which is batch gradient descent (BGD) for basic dot product or run FBGD_SVDFeature, which is BGD for SVDFeature. fBGD can be applied in fields where there are a small portion of positive examples and a large portion of negative or unlabeled examples, such image/document classification, DNA representation, CTR prediction, query autocompletion,recommendation, word embedding...
a C++ code for word embedding task can be found as follows 
(Note that FBGD_MF or FBGD_SVDFeature can be used for word embedding task with a positive weight from Glove paper (GloVe: Global Vectors for Word Representation) )

https://github.com/XinGla/AllVec
