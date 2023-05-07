# LiU-Master-Thesis
Master Thesis: Optimal designs for sub-regions’ effects in multi-environment crop variety testing

Growing population, limited cultivable land size, and climate change are the major challenges that the world is facing at present. To counter these issues, the United Nations has advocated the need for genetic diversity in agriculture. In order to provide a credible recommendation to the farmers, the crops must be thoroughly tested in multi-environment trials to obtain trustworthy empirical support. Since the environment is a large, complex
and diverse set-up, it could be logically divided into smaller sub-regions based on their homogeneity between them. The allocation of crop trials in different sub-regions could be further determined by optimal design criterion, which estimates optimal designs to ensure estimation of parameters without bias and with minimum variance.

A hierarchical linear mixed model which involves sub-region trials was considered.The best linear unbiased estimator and its covariance matrix that measure the changes of variables together, for the sub-regions’ effects were obtained. The standard and weighted A-design criterion were formulated using approximate and exact methods. The real data example of the Indian maize zone was considered and its variances were used for the calculation of the optimal design. The OptimalDesign package in R was used for the implementation of optimal design, which illustrated that the standard A-criterion gives equal weightage to the sub-region for the allocation of trials. The weighted A-Criterion resulted in the allocation of trials to sub-region based on the value of their coefficients. The constraints-based examples were also performed, which highlights the effective consideration of limitations that may arise due to any practical issue or requirements. It was also observed that higher variance in the sub-region leads to lower allocation of trials which can assist in decision-making.


List of Tables

1 Introduction 

  1.1 Background 
  
  1.2 Problem 
  
  1.3 Goal 
  
  1.4 Motivation 
  
2 Literature Review 

3 Model Specification 

  3.1 Linear Mixed Models 
  
  3.2 Linear Mixed Model - The Specific Model 
  
4 Estimators 

  4.1 Best Linear Unbiased Estimator- BLUE 
  
  4.2 Computation of Covariance Matrix of BLUE 
  
5 Optimal Design 

  5.1 Exact and Approximate Design 
  
  5.2 Design Criteria 
  
6 OptimalDesign(OD) package in R 

7 Optimal design - example 

  7.1 Description 
  
  7.2 Methods - Exact and Approximate Designs for Fixed effects 
  
8 Results 

  8.1 Standard A-Criterion 
  
  8.2 Weighted A-criterion 
  
9 Discussion 

10 Conclusion 

11 Limitations, Future Work and Ethical Consideration
