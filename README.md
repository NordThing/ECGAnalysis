Latest update: 2022-10-08
# ECGAnalysis
Collecting information about differents types and trying to use already existing software. 
We will build a backend and a frontend with the capabilites to review the waveforms and do beat annotations. 
A good resource to find software is physionet.org

Today there are many waveforms that could be read. The most common sense to be .ishne and .edf and .edf+ 
There are of course a lot more formats

When finding the right place there is a lot of resources for this - very interesting. 
The most interesting is the WFDB for Python that are created. This we can use to call from a web-application to render the ECG-wave. 
I also found this https://github.com/citiususc/construe An abductive framework for the interpretation of time series, with special application to ECG data.

# ECGAnalysis
EP Limited:  Open Source ECG Analysis Software - STEP 1

osea13.pdf - Open Source ECG Analysis Software Documentation 

BuildInstructions.txt -  Instructions for unpacking and compiling gcc file versions

/ec13/ - Test files for standard AAMI EC13

/src/  - Original source code from EP Limited - QRS-finder and Beat-analyser

/mitdb/ - MIT-BIH Arrhythmia Database

/mitdbaf/ - MIT-BIH Atrial Fibrillation Database
