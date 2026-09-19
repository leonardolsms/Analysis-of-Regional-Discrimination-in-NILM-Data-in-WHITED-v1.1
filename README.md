# Analysis of Regional Discrimination in NILM Data: Impact of Acquisition Kit and Load Composition in WHITED v1.1
A reproducible audit of the structure of the WHITED v1.1 dataset used in the study; a joint analysis based
on Principal Component Analysis (PCA), the Silhouette coefficient, and nonparametric statistical tests; a
supervised evaluation using appliance-grouped cross-validation; an explicit analysis of the relationship between region and acquisition kit; and a discussion of the distinction between predictive discrimination and the existence of an independent geographical electrical signature 
## Abstract 
Non Intrusive Load Monitoring (NILM) relies on features that represent differences among appliances, but datasets collected in different places may also differ in acquisition hardware and appliance composition. This study investigates regional discrimination in WHITED v1.1 while explicitly assessing the influence of the acquisition kit. After auditing the package
and removing duplicated files, 1,339 observations of 134 appliances, from nine regions and two acquisition
kits, were analyzed using 12 waveform features. Principal Component Analysis (PCA) concentrated 62.27% of
the variance in two components, yet the regional Silhouette coefficient was −0.0681, against 0.2458 for the ac-
quisition kit. With appliance-grouped cross-validation, a Random Forest reached an accuracy of 0.7048 (balanced accuracy 0.7384) using the features alone and 0.7564 (0.7914) when the kit was added. Regional classification remained possible within a single kit
(accuracy 0.8076 for MK1 and 0.7852 for MK2) and in the three regions shared by both kits (0.8135, or 0.8163
with the kit), where the kit added almost nothing. Eight of the twelve features differed significantly among
regions after FDR correction. However, six of the nine regions were recorded with a single kit, and 65.6% of
the MK1 observations belong to appliance types found in only one region. The results reveal region-associated
discriminative information, but do not support interpreting it as an independent geographic electrical signature.


Keywords: NILM; WHITED; machine learning; Random Forest; PCA; Silhouette coefficient; domain heterogeneity.
