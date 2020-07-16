# Lithic Classification

This repository is where I will attempt to:
    1. Create labels for unlabeled rock types via ensemble classification
    2. Create a RF classification algorithm using those labels for identifying unknown rock types in the future
    3. Test the RF classification on a test set
    
The data for this project was collected by me during my undergraduate studies using a Bruker Tracer IV X-Ray Fluorescence analyser. This analyser was used on 1000+ artifacts of unknown rock types & raw chert samples from known locations. Each scan generated an estimation of the chemical intensity of 30 elements per sample, which I am using as an approximation of the chemical makeup of each sample. This data can be found in the AllSamples.csv file in this repository. Some of these artifacts were scanned more than once, and a small subset of these serves as the test set, named Test.csv. 

