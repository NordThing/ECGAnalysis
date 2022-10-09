Latest update: 2022-10-09
# Latest comments about this project 
I´m trying to consolidate as much information as possible here to get forward what I´m trying to achieve. 
There will not be a good order in this project right now, but will be cleaned later. 


# ECGAnalysis - GOAL 
1. Use latest Angular framework to build the frontend
2. Use latest WFDB for python to build the backend

# ECGAnalysis - Howto do it
https://www.highcharts.com/blog/tutorials/highcharts-and-angular-7/



# ECGAnalysis
Collecting information about differents types and trying to use already existing software. 
We will build a backend and a frontend with the capabilites to review the waveforms and do beat annotations. 
A good resource to find software is physionet.org

Today there are many waveforms that could be read. The most common sense to be .ishne and .edf and .edf+ 
There are of course a lot more formats

When finding the right place there is a lot of resources for this - very interesting. 
The most interesting is the WFDB for Python that are created. This we can use to call from a web-application to render the ECG-wave. 
I also found this https://github.com/citiususc/construe An abductive framework for the interpretation of time series, with special application to ECG data.

https://github.com/jeffplourde/wfdb here is a sample to connect Node.js with WFDB

# ECGAnalysis
EP Limited:  Open Source ECG Analysis Software - STEP 1

osea13.pdf - Open Source ECG Analysis Software Documentation 

BuildInstructions.txt -  Instructions for unpacking and compiling gcc file versions

/ec13/ - Test files for standard AAMI EC13

/src/  - Original source code from EP Limited - QRS-finder and Beat-analyser

/mitdb/ - MIT-BIH Arrhythmia Database

/mitdbaf/ - MIT-BIH Atrial Fibrillation Database
