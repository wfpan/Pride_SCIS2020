# TSE_Pride
This is the replication package for our work submitted to IEEE Transactions on Software Engineering, i.e., Weifeng Pan, Hua Ming, Dae-Kyoo Kim, Zijiang Yang. PRIDE: Prioritizing documentation effort based on an improved PageRank algorithm and simple filtering rules. IEEE Transactions on Software Engineering, 2021, submitted. [[PDF](#)]

Note that we only provide our tool used to compute ClassRank PageRank values, and some sample WDCCNs. The whole data set will be available after our paper's acceptance.

# WDCCN
This directory contains the WDCCNs that we built for all the subject systems used in our experiments. There are three versions of WDCCNs according to different weighting mechanisms. Note that the whole data set will be available after our work's acceptance. Of course, interested readers can email us (Email: wfpan@zjgsu.edu.cn) to get the whole data set in advance. Please use your institutional email address.

# Pride.jar
Pride.jar is the tool used to compute the ClassRank PageRank values. It is a small part of our own developped software, SNAP. Of course, the SNAP software can be obtained by emailing us (Email: wfpan@zjgsu.edu.cn).

# How to use our data set and software
The steps to use Pride.jar is shown as follows. To run the software, you should install the jdk (java development kit) 1.6 (or higher) first in your computer. JDK can be downloaded from https://www.oracle.com/technetwork/java/javase/downloads/index.html
- Download the Pride.jar and the data set file to the same directory.
- Double-click the Pride.jar
- Select File->Open a WDCCN file...
- Browse the WDCCN directory and select a specific WDCCN file (end with .net).
- Select Analysis->ClassRank
- Then you will get the ClassRank PageRank value for each class. You can also find a file storing the obtained results in the corresponding directory.

# Cite our work
If you use our data set or tool, please cite our work.

Weifeng Pan, Hua Ming, Dae-Kyoo Kim, Zijiang Yang. PRIDE: Prioritizing documentation effort based on an improved PageRank algorithm and simple filtering rules. IEEE Transactions on Software Engineering, 2021, submitted. [[PDF](#)]
