# Projects

Please submit a PR to [this repo](https://github.com/brainhack-boston/brainhack-boston.github.io) or email `brainhackboston@gmail.com` to add a project or to add your name as an interested party to an existing project.

## Realtime visualization/analysis of BOLD data

Realtime fmri paradigms require a mechanism to stream BOLD data from the MR scanner to an external computer.  Given such a mechanism, what else is possible?  What other monitoring, visualization, or realtime paradigm can this mechanism enable?

### Resources
- [murfi2](https://github.com/gablab/murfi2)

### Interested parties
- Paul Wighton

---

## FreeSurfer and the Common Workflow Language

The Common Workflow Language (CWL) is a specification for describing analysis workflows and tools in a way that makes them portable and scalable across a variety of software and hardware environments.  This project aims to specify FreeSurfer's recon-all stream in the common workflow language.  What is the best way to go about this and what does this enable?

### Resources
- [FreeSurfer](https://github.com/freesurfer/freesurfer)
- [Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)
- [CWL for FreeSurfer](https://github.com/corticometrics/fs-cwl)

### Interested parties
- Paul Wighton

---

## Nipype

Nipype is a Python project that provides a uniform interface to existing neuroimaging software and facilitates interaction between these packages within a single workflow.

### Resources
- [Github](https://github.com/nipy/nipype)
- [Interactive tutorial](https://miykael.github.io/nipype_tutorial/)
- [Issues](https://github.com/nipy/nipype/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Agood-first-issue)

---
## TRACULA and Freesurfer cortical thickness

TRACULA provides probabily maps of main white matter (WM)  structures allowing for statistical analysis of miscrostructural information such as fractional anisotropy (FA) and mean/radial/axial diffusivity (MD/RD/AD). Changes in grey matter (GM) cortical thickness might have an impact on the connecting white matter and vice-versa. Integrating TRACULA with FreeSurfer cortical thickness analysis extend the WM/GM analysis.

### Resources
- [TRACULA](https://surfer.nmr.mgh.harvard.edu/fswiki/Tracula)
- [FreeSurfer](https://github.com/freesurfer/freesurfer)

### Interested parties
- Viviana Siless
- Jonathan Wang

---
## Group short connection streamlines based on cortical structures

Most of the streamline white matter (WM) clustering methods focus on long range connection streamlines and little attention has been payed to short connection streamlines. Short connection streamlines can be correlated with cortical thickness changes. The goal is to compare the effect of grouping short connection streamlines based on cortical regions they connect, and compare it to grouping them based on a spatial distance.

### Resources
- [AnatomiCuts](https://www.ncbi.nlm.nih.gov/pubmed/29100937)
- [FreeSurfer](https://github.com/freesurfer/freesurfer)

### Interested parties
- Viviana Siless
- Hui Wang

---
## Streamline visualization

Visualizing million of 3D curves inside the brain can be hard. The main goal of this project is to explore alternatives for visualizing white matter connections, such as short connections on the flat surface.

### Resources
- [FreeSurfer](https://github.com/freesurfer/freesurfer)

### Interested parties
- Viviana Siless

---
## RegTest

We created a robustness testing framework to analyze performance of specific analyses in varied computational environments. To build tests, information about three components are specified using a JSON file: requested computational environments; scripts to run the analysis; and tests to compare workflow output to a reference output. Neurdocker creates Docker test environments, and the Common Workflow Language (CWL) is used to run all steps. The comparison step uses existing or user provided tests. The framework currently uses GitHub and CircleCI for integration and visualizing comparisons.

I want to work mostly on the visualization part that uses JavaScript and D3 and scattering options with CWL.

### Resources
- [RegTest](https://github.com/ReproNim/regtests)
- [CWL](https://www.commonwl.org/)

### Interested parties
- Dorota Jarecka
- Paul Wighton

---
## Hacking the scientists brains

Any idea how to convince more scientist to join the Brainhack Global next year?? Anything else would you like to hack in the scientists brains?? Share your ideas. 
It can be used as a GitHub exercise ;-)

### Resources
- [Hacking the scientists brains](https://github.com/djarecka/hacking_the_scientists_brains)

### Interested parties
- Dorota Jarecka
- Paul Wighton

---
## DICOM outputs for FreeSurfer

dcmqi (DICOM for Quantitative Imaging) is a library that implements conversion between commonly used imaging research formats and the standard DICOM representation.  We have already converted FreeSurfer's subcortical segmentation (`aseg.mgz`) to DICOM-SEG.  Can we convert the statistics to DICOM-SR?

### Resources
- [fs2dicom](https://github.com/corticometrics/fs2dicom)
- [dcmqi](https://github.com/djarecka/hacking_the_scientists_brains)
- [FreeSurfer](https://github.com/freesurfer/freesurfer)

### Interested parties
- Paul Wighton




