# Welcome to LivingPark!

LivingPark is a project to improve the generalizability and robustness of MRI-derived biomarkers of Parkinson's Disease through analytical and data variability evaluations.
It started in March 2022 and is currently funded by the [Michael J Fox Foundation](https://www.michaeljfox.org). The first objective of the project is to 
replicate the following MRI measures of Parkinson's Disease and make them available as [Jupyter Notebooks](https://jupyter.org).

We'd love to hear from you! Feel free to reach out by posting an issue in any of our repos, or by email at [livingpark@lists.concordia.ca](mailto:livingpark@lists.concordia.ca)

The following table points to the on-going replication efforts.

| Replication outcome | Reference | Person in charge | Notebook repo | Limitations | External review | Authors feedback | Extension to QPN |
|:--------------------|:----------|:----------------:|:--------------|:------------|:----------------|:-----------------|:-----------------|
| 🟥 | C. Scherfler et al., “White and gray matter abnormalities in idiopathic rapid eye movement sleep behavior disorder: a diffusion-tensor imaging and voxel-based morphometry study,” Annals of neurology, vol. 69, no. 2, pp. 400–407, 2011. | @glatard | https://github.com/LivingPark-MRI/scherfler-etal | Discrepancies in RBD diagnosis (being addressed) | | | |
| 🏃 | S. Rahayel et al., “Cortical and subcortical gray matter bases of cognitive deficits in REM sleep behavior disorder,” Neurology, vol. 90, no. 20, pp. e1759–e1770, 2018. | @niyonx | https://github.com/LivingPark-MRI/rahayel-etal | | | | |
| 🟥 | Y. Zeighami et al., “Network structure of brain atrophy in de novo Parkinson’s disease,” elife, vol. 4, p. e08440, 2015. | Niusha | https://github.com/LivingPark-MRI/zeighami-etal-2015| No major limitation identified  || On-going ||
| 🟥 | Y. Zeighami, S.-M. Fereshtehnejad, M. Dadar, D. L. Collins, R. B. Postuma, and A. Dagher, “Assessment of a prognostic MRI biomarker in early de novo Parkinson’s disease,” NeuroImage: Clinical, vol. 24, p. 101986, 2019. | @michellewang | [https://github.com/LivingPark-MRI/zeighami-etal-2019](https://github.com/LivingPark-MRI/zeighami-etal-2019)| No major limitation identified | | On-going | |
| 🟥 | E. Mak et al., “Baseline and longitudinal grey matter changes in newly diagnosed Parkinson’s disease: ICICLE-PD study,” Brain, vol. 138, no. 10, pp. 2974–2986, 2015. | @chelsieng / @ansokolowski | https://github.com/LivingPark-MRI/mak-etal-2015  | Sample size | | | | |
| 🏃 | C. Tessa et al., “Progression of brain atrophy in the early stages of Parkinson’s disease: A longitudinal tensor-based morphometry study in de novo patients without cognitive impairment,” Human brain mapping, vol. 35, no. 8, pp. 3932–3944, 2014. | Jacob | https://github.com/LivingPark-MRI/tessa-etal-2014 | | | | |
| 🏃 | E. Mak et al., “Longitudinal whole-brain atrophy and ventricular enlargement in nondemented Parkinson’s disease,” Neurobiology of aging, vol. 55, pp. 78–90, 2017. | @mathdugre | https://github.com/LivingPark-MRI/mak-etal | | | | |
| 🏃 | F. Agosta et al., “The topography of brain damage at different stages of Parkinson’s disease,” Human brain mapping, vol. 34, no. 11, pp. 2798–2807, 2013. | @glatard | https://github.com/LivingPark-MRI/agosta-etal | | | | |
| 🟥 | Z. Shu et al., “Predicting the progression of Parkinson's disease using conventional MRI and machine learning: An application of radiomic biomarkers in whole-brain white matter,” Magnetic Resonance in Medicine 85.3 (2021): 1611-1624. | @mohanadarafe | https://github.com/LivingPark-MRI/shu-etal | No major limitation identified | | | |
| 🏃 | N. W. Sterling et al., “Stage-dependent loss of cortical gyrification as Parkinson disease ‘unfolds,’” Neurology, vol. 86, no. 12, pp. 1143–1151, 2016. | @rmanaem | https://github.com/LivingPark-MRI/sterling-etal-2016 | | | | |
| 🟧 | A. Hanganu et al., “Mild cognitive impairment is linked with faster rate of cortical thinning in patients with Parkinson’s disease longitudinally,” Brain, vol. 137, no. 4, pp. 1120–1129, 2014. | @ansokolowski | https://github.com/LivingPark-MRI/hanganu-etal-2014 | Sample size | | On-going | |

🟥 could not replicate the original result 🟧 partially replicated the original result 🏃 work in progress

To facilitate the development of these notebooks we develop [livingpark-utils](https://github.com/LivingPark-MRI/livingpark-utils), a collection of functions to help work with PPMI data. We also develop [ppmi-scraper](https://github.com/LivingPark-MRI/ppmi-scraper), a set of utilities to download PPMI study and imaging data. 

