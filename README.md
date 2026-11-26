# Diabetes and gallstones

[Open the analysis in Google Colab](https://colab.research.google.com/github/Noraaa777/diabetes-gallstones-colab/blob/main/Diabetes_and_gallstones.ipynb)

Choose **Runtime → Run all** in a Python runtime. The notebook downloads the public 2017–March 2020 NHANES files from CDC and installs the R package `survey` if needed. The MR section starts with 109 harmonized SNPs embedded in the notebook. Google Drive and an OpenGWAS key are unnecessary for this workflow.

The MR exposure is type 2 diabetes (GCST006867), and the outcome is FinnGen cholelithiasis (finn-b-K11_CHOLELITH). It is a reanalysis using an alternative outcome dataset. The notebook starts the MR workflow after SNP selection, clumping, matching, and harmonization.
