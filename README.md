Algorithmic Role Switching and Identity Fluidity in Multi-Project Electronics Supply Chain Teams
This repository contains the deep learning framework and data processing pipeline for analyzing team dynamics in high-velocity electronics manufacturing environments. The project investigates how data-driven role transitions ("Algorithmic Role Switching") and individual adaptability ("Identity Fluidity") impact organizational coordination costs.

📌 Project Overview
In modern electronics supply chains, teams manage multiple concurrent projects with overlapping resource requirements. This study utilizes Deep Embedded Clustering (DEC) and Variational Autoencoders (VAE) to quantify the trade-offs between workforce flexibility and operational efficiency.

Research Questions
RQ1: How frequent and varied is algorithmic role switching across supply chain functions?

RQ2: Does professional identity fluidity significantly improve a team’s capacity for adaptation?

RQ3: What are the quantifiable coordination costs associated with high-frequency role transitions?

📊 Dataset Architecture
The study integrates five heterogeneous datasets to provide a holistic view of the supply chain ecosystem:


DataCo Smart Supply Chain (Primary): 180,000 rows of transactional data (2015–2018) for mapping role interactions in procurement, production, and sales.


SupplyGraph (Structural): A benchmark FMCG dataset used for graph neural network applications to model production facility assignments and shared resource dependencies.


GitHub Collaboration (Behavioral): Captured developer interactions and explicit role indicators (contributor, reviewer, maintainer) to benchmark agile team dynamics.


Electronics Manufacturing MES (Operational): Real-time workstation assignments, cycle times, and quality inspection results from 2018–2023.


IBM HR Analytics (Validation): Organizational context linking career progression (e.g., "Years in Current Role") to identity fluidity.

🛠 Methodology
The project employs a two-stage deep learning pipeline:


Role Typology Discovery: Using DEC to cluster team members into categories like "Stable Specialists," "Adaptive Generalists," and "Rapid Switchers".


Identity Fluidity Index (IFI): A novel metric derived from the latent space variance of a VAE, quantifying the degree of professional adaptability.


Coordination Cost Modeling: Polynomial regression analysis using lead times and processing variances as proxies for organizational friction.

🚀 Getting Started
Prerequisites
Python 3.8+

PyTorch

Scikit-learn

Pandas / NumPy

Matplotlib / Seaborn

Installation
Running the Analysis
The main implementation is contained within the Role_Switching_Analysis.ipynb Jupyter Notebook. It includes:

Data simulation and integration of multi-project indicators.

VAE training for latent identity mapping.

Visualization of Research Questions (RQ1–RQ3).

📈 Key Results
Optimal Fluidity: Findings identify an IFI of 0.85 as the "sweet spot" for maximizing adaptability while minimizing costs.

Switching Hubs: Procurement and logistics are identified as the roles with the highest transition centrality.

Cost Thresholds: Coordination costs increase exponentially once the Identity Fluidity Index exceeds 1.10.

⚖️ License
This project is licensed under the MIT License.

🎓 Citation
If you use this framework or datasets in your research, please cite the documentation:

Jha, G. K. (2026). Algorithmic Role Switching and Identity Fluidity in Multi-Project Electronics Supply Chain Teams. Dataset Documentation Project.
