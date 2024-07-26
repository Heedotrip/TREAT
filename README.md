# *TREAT paper title*
선생님<sup>\*</sup>, 선생님<sup>*</sup>, 교수님<sup>*</sup>, 교수님<sup>*</sup>
§ These authors contributed equally to the work
* Corresponding authors


## Description
This repository contains the R code used to produce all the analyses and figures presente in the article.

The underlying data used for the analyses have been deposited to GEO. Space Ranger output found within the sipped files in folders. To generate these files, raw FastQ files from the Nova seq were processed with the Space Ranger pipiline (v. 1.2.2, 10x Genomics), where the reads were mapped to the mm10 (mouse) reference genome. Manual spot annotation was performed in the Rstudio.

Seurat/STUtility object were generated from the Space Ranger output files, using the R packages STUtility (v.1.1.1) and Seurat (v. 4.1.1) in R (v. 4.0.5) or using Seurat (v. 4.3.0.1) in R (v. 4.2.3).

The data processing workflows have been illustrated here.
