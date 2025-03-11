# Mara’s GitHub Repositories

structuring GitHub repositories: [projthis](https://ijlyttle.github.io/projthis/articles/projthis.html) (R), cookiecutter 

## **asteRIa**

📝 **Manuscript:** *asteRIa enables robust interaction modeling between chromatin modifications and epigenetic readers*

🤝 **Collaborators:** Till Bartke, Saulius Lukauskas

🔹 Useful for hierarchical interaction modeling when **only a few, inconsistent replicates** are available. Integrates hierarchical interaction modeling with stability selection and replicate consistency checks, focusing on **binary input data**.

🔹 Provides a template for a semi-synthetic simulation setup in regression with a multiple response matrix Y.

📊 **Data:** MARCS 

https://github.com/bio-datascience/asteRIa

---

## **Microbial-Interactions**

📝 **Manuscript:** *Predictive modeling of microbial data with interaction effects*

🤝 **Collaborator:** Jacob Bien

🔹 Enables context-dependent interaction modeling for microbial data (absolute, binary, or **compositional**).

🔹 Includes all-pairs lasso/hierarchical lasso, cross-validation, and stability selection.

🔹 Provides a template for a semi-synthetic simulation setup for compositional data in regression.

📊 **Data:** Tara Oceans, MetaCardis, Clark et al. butyrate production data

https://github.com/bio-datascience/Microbial-Interactions

---

## **Drug-interactions-HCS**

🤝 **Collaborators:** Erwin Kupczyk & Research Unit Analytical Biogeochemistry (Helmholtz Munich)

🔹 Extends hierNet with a **robust Huber loss function** for hierarchical interaction modeling when multiple replicates are available, accounting for potential outliers.

📊 **Data:** High-content screening data

 https://github.com/bio-datascience/Drug-interactions-HCS

---

## **LassoNetR**

🤝 **Collaborators:** Fabian Schaipp, Daniele Pugno

🔹 R interface for LassoNet using reticulate, with comparisons to hierNet.

 https://github.com/bio-datascience/LassoNetR

💻 **Example usage:**

```
LassoNetR(X = X, Y = y, NN = py$torch_hiernet,
          D_in = D_in, D_out = D_out, H = H,
          batch_size=batch_size, lam = 5L, M = 1L,
          n_epochs = 30L, valid = TRUE, optimizer = "SGD")
```

---

## **drug_interactions_bacterial_growth**

🤝 **Collaborator:** Medina Feldl

🔹 Uses AUCs from bacterial growth data to identify drug interaction effects.

🔹 Early-stage project; comparison asteRIa with Bliss independence analysis and the Dose model (Zimmer et al.) needed.

🔹 Likely to be continued by a Master's student.

📊 **Data:** Ana Rita Brochado lab

https://github.com/bio-datascience/drug_interactions_bacterial_growth

---

## **Presence-absence-guided-compositional-modeling**

🤝 **Collaborator:** Jacob Bien

🔹 Investigates whether relative abundances in 16S data provide more information than pure presence-absence data.

🔹 Introduces a joint optimization approach (λ1, λ2) for relative and presence-absence data.

📊 **Data:** American Gut Project, Central Park Soil 

https://github.com/bio-datascience/Presence-absence-guided-compositional-modeling

---

## **randILR**

🔹 Implements simulations of (random) Generalized Helmert-Ledermann orthogonal matrices (GHL) for generating random ILR transformations.

🔹 Potentially useful for data augmentation in compositional microbiome data.

 https://github.com/bio-datascience/randILR

---

## **tensor-fact-covid**

🤝 **Collaborator:** Göran Kauermann

🔹 Non-negative tensor factorization applied to COVID-19 data, includes code for (spatial) visualizations.

📊 **Data:** COVID-19 data (RKI) 

https://github.com/bio-datascience/tensor-fact-covid

---

## **OMM12-interaction-modeling**

🤝 **Collaborator:** Anna Weiss

🔹 Uses synthetic gut community data for interaction modeling.

🔹 Final results available in branches by Oktawia Miluch and Jakob Winkler.

📊 **Data:** OMM12 synthetic microbial community

https://github.com/bio-datascience/OMM12-interaction-modeling

---

## **host_microbiome**

📝 **Paper:** *RNF43 is a gatekeeper for colitis-associated cancer*

🤝 **Collaborators:** Alisa Dietl, Roberto Olayo

🔹 Analyzes microbiome (16S), RNA-seq, histological, and clinical data from a mouse study on CRC and IBD.

🔹 Methods include DA testing, DE analysis, MDS, mixedCCA, log-contrast regression, and latent correlation.

📊 **Data:** RNF43 data 

https://github.com/bio-datascience/host_microbiome

---

## **Seminar_linDA_RNF43**

🤝 **Collaborator:** Alisa Dietl

🔹 R code by Oktawia Miluch applying linDA to RNF43 data, compared against ANCOM-BC and ALDEx2.

📊 **Data:** RNF43 data

https://github.com/bio-datascience/Seminar_linDA_RNF43

---

## **prototype_clustering**

🔹 Performs prototype clustering on MARCS data with visualization features.

🔹 Used for the figure in the Nature paper. 

https://github.com/bio-datascience/prototype_clustering

---

## MScThesis_Maria

🔹 Code by Maria Pröbstl on *Estimation of higher-order species interactions from ecological time series*.

🔹 Methods: compositional Lotka-Volterra Model; DeepMoD, a deep learning framework tailored for the extraction of partial or ordinary differential equations; NODE-BNGM, a nonparametric technique that fits neural ordinary differential equations (NODEs) with Bayesian neural gradient matching to detect ecological interactions from time series observations.

🔹 Collection of ecological times series data

📊 **Data:** Karwowska et al., Silverman’s Artificial Gut, Bucci’s C. Diff., Four BioTIME Studies, Synthetic data: miaSim, Tri-Trophic Lotka-Volterra
ODE System, Van der Pol Oscillator 

https://github.com/bio-datascience/MScThesis_Maria

---
