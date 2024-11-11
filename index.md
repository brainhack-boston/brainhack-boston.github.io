
# Brainhack Boston 2024
### November 21st and 22nd, 2024 <BR> Hosted at MGB Assembly Row and virtually

### Register

If you are interested in participating in our 2024 Brainhack, please fill out [this short form.](https://forms.gle/rjnX8opcLvorguEk8)

### About
Brainhack Boston 2024 is organized in coordination with Brainhack Global 2024.

Brainhack Global is a unique conference that convenes researchers from across the globe and a myriad of disciplines to work together on innovative projects related to neuroscience.

Brainhack Boston 2024 is focused on tool development for the [BRAIN Initiative CONNECTS program](https://www.ninds.nih.gov/news-events/highlights-announcements/nih-brain-initiative-launches-projects-develop-innovative-technologies-map-brain-incredible-detail), and particularly [CONNECTS projects on multi-modal imaging of fiber tracts](https://reporter.nih.gov/search/Gv18N9u3AUeBAKNSlbkxuA/projects?sort_field=ic_serial_num&sort_order=desc). These projects aim to collect, analyze, and integrate diffusion MRI and microscopy data towards constructing a multi-scale human connectome.

**In-person location:**

MGB Assembly Row, room 3E33<BR>
[399 Revolution Dr, Somerville, MA 02145](https://maps.app.goo.gl/rBJ9CdUx3ntQdbcV9)<BR>

**Zoom link:**
[https://partners.zoom.us/j/84748902367](https://partners.zoom.us/j/84748902367)

**Mattermost channel:**
[https://mattermost.brainhack.org/brainhack/channels/bgh24-boston](https://mattermost.brainhack.org/brainhack/channels/bgh24-boston)

### Projects

**1. Assemble and document a package of converters between CONNECTS image formats**

The CONNECTS program will be generating imaging data from a variety of modalities, including diffusion MRI, optical and X-ray microscopy. Most of these images will be too large to hold in memory all at once, and thus the [OME-Zarr](https://link.springer.com/article/10.1007/s00418-023-02209-1) format, which allows storing and accessing large images in chunks, has been agreed upon as the common standard of choice for these data. However, the raw data are being generated in a variety of different formats, including .jp2, .tif, and .mat. The LINC project has a [collection of scripts](https://github.com/lincbrain/linc-convert) for converting these formats to OME-Zarr. The goal of this project is to assemble these scripts into a package and add testing and documentation.

**2. Structure tensor analysis to visualize white-matter texture from microscopy data**

The [structure tensor](https://en.wikipedia.org/wiki/Structure_tensor) contains the gradient of an image in different directions in a local neighborhood around a voxel, hence it captures the directionality of the texture of the image around the voxel. [Hierarchical phase-contrast tomography (HiP-CT)](https://mecheng.ucl.ac.uk/hip-ct/) is an X-ray technique for ex vivo imaging of intact organs, including whole human brains, with ten times the resolution of a medical CT scanner. The goal of this project is to compare different approaches to structure tensor analysis of HiP-CT images, in terms of their computational efficiency and their fidelity to the underlying white-matter architecture. We will then apply the same analysis to lightsheet microscopy (LSM) images collected from tissue sections stained with different fluorescent markers.

**3. Registration of ex vivo dMRI brain datasets to in vivo MRI templates**

Aligning ex vivo dMRI brain scans to in vivo brain templates is complicated by morphological differences (nonlinear distortions of ex vivo brains after extraction from the skull) and differences in image contrast (esp. when the target of the alignment is a T1 or T2 in vivo template). The goal of this project is to test different strategies for preprocessing the source and/or target images to improve this alignment, including automated segmentation or contrast synthesis.

### Schedule
- All times below are EST.

#### Thursday, November 21st, 2024

- 09:00 am Project pitches
- 10:00 am Hacking time

#### Friday, November 22nd, 2024

- 09:00 am Hacking time
- 03:00 pm Project updates

###  Conduct

[Brainhack is dedicated to providing a harassment-free conference experience for everyone.](https://brainhack.org/code-of-conduct.html)

### Contact

- Email:
  - Kabilar Gunalan `kabi@mit.edu`
  - Anastasia Yendiki `ayendiki@mgh.harvard.edu`

### Acknowledgements

We would like to thank our funders and institutions for supporting this event.

- NIH BRAIN CONNECTS - The center for Large-scale Imaging of Neural Circuits (LINC) (UM1 NS132358)
- NIH BRAIN CONNECTS - Center for Mesoscale Connectomics (UM1 NS132207)
- NIH BRAIN CONNECTS - Mapping connectivity of the human brainstem in a nuclear coordinate system (U01 NS132181)

### Past events
- [Spring Brainhack Boston 2024](index.2024.04.md)
- [Brainhack Boston 2023](index.2023.12.md)

