# A meta-analysis and systematic review of single vs. multimodal neuroimaging techniques in the classification of psychosis

Here we sought to determine whether single or multimodal neuroimaging techniques provide significant differences in predictive performance in the classification os psychosis compared to healthy controls. We conducted a bivariate meta-analysis to examine whether imaging modality (DTI, T1, FC) provides significant differences in classification of psychosis. We found minimal differences between imaging modality and performance and evidence of biased effect sizes. This work highlights the need for more studies using external datasets for prediction and use of large sample sizes. 

# Final Analysis

The main findings from this manuscript can be found here using the externally reported datasets file (external_only23.csv) and the internal results from training folds (internal_only23.csv)

# FC Motion

In addition to examining neuroimaging modalities we also sought to explore whether denoising of functional connectivity data influences classification. A rating system was created based on Ciric et al 2017 in which scores were derived based on the processing strategy used to remove motion related artifacts and distance dependent effects. We did not find a significant differences in motion processing strategy and performance, however, this result may be due to the limited range of motion denoising methods used within FC based studies. 
This analysis can be replicated using the motion23.rmd file which relies on the FC_analysis (internal data folds) and external_only_FC_analysis23 (external datasets). 

# Supplemental figures

Various supplemental material for multiple comparisons and dip tests can be found here. 


