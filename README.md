# Radiogenomic Integration of Brain Tumor MRI Phenotypes and Transcriptomic Dysregulation

## Overview

This project presents a multimodal radiogenomic framework integrating deep learning-based MRI analysis with transcriptomic and pathway-level genomic profiling for biologically interpretable characterization of brain tumors.

The study combines:
- convolutional neural network (CNN)-based MRI classification,
- Grad-CAM explainability,
- radiomic heterogeneity analysis,
- differential gene expression analysis,
- pathway enrichment profiling,
- and radiogenomic integration.

The primary objective of the project is to investigate whether MRI-visible tumor phenotypes may reflect underlying molecular dysregulation associated with glioma progression and tumor heterogeneity.

---

# Radiogenomic Summary Framework

<p align="center">
  <img src="C:\Users\Somshir saha\Downloads\image.png" width="100%">
</p>

---

# Project Objectives

- Develop a deep learning framework for brain tumor MRI classification.
- Improve model interpretability using Grad-CAM activation mapping.
- Explore radiomic heterogeneity across tumor phenotypes.
- Identify significant transcriptomic alterations associated with brain tumors.
- Perform biological pathway and disease enrichment analysis.
- Integrate imaging and molecular findings into a radiogenomic interpretation framework.
- Investigate biologically plausible associations between MRI features and transcriptomic dysregulation.

---

# Imaging Pipeline

## MRI-Based Brain Tumor Classification

A convolutional neural network was developed to classify MRI images into:
- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

The imaging workflow included:
- MRI preprocessing and resizing,
- deep learning model training,
- performance evaluation,
- and explainability analysis.

---

## Grad-CAM Explainability Analysis

Grad-CAM activation overlays were generated to identify image regions contributing most strongly to model predictions.

This enabled:
- visual interpretability,
- localization of tumor-associated activation regions,
- and biological inspection of CNN decision-making behavior.

---

## Radiomic Heterogeneity Analysis

Radiomic-style imaging feature analysis was performed using:
- contrast,
- homogeneity,
- energy,
- and correlation metrics.

This analysis revealed:
- structural heterogeneity,
- intensity variability,
- and phenotype differences across tumor categories.

---

# Genomic / Transcriptomic Pipeline

## Differential Gene Expression Analysis

Transcriptomic expression datasets were analyzed to identify significantly dysregulated genes associated with brain tumors.

The workflow included:
- preprocessing,
- missing value handling,
- DEG filtering,
- and statistical analysis.

Both upregulated and downregulated genes were identified using:
- log2 fold change,
- p-values,
- and adjusted p-values.

---

## Principal Component Analysis (PCA)

PCA was used to visualize transcriptomic separation between:
- tumor,
- and non-tumor samples.

The PCA analysis demonstrated biologically distinct molecular clustering patterns.

---

# Functional Enrichment Analysis

## Why Enrichr Was Used

Enrichr was used for downstream biological interpretation of significant differentially expressed genes.

Functional enrichment analysis was performed using:
- GO Biological Process,
- Reactome Pathways,
- KEGG Pathways,
- and Disease Enrichment libraries.

---

## Major Biological Findings

The enrichment analysis identified strong associations with:
- glioma progression,
- extracellular matrix (ECM) remodeling,
- synaptic signaling dysregulation,
- neuronal communication pathways,
- invasive tumor behavior,
- and proliferative molecular mechanisms.

---

# Radiogenomic Integration Framework

The imaging and transcriptomic findings were integrated into a radiogenomic interpretation framework.

The integration investigated biologically plausible relationships between:
- MRI-visible tumor phenotypes,
- radiomic heterogeneity,
- and transcriptomic dysregulation.

A radiogenomic association heatmap was constructed to explore potential links between:
- activation hotspot regions,
- structural heterogeneity,
- diffuse tumor boundaries,
- texture variability,
and:
- cell-cycle activation,
- ECM remodeling,
- synaptic signaling,
- tumor invasion,
- and neuronal dysregulation.

---

# Final Interpretation

The integrated analysis suggests that:
- MRI-derived tumor phenotypes may encode biologically meaningful molecular information,
- imaging heterogeneity may reflect underlying transcriptomic alterations,
- and multimodal radiogenomic analysis may support biologically interpretable AI-assisted characterization of brain tumors.

The framework demonstrates how:
- deep learning,
- radiomics,
- transcriptomics,
- and systems biology

can be integrated for future precision oncology research.

---

# Technologies and Libraries Used

## Deep Learning and Imaging
- TensorFlow
- Keras
- OpenCV
- Grad-CAM
- Matplotlib
- Seaborn

## Transcriptomics and Bioinformatics
- Pandas
- NumPy
- SciPy
- Scikit-learn
- Enrichr
- PCA
- Differential Expression Analysis

---

# Key Outputs

- CNN-based MRI tumor classification model
- Grad-CAM activation overlays
- Confusion matrix analysis
- Radiomic heterogeneity analysis
- Differential gene expression profiling
- Volcano plot visualization
- PCA transcriptomic clustering
- GO, Reactome, KEGG, and Disease enrichment analysis
- Radiogenomic association heatmap
- Integrated radiogenomic systems-level framework

---

# Limitations

- MRI and transcriptomic datasets were analyzed independently and were not paired at the patient level.
- The radiogenomic associations presented are biologically informed interpretative relationships rather than experimentally validated causal links.
- Further validation using matched multimodal patient cohorts is required.

---

# Future Scope

Future extensions of this work may include:
- multimodal deep learning,
- patient-level radiogenomic correlation,
- survival prediction,
- molecular subtype prediction,
- explainable AI-assisted clinical decision systems,
- and precision oncology applications.

---

# Conclusion

This project demonstrates a biologically interpretable radiogenomic framework integrating MRI-based deep learning and transcriptomic pathway analysis for brain tumor characterization.

The study highlights the potential of multimodal AI and systems biology approaches for understanding glioma-associated molecular mechanisms and advancing precision neuro-oncology research.
