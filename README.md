# RSB
Robust Successive Binarizations technique for Change Detection in Hyperspectral Images

This procedure relies on the computation of specific dissimilarity measures which have been introduced here:

Falini, A., Tamborrino, C., Castellano, G., Mazzia, F., Mininni, R. M., Appice, A., & Malerba, D. (2020, July). Novel reconstruction errors for saliency detection in hyperspectral images. In International Conference on Machine Learning, Optimization, and Data Science (pp. 113-124). Springer, Cham

also a new measure based on the Pearson correlation coefficient is adopted.
Successive binarization techniques are used in a novel formulation and are proven to be robust, with respect to the different scenarios produced by the chosen measure. Moreover, it is  fully automatic.

The method has been tried on the following three datasets:

-Hermiston, https://gitlab.citius.usc.es/hiperespectral/ChangeDetectionDataset/-/tree/master/Hermiston

-USA, https://rslab.ut.ac.ir/documents/81960329/82034892/Hyperspectral_Change_Datasets.zip

-River, http://crabwq.github.io
