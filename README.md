# Stroke Outcome Optimization Project (SOOP)

## Overview

This dataset includes anonymized images, behavioral measures and demographic details from a cohort of individuals from South Carolina with acute stroke. The fully BIDS-compatible dataset is fully anonymized, allowing public sharing which is vital for education and development of BIDS pipelines that are capable of processing clinical datasets. Along with its companion chronic [Aphasia Recovery Cohort (ARC)](https://openneuro.org/datasets/ds004512/), these features complement existing repositories of [acute](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10444746/ and [chronic](https://pubmed.ncbi.nlm.nih.gov/32310331/) stroke.

## Data Contents
* `participants.tsv` - List of subject IDs, demographic variables, and impairment measures. Note that many variables are [generalized](https://www.hhs.gov/hipaa/for-professionals/privacy/special-topics/de-identification/index.html#approachmitigate) to meet [International Safe Harbor Privacy Principles](https://en.wikipedia.org/wiki/International_Safe_Harbor_Privacy_Principles).


* `Subject Directories` - MRI data directories for each subject. Note that sequence protocols and diffusion derivative formula vary between individuals. See the individual BIDS JSON sidecars included with each image for specific details.
  - `anat` - T1w and T2w-FLAIR anatomical images
  - `dwi` - Diffusion weighted Trace and  apparent diffusion coefficient (ADC) images
