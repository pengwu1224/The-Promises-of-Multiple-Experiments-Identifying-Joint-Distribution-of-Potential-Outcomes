# The Promises of Multiple Experiments: Identifying Joint Distribution of Potential Outcomes

Reproducible code for simulation and application in the article "The Promises of Multiple Experiments: Identifying Joint Distribution of Potential Outcomes".


**For Application:**

- The data from Phase III Adjuvant Colon Clinical Trials (ACCTs) is available in this article below:
  - Stuart G. Baker, Daniel J. Sargent, Marc Buyse, and Tomasz Burzykowski. Predicting treatment effect from
surrogate endpoints and historical trials: An extrapolation involving probabilities of a binary outcome or survival
to a specific time. Biometrics, 1(68):248–257, 2012, https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1541-0420.2011.01646.x.  

- ACCT_data.R: this file contains the code for data analysis.
  - To reproduce all the results presented in the application, simply run this file. 

- All results generated by this application are saved in the "figures/" directory.

**For Simulation:** 


- GenData.R: data-generating mechanisms for cases (C1)-(C6) in the manuscript. 

- Simulation code, which utilizes 'GenData.R' for generating simulated datasets. 
  - MainC1.R: main code for simulation case (C1).   
  - MainC2.R: main code for simulation case (C2).
  - MainC3.R: main code for simulation case (C3).   
  - MainC4.R: main code for simulation case (C4).

- To reproduce all simulation results, run the file prefixed with "Main" one by one.

- All simulation results are saved in the "result/" directory.
  
