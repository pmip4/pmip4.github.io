## Welcome to the PMIP4 code repository

This organisation collects together the various pieces of code that have been contributed and deal with PMIP4 simulations in analyses. It is a place to enable scripts to be shared and found with fellow researchers. 

The codes here range from a single python script creating a single figure to large analysis packages that are aimed to be run on many different simulations at once. One or two of them may even come as Docker images that allow analyses to be performed within a platform-agnostic container. 

If you would like to volunteer your own piece of code, please contact Chris to be added to this organisation. 

The repos currently stored here are:

1. **[PMIP_for_AR6_Interactive_Atlas](https://github.com/pmip4/PMIP_for_AR6_Interactive_Atlas)** contains the files created for potential inclusion on the interactive atlas. This consists of monthly climatologies of all changes from the piControl for PMIP3 and PMIP4 simulations on the ESGF, as well as annual averages. All files are regridded onto a 1x1 degree grid through bilinear interpolation. Additionally this repository includes data and scripts to recreate a pair of figures. (Chris Brierley & Anni Zhao)
2. **[PMIP_resolution_improvements](https://github.com/pmip4/PMIP_resolution_improvements)** creates a plot showing the changes in resolution over all 4 generations of PMIP (Chris Brierley)
3. **[UCL_curated_ESGF_replica](https://github.com/pmip4/UCL_curated_ESGF_replica)** list the contents of UCL's replica of the PMIP simulations from the ESGF. This only includes monthly files of tas,ts,pr,psl as well as fields of sea ice and AMOC. Calendar adjusted versions of the files are also listed (Chris Brierley)
4. **[CVDP-ncl](https://github.com/pmip4/CVDP-ncl)** is the version of NCAR's Climate Variability Diagnostics Package that has been modified for palaeoclimate use
5. **[pmip_p2fvar_analyzer](https://github.com/pmip4/pmip_p2fvar_analyzer)** is the summary repository containing data, scripts and an interactive Docker image of Zhao et al (2021). 
