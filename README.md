# *Drugless Extracellular Hydrogels Enable the Reprogramming of Malignant Glioblastoma*
*Jungwoo Kim<sup>1,2§</sup>, Jaeseung Yei<sup>1,2,3§</sup>, Daeun Lee<sup>4,5,6§</sup>, Seunghee Jeong<sup>4,5,6</sup>, Seungmin Ryu<sup>2,3</sup>, NaKyeong Lee<sup>1,3</sup>, Seong-Eun Ryu<sup>1,2,3</sup>, Donghee Son<sup>2,7,8</sup>, Chun Gwon Park<sup>1,3,9,10</sup>, Seong-Gi Kim<sup>2,3</sup>, Jaecheol Lee<sup>4,5,6,10,11</sup>\*, Minah Suh<sup>1,2,3,10,11,12</sup>\*, Mikyung Shin<sup>1,2,3,10</sup>\*<br>*

*<sup>1</sup>Department of Intelligent Precision Healthcare Convergence, Institute for Cross-disciplinary Studies, Sungkyunkwan University, Suwon 16419, Republic of Korea<br>*
*<sup>2</sup>Center for Neuroscience Imaging Research, Institute for Basic Science, Suwon 16419, Republic of Korea<br>*
*<sup>3</sup>Department of Biomedical Engineering, Institute for Cross-disciplinary Studies, Sungkyunkwan University, Suwon 16419, Republic of Korea<br>*
*<sup>4</sup>Department of Biopharmaceutical Convergence, Sungkyunkwan University, Suwon 16419, Republic of Korea<br>*
*<sup>5</sup>School of Pharmacy, Sungkyunkwan University, Suwon 16419, Republic of Korea<br>*
*<sup>6</sup>Epigenome Dynamics Control Research Center (EDCRC), School of Pharmacy, Sungkyunkwan University, Suwon 16419, Republic of Korea<br>*
*<sup>7</sup>Department of Electrical and Computer Engineering, Sungkyunkwan University, Suwon, Republic of Korea<br>*
*<sup>8</sup>Department of Artificial Intelligence System Engineering, Sungkyunkwan University, Suwon, Republic of Korea<br>*
*<sup>9</sup>Biomaterials Research Center, Korea Institute of Science and Technology, Seoul, Republic of Korea<br>*
*<sup>10</sup>Department of Biomedical Institute for Convergence at SKKU (BICS), Sungkyunkwan University, Suwon 16419, Republic of Korea<br>*
*<sup>11</sup>IMNEWRUN Inc., Suwon 16419, Republic of Korea<br>*
*<sup>12</sup>KIST-SKKU Brain Research Center, Suwon 16419, Republic of Korea<br>*

*§ These authors contributed equally to the work<br>*
*&ast; Correspondence to be addressed: mikyungshin@skku.edu; minahsuh@skku.edu; jaecheol@skku.edu*






# Description
This repository contains the R code used to produce all the analyses and figures presente in the article.<br>

The underlying data used for the analyses have been deposited to GEO. Space Ranger output found within the sipped files in folders. To generate these files, raw FastQ files from the Nova seq were processed with the Space Ranger pipiline (v. 1.2.2, 10x Genomics), where the reads were mapped to the mm10 (mouse) reference genome. Manual spot annotation was performed in the Rstudio.<br>

Seurat/STUtility object were generated from the Space Ranger output files, using the R packages STUtility (v.1.1.1) and Seurat (v. 4.1.1) in R (v. 4.0.5) or using Seurat (v. 4.3.0.1) in R (v. 4.2.3).<br>

The data processing workflows have been illustrated here.<br>


![all_gathered](https://github.com/user-attachments/assets/c3f8d8cc-6e47-4353-9385-7d19119f3704)
