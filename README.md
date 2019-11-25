# Awesome medical imaging
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is an [awesome](https://github.com/sindresorhus/awesome) list of software that I use to do research in medical imaging.


## Kitware stuff
<img src="https://www.kitware.com/main/wp-content/uploads/2017/03/Kitware_Logo.png" alt="kitware" width="200"/>


### [ITK - Insight Segmentation and Registration Toolkit](https://itk.org/)

<img src="https://discourse.itk.org/uploads/default/original/1X/83aa25abdcbd323ce491ff99db5dfe2e59d7fd4d.png" alt="itk" width="200"/>

> ITK is an open-source, cross-platform system that provides developers with an extensive suite of software tools for image analysis.  Developed through extreme programming methodologies, ITK employs leading-edge algorithms for registering and segmenting multidimensional data.


#### [SimpleITK](http://www.simpleitk.org/)

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/SimpleITKToolkitLogo.jpg/1200px-SimpleITKToolkitLogo.jpg" alt="simpleitk" width="200"/>

> SimpleITK is a simplified layer built on top of ITK, intended to facilitate its use in rapid prototyping, education, interpreted languages.

#### [`itk` - ITKPythonPackage](https://itkpythonpackage.readthedocs.io/)
PyPI package for a pythonic interface to ITK.


### [VTK - Visualization Toolkit](https://www.vtk.org/)

<img src="https://c1.staticflickr.com/3/2244/2286824312_3d69ae384a_z.jpg?zz=1" alt="vtk" width="200"/>

> The Visualization Toolkit (VTK) is open source software for manipulating and displaying scientific data. It comes with state-of-the-art tools for 3D rendering, a suite of widgets for 3D interaction, and extensive 2D plotting capability.

[Link to VTK examples](https://lorensen.github.io/VTKExamples/site/)


### [3D Slicer](https://www.slicer.org/)

<img src="https://www.slicer.org/w/img_auth.php/1/1f/3DSlicerLogo-H-Color-1273x737.png" alt="slicer" width="200"/>

> 3D Slicer is an open source software platform for medical image informatics, image processing, and three-dimensional visualization. Built over two decades through support from the National Institutes of Health and a worldwide developer community, Slicer brings free, powerful cross-platform processing tools to physicians, researchers, and the general public.

[Link to 3D Slicer tutorials](https://www.slicer.org/wiki/Documentation/4.8/Training)


### [ITK-SNAP](http://www.itksnap.org/pmwiki/pmwiki.php)

<img src="http://www.itksnap.org/Artwork/snaplogo3.png" alt="itksnap" width="200"/>

> ITK-SNAP is a software application used to segment structures in 3D medical images. It provides semi-automatic segmentation using active contour methods, as well as manual delineation and image navigation.


## [NIPY](http://nipy.org/)

<img src="http://nipy.org/img/nipy.svg" alt="nipy" width="200"/>

> NIPY is a community of practice devoted to the use of the Python programming language in the analysis of neuroimaging data.


### Analysis Pipeline Management

#### [Nipype](https://nipype.readthedocs.io/)

<img src="http://miykael.github.io/nipype-beginner-s-guide/_static/nipype-beginners-guide-html_logo.png" alt="nipype" width="200"/>

> Nipype, an open-source, community-developed initiative under the umbrella of NiPy, is a Python project that provides a uniform interface to existing neuroimaging software and facilitates interaction between these packages within a single workflow.


### File I/O
#### [NiBabel](http://nipy.org/nibabel/)
> Read / write access to some common neuroimaging file formats.

#### [`dcm2niix`](https://github.com/rordenlab/dcm2niix)
`dcm2niix` is a tool designed to convert neuroimaging data from the DICOM format to the NIfTI format.

## Neuroimaging

### [ANTs - Advanced Normalization Tools](http://stnava.github.io/ANTs/)
> Advanced Normalization Tools (ANTs) extracts information from complex datasets that include imaging.

It heavily relies on ITK.

### [SPM - Statistical Parametric Mapping](https://www.fil.ion.ucl.ac.uk/spm/)
> Statistical Parametric Mapping refers to the construction and assessment of spatially extended statistical processes used to test hypotheses about functional imaging data. These ideas have been instantiated in software that is called SPM.

>The SPM software package has been designed for the analysis of brain imaging data sequences. The sequences can be a series of images from different cohorts, or time-series from the same subject. The current release is designed for the analysis of fMRI, PET, SPECT, EEG and MEG.


### [FSL - Functional Magnetic Resonance Imaging of the Brain Software Library](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki)

<img src="https://fsl.fmrib.ox.ac.uk/fsl/wiki_static/fsl/img/fsl-logo-x2.png" alt="fsl" width="200"/>

> FSL is a comprehensive library of analysis tools for FMRI, MRI and DTI brain imaging data.


### [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/)

<img src="https://surfer.nmr.mgh.harvard.edu/fscortex.png" alt="freesurfer" width="200"/>

> An open source software suite for processing and analyzing (human) brain MRI images.


### [MRtrix3](http://www.mrtrix.org/)

> MRtrix3 provides a set of tools to perform various types of diffusion MRI analyses, from various forms of tractography through to next-generation group-level analyses.


## Registration

### [NiftyReg](http://cmictig.cs.ucl.ac.uk/wiki/index.php/NiftyReg)
![niftyreg](https://cmiclab.cs.ucl.ac.uk/uploads/-/system/project/avatar/252/nifty_reg_logo.png)
NiftyReg is an open-source software for efficient medical image registration.


## Deep learning

### [NiftyNet](http://www.niftynet.io/)
![niftynet](http://www.niftynet.io/img/niftynet-logo.png)
> NiftyNet is a TensorFlow-based open-source convolutional neural networks (CNNs) platform for research in medical image analysis and image-guided therapy. NiftyNet’s modular structure is designed for sharing networks and pre-trained models.

## File formats

### [NIfTI - Neuroimaging Informatics Technology Initiative](https://nifti.nimh.nih.gov/)
![nifti](https://nifti.nimh.nih.gov/iconBlue.jpg)
> NIfTI-1 is a new Analyze-style data format, proposed by the NIfTI DFWG as a short-term measure to facilitate inter-operation of functional MRI data analysis software packages.

### [DICOM - Digital Imaging and Communications in Medicine](https://www.dicomstandard.org/)
![dicom](http://blog.nema.org/wp-content/uploads/2016/11/DICOM-logo-e1479849233486.jpg)
> DICOM® (Digital Imaging and Communications in Medicine) is the international standard to transmit, store, retrieve, print, process, and display medical imaging information.

### [NRRD - Nearly Raw Raster Data](http://teem.sourceforge.net/nrrd/)
![nrrd](http://teem.sourceforge.net/img/nrrd256.jpg)
> Nrrd is a library and file format designed to support scientific visualization and image processing involving N-dimensional raster data.


## Others

### [SciPy ecosystem](https://www.scipy.org/)
![scipy](https://cdn-images-1.medium.com/max/400/1*ejeltApvDzDBB9izIwnyiQ.png)
> SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. In particular, these are some of the core packages:

#### [NumPy](http://www.numpy.org/)
![numpy](https://www.scipy.org/_static/images/numpylogo_med.png)
> NumPy is the fundamental package for scientific computing with Python.

#### [IPython](http://ipython.org/)
![ipython](https://www.scipy.org/_static/images/ipython.png)
> Enhanced Interactive Console

#### [SciPy library](https://www.scipy.org/scipylib/index.html)
![scipylib](https://www.scipy.org/_static/images/scipy_med.png)
> The SciPy library is one of the core packages that make up the SciPy stack. It provides many user-friendly and efficient numerical routines such as routines for numerical integration and optimization.

#### [Matplotlib](https://matplotlib.org/)
![mpl](https://www.scipy.org/_static/images/matplotlib_med.png)
> Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.

#### [Pandas](http://pandas.pydata.org/)
![pandas](https://www.scipy.org/_static/images/pandas_badge2.jpg)
> Pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

### Other plotting libraries

#### [Seaborn](https://seaborn.pydata.org/)
> Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

#### [Altair](https://altair-viz.github.io/)
![altair](https://altair-viz.github.io/_static/altair-logo-light.png)
> Altair is a declarative statistical visualization library for Python, based on Vega and Vega-Lite.


### Machine learning
#### [TensorFlow](https://www.tensorflow.org/)
![tf](https://pbs.twimg.com/profile_images/773317101012586496/q8sc1KuZ_400x400.jpg)
> TensorFlow is an open-source machine learning library for research and production.

#### [PyTorch](https://pytorch.org/)
![pytorch](https://upload.wikimedia.org/wikipedia/commons/9/96/Pytorch_logo.png)
> An open source deep learning platform that provides a seamless path from research prototyping to production deployment.

#### [Keras](https://keras.io/)
![keras](https://upload.wikimedia.org/wikipedia/commons/c/c9/Keras_Logo.jpg)
> Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation.

#### [Scikit-learn](http://scikit-learn.org/)
![sklearn](http://scikit-learn.org/stable/_images/scikit-learn-logo-notext.png)
> Scikit-learn is a free software machine learning library for the Python programming language.


### Computer vision / image processing

#### [OpenCV - Open Source Computer Vision Library](https://opencv.org/)
![opencv](https://qph.fs.quoracdn.net/main-qimg-748316a749bdb46f5cdbe02e976e5500)
> OpenCV (Open Source Computer Vision Library) is released under a BSD license and hence it’s free for both academic and commercial use. It has C++, Python and Java interfaces and supports Windows, Linux, Mac OS, iOS and Android. OpenCV was designed for computational efficiency and with a strong focus on real-time applications.

#### [Pillow](https://pillow.readthedocs.io/)
> Pillow is the friendly PIL fork by Alex Clark and Contributors. PIL is the Python Imaging Library by Fredrik Lundh and Contributors.

#### [Scikit-image](https://scikit-image.org/)
![skimage](https://avatars3.githubusercontent.com/u/897180?s=400&v=4)
> Scikit-image is a collection of algorithms for image processing.
