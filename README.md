# Ghost-Hunting-Finding-a-Botnet-in-NetFlow-Traffic
Searching for malware is like hunting ghosts.  Purposefully designed to blend in with normal system traffic, the average network security officer can easily miss malware transmissions traversing his or her network amongst the vast amount of other material(Gunter, 2020). 
This project is designed to determine the efficacy of machine learning classification and data modification techniques in identifying those malware transmissions.  

First, we clean the data and make determinations about how to extract the maximum amount of information from the available variables.  Next, we directly employ a range of classification techniques to discern which are optimized for this type of dataset.  Finally, dimension and dataset reduction techniques are employed to see how efficiently high accuracy results can be achieved.  

In most cases, our efforts were successful, validating the use of many of the machine learning classification and data manipulation techniques explored for use in classifying botnet traffic.  

## About dataset:
 In 2011, the Czech Technical University (CTU) generated network packet capture (PCAP) in order to show how malicious botnets, a form of malware, appear when present in otherwise normal, benign network traffic (Stratosphere Lab, 2020).  The aforementioned PCAP, known as CTU-13, was posted publicly online for researchers to use.  
This project used the NetFlow of a portion of that PCAP, showing high-level summary data characterizing each network.  While only a small part of the overall CTU-13, the selected dataset still contained approximately 1.29 million NetFlow observations. 
### Data Source: https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-54/

https://www.stratosphereips.org/datasets-ctu13

This second link provides an overview of the Czech Technical University dataset 13 (CTU-13), of which we are examining one part (CTU-Malware-Capture-Botnet-54).

Backup site for CTU-13 dataset: https://mega.nz/folder/vdRmBA6D#yMZXx74nnu8GjhdwSF54Sw/folder/TBAVQK5b

Here's a link to our presentation on YouTube: https://www.youtube.com/watch?v=Z_-J9RFIwlQ&feature=youtu.be
