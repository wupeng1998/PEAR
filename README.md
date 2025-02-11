# PEAR


To enable a comprehensive comparison, we obtained published, manually curated metabolic network models from the BiGG database and retrieved the corresponding genome sequences for 79 diverse species from NCBI.

Subsequently, metabolic network models were reconstructed using CarveMe, ModelSEED, and PEAR based on these genome sequences. After reconstruction, we recorded the number of genes, reactions, and metabolites in each model and simulated the production rates of NADH, ATP, and biomass for each strain, using glucose as the sole carbon source with an uptake rate set to 10 mmol/g DCW/h.

The results demonstrate that PEAR-reconstructed models exhibit the highest consistency with manually curated (published) models across various metrics. Notably, in quantitative calculations, PEAR consistently outperforms other tools, which often generate excessively high predicted values.


![model_comparison_defaul](https://github.com/user-attachments/assets/1eb13be5-d944-4b3d-b04d-29c77d47ad97)
Figure 1. Comparison of GEMs of 79 species reconstructed using PEAR, CarveMe, and ModelSEED across bacteria, archaea, and eukaryotes. GEMs were evaluated by number of gene, reaction, and metabolite, as well as simulated NADH, ATP, and Biomass production rates.

