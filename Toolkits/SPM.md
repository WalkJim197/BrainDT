**Brief descriptions:** SPM (Statistical Parametric Mapping) is a software package designed for the analysis of brain imaging data sequences. The sequences can be a series of images from different cohorts, or time-series from the same subject. The current version is SPM12, released on 1st October 2014 and last updated on 13th January 2020.<br>

**Platform:** SPM is implemented as a suite of MATLAB functions with some externally compiled C routines. It is designed to work with MATLAB versions R2007a (7.4) to R2023b (9.15), and will not work with earlier versions. It only requires core MATLAB to run, i.e., no special toolboxes are required.<br>

**System:** SPM is compatible with multiple operating systems. Pre-compiled binaries of the external C-MEX routines are provided for Windows (32 and 64 bit), Linux (64 bit), and macOS (64 bit). For these platforms, SPM should work straight out of the box. For other platforms, you will need to build the MEX files using a suitable C compiler and the Makefile provided with the SPM distribution.<br>

**File Format:** SPM12 uses the NIFTI-1 file format for the image data. All images are written as NIFTI-1, but it will also read the old Analyze format used by SPM2. Tools are provided to import data from DICOM, PAR/REC, MINC, and ECAT7. SPM12 also uses the GIfTI file format for surface-based data
