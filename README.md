# **Polymer Tg Prediction Using Isolation Forest and HybridGIN**

This project was developed as part of a personal initiative during my time at university, focused on applying **advanced machine learning techniques** to the prediction of **polymer properties**. The goal is to predict the **glass transition temperature (Tg)** of polymers by combining two main ideas:

- **Isolation Forest**: used to find and remove **outliers** from the dataset, so the model trains on cleaner, more reliable data.
- **Hybrid Graph Isomorphism Network (HybridGIN)**: a model that mixes **graph-based node features** with **molecular descriptors** to learn better.

By blending information from the polymer’s structure (graphs) and chemical descriptors (numbers), the model can make more accurate and reliable **Tg predictions**, achieving a validation **R² score** of around **0.90**.
