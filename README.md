# Presentation Assignment: Anomaly Detection 

Term: Spring 2022

+ **Team**: Group 5
+ **Project title**: Maximizing Accuracy under Fairness Constraints (C-LR and C-SVM) and Information Theoretic Measures for Fairness-Aware Feature selection (FFS) 
+ **Team members**:
  + Jiachen Hu
  + Jiayi Wang
  + [Marcus Loke](https://www.linkedin.com/in/lokemarcus/) (ml4636@columbia.edu)
  + Qinyun Luo
  + Rohit Kundurthi
  + Xin Li
  + Yafei Wen
  + Yinjie Dai
  + Yunzi Ma
  + Zheyu Xu

+ **Project summary**: This project explores...

+ **Results summary**: The FFS models performed best in calibration and had comparable accuracy with the unconstrained models. The FFS-LR model was picked over the FFS-SVM as the model of choice since it is more interpretable and simpler to implement.

+ **Technologies used**: Python
	
+ **Contribution statement**: All team members approve our work presented in this GitHub repository including this contributions statement. 
  + **Chang Lu (cl4150)** worked on the EDA and feature selection with Marcus and implemented the SVM and C-SVM algorithm. He adapted the helper function, SVM_scratch.py, and customized it for our C-SVM algorithm. He also created the function to compute calibration.
  + **Jiaxin Yu (jy3161)** researched on the A2 paper and worked on the unconstrained SVM, C-SVM and plotting of the calibration plots (but not used in final report). 
  + **Marcus Loke (ml4636)** is the team lead for this project. He researched on the A2 paper, performed the EDA and data cleaning in R, and implemented the LR, C-LR and FFS algorithms in Python. He adapted the helper functions (utils.py, utils2.py, loss_funcs.py, helper.py) and customized it for the constrained models and he also worked with Chang on the C-SVM algorithm. He also created the function to compute p-rule. 
  + **Xiran Lin (xl3000)** researched on both A2 and A7 papers and contributed to the building and testing of the SVM and C-SVM models. He attempted the calibration computation for LR and SVM and prepared the presentation slides. He is the presenter for the team.
  + **Zaigham Khan (zak2131)** researched on both A2 and A7 papers and was responsible for understanding and coding the FFS algorithm. He brought the team up to speed on the A7 method and how it differed from the A2 method. He also identified the feature to remove based on the Shapley accuracy and discrimination and worked with Marcus on the helper function, utils2.py.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
