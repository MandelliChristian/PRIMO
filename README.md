# PRIMO SVM MODEL
Efficient selection of siRNA sequences for systemic silencing of target genes or transcripts is crucial for the development of efficacious RNAi-based products. However, this process is still a major challenge, and the development of effective in silico tools to predict siRNA species with high silencing efficiency and systemic potential is a significant priority. Recent studies have shown that the target accessibility and siRNA 5’ composition are essential criteria to evaluate the silencing property of an siRNA sequence.
One approach to predicting siRNA efficacy is to use Support Vector Machines (SVMs), which can be trained and tested over an experimentally validated sequence dataset. In addition to commonly used features such as di- and tri-nucleotide counts, GC content, duplex flexibility, and thermodynamics stability, the target accessibility and siRNA 5’ composition are also critical factors in the SVM pipeline.
To improve the prediction accuracy, a hybrid-SVM-based approach has been previously developed, combining efficacy scores from previous models and training datasets of siRNAs that have demonstrated efficacious systemic silencing. This approach has demonstrated a high correlation coefficient between predicted and measured efficacy, making it a promising tool for identifying effective siRNA sequences.

PRIMO is a SVM model that aims to increase the accuracy of siRNA efficacy prediction based on a dsRNA precursor sequence.
