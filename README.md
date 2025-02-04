# *Drugless Extracellular Hydrogels Enable the Reprogramming of Malignant Glioblastoma*
Jungwoo Kim<sup>1,</sup><sup>2</sup><sup>§</sup>, Jaeseung Yei<sup>1,</sup><sup>2,</sup><sup>3</sup><sup>§</sup>, Daeun Lee<sup>4,5,6</sup><sup>§</sup>, Seunghee Jeong, Seungmin Ryu, NaKyeong Lee, Seong-Eun Ryu, Donghee Son, Chun Gwon Park, Seong-Gi Kim, Jaecheol Lee\*, Minah Suh\*, Mikyung Shin\*<br>
§ These authors contributed equally to the work<br>
&ast; Correspondence to be addressed: mikyungshin@skku.edu; minahsuh@skku.edu; jaecheol@skku.edu


## Description
This repository contains the R code used to produce all the analyses and figures presente in the article.<br>

The underlying data used for the analyses have been deposited to GEO. Space Ranger output found within the sipped files in folders. To generate these files, raw FastQ files from the Nova seq were processed with the Space Ranger pipiline (v. 1.2.2, 10x Genomics), where the reads were mapped to the mm10 (mouse) reference genome. Manual spot annotation was performed in the Rstudio.<br>

Seurat/STUtility object were generated from the Space Ranger output files, using the R packages STUtility (v.1.1.1) and Seurat (v. 4.1.1) in R (v. 4.0.5) or using Seurat (v. 4.3.0.1) in R (v. 4.2.3).<br>

The data processing workflows have been illustrated here.<br>


![all_gathered](https://github.com/user-attachments/assets/c3f8d8cc-6e47-4353-9385-7d19119f3704)
