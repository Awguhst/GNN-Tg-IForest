# **Polymer Tg Prediction Using Isolation Forest and HybridGIN**

This project was developed as part of a personal initiative during my time at university and was **presented at an undergraduate conference**. It focuses on applying **advanced machine learning techniques** to the prediction of **polymer properties**, specifically the **glass transition temperature (Tg)**.

The approach combines two main ideas:

- **Isolation Forest**: used to find and remove **outliers** from the dataset, so the model trains on cleaner, more reliable data.  
- **Hybrid Graph Isomorphism Network (HybridGIN)**: a model that mixes **graph-based node features** with **molecular descriptors** to learn better.

By integrating the polymer’s **node features** (which capture structural information) with **chemical descriptors**, the model can make more accurate and reliable **Tg predictions**, achieving a validation **R² score** of around **0.90**.
