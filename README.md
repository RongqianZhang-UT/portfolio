# PhD candidate in Statistics

## Research interests
- Statistical methodologies: High-dimensional data analysis, spatial statistics, deep learning
- Scientific applications: Imaging, neuroscience, data harmonization
  
## Education
- Ph.D., Statistics | University of Toronto (_Expected in 2025_)             		
- M.S., Applied Statistics | University of Michigan (_January 2021_)	 			        		
- B.E., Economic Statistics | Renmin University of China (_June 2019_)

## Research Experience
### Mitigating Inter-Scanner Biases in High-Dimensional Neuroimaging Data
- Developed the Spatial Autocorrelation Normalization (SAN) technique, a method to ensure that neuroimaging data remains consistent across different study sites and 
  MRI scanners by mitigating unwanted technical variations at the vertex level (high dimensions).
- Conducted both real data analysis and simulation studies, comparing our new method with existing methods. Our approach demonstrated substantial improvements in 
  reducing unwanted variations in covariances, enhancing data quality and reproducibility. 
- This work marked a pioneering effort in methodological research, introducing spatial modelling to tackle inter-scanner biases and ultimately providing more 
  reliable data for downstream analyses.

### A Structured Multivariate Approach for Removing Latent Inter-Scanner Effects
[Publication](https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00011/116599/RELIEF-A-structured-multivariate-approach-for)
- Developed a multivariate approach called RELIEF (REmoval of Latent Inter-scanner Effects through Factorization) for correcting unwanted scanner-related artifacts to improve the quality of brain imaging studies that involve multiple scanners or sites.
- Introduced this groundbreaking method that simultaneously reduces dimensions and factors interlinked matrices in the context of data harmonization. It provides a new direction in methodological research for correcting inter-scanner biases while preserving biological associations of interest, thereby significantly increasing statistical power compared to existing methods.
- Developed an efficient [R package (RELIEF)](https://github.com/junjypark/RELIEF/tree/master) and built a GitHub repository for sharing simulated examples and codes publicly.

### Scalar on Image Deep Neural Network
- Proposed an innovative regulaized Neural Network model tailored for solving Scalar on Image problems. This model incorporates Total Variation penalties and L-1 penalties to effectively recover sparsity spatial patterns in nonlinear systems.
- Developed a scalable algorithm for efficiently estimating the model's parameters. Additionally, I established a generalized framework, enabling prediction and variable selection across a wide range of data types, including continuous, binary, and multi-categorical variables.
- Conducted both practical applications and simulation studies to compare against existing approaches (Elastic Net, Fused Lasso, etc.), demonstrating higher prediction accuracy and comparable specificity and sensitivity in variable selection.

### fMRI Data Reconstruction, Visualization and Predictive Analytics
[Publication](https://link.springer.com/article/10.1007/s00521-021-06789-8)
- Registered fMRI 3D volume to brain Atlas to segment the fMRI anatomy into distinct regions.
- Identified active ROI candidates by using Temporal Contrast-to-noise Ratio (tCNR) for t-tests, applied tensor regression to detect activated brain areas within these candidates, and used post hoc statistical mapping filtering to localize the task-activated regions.
- Co-developed an efficient [R package (TCIU)](https://github.com/SOCR/TCIU) and built a GitHub repository for sharing simulated examples and codes publicly.

## Work Experience
**Teaching Assistant @ University of Toronto (_September 2021 - Current_)**
- STA257 Probability and Statistics I
- STA305 Design and Analysis of Experiments
- STA447 Stochastic Processes
- STA437 Methods for Multivariate Data

**Data Analyst Intern @ Bayer Healthcare Co. Ltd. (_August 2018 - January 2019_)**
- Established a sales forecasting ARIMA model based on 4-year monthly data to predict the sales amount of a selected drug in the following year, and optimized the model based on the AIC.
- Distributed sales quota to each sales representative by simulations based on historical sales, market potential and sales forecast data.

## Awards & Honors
- Student Paper Award (runner-up) in the 2022 Statistical Methods in Imaging (SMI) conference
- Data Sciences Institute Doctoral Student Fellowship in 2023 (CAD $25,000 per year up to 3 years)

## Presentations 
_Talks_

2023 Joint Statistical Meetings (JSM) 

2022 Statistical Methods in Imaging (SMI) conference

_Poster_

2023 Statistical Methods in Imaging (SMI) conference

2023 Eastern North American Region (ENAR) meeting

## Skills
- Languages: R, Python, STAN
- Training Framework: TensorFlow, Keras, Scikit-Learn
- Frameworks: Pandas, Numpy, Scipy
- Tools: Linux, git, ggplot2

## Publications
1. **Zhang, R.**, Oliver, L. D., Voineskos, A. N., & Park, J. Y. (2023). RELIEF: A structured multivariate approach for removal of latent inter-scanner effects. Imaging Neuroscience 2023; 1 1–16. doi: https://doi.org/10.1162/imag_a_00011
2. **Zhang, R.**, Zhang, Y., Liu, Y., Guo, Y., Shen, Y., Deng, D., ... & Dinov, I. D. (2022). Kimesurface Representation and Tensor Linear Modeling of Longitudinal Data, Neural Computing and Applications Journal, DOI: 10.1007/s00521-021-06789-8



