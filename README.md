# Master-Thesis-AI
Master Thesis AI: Recognition immune communities

Understanding interactions and relationships among immune cell populations is
critical to increase the effectiveness of cancer treatments. Advancements in cell
sequencing and spatial technologies to spot-level resolution have improved our ability
to visualise the variability and evolution of tumour heterogeneity. Obtaining spatial
data allows for more personalised immunotherapies and better patient prognosis.
However, the high cost of these techniques limits their immediate application in
clinical cancer classification analysis. The deployment of artificial intelligence (AI) in
analysing microbiological tissues and detecting specific cancer tumours from pathology
images is expanding rapidly and could offer a viable alternative or complement.
This work investigates how AI can be used to better understand relationships among
cell populations directly from H&E staining, bypassing the need for expensive spatial
data technologies. Several convolutional neural networks (CNNs) based on ShuffleNet
are defined to infer gene signature expressions and tumour cluster classifications from
H&E patches, and to correlate these findings to patient level for survival prognosis
analysis. Defined prototype models could complement clinicians in their analysis on
tumour heterogeneity. The case is developed for glioblastoma, a malignant brain
cancer. The scope includes spatial data from 59 H&E glioblastoma slides of 51
patients and 12.591 patient slides from approximately 600 patients. The datasets
comprise 164.488 spot observations and 31.908 variables. Models are trained using
12.500 patches to predict a total of 74 gene signatures and 39 tumour clusters.
Results show good predictions of morphology. R2 values for gene signature expressions
are reported above 95%, with the best performers above 99% after training to 300
epochs. Examples include: IFNg, Expanded immune, T cell inflamed, Zheng Non
Exhausted Non reactive and Reactive CD4 T cells, Oliveira CD8 T Activated. Tumour
cluster regions are predicted with ROC values over 90% on trained prototypes up
to 50 epochs. Predictions are aggregated to patient level and linked to survival
prognosis in a proof of concept. Models are low-capacity demanding, are easy to
exchange, and can be installed on laptops in a clinical lab setting.
To advance this work beyond research, models need to be upscaled and retrained
with a larger volume and greater variability in patches. Pathology experts need to
compare AI predictions with spatial data for new patient cases. This study confirms
the potential to predict signature expressions and tumour zones directly from H&E.
