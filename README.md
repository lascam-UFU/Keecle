# Keecle
A semi automatic tool for finding Java key classes in open source systems

Steps to find key classes:

Setup Tools

1 -  Execution trace: trace extractor is a tool based on AspectJ. Unzip TraceExtractor and configure trace extractor on  Eclipse IDE. Convert your Java project in an AspectJ project and in sequence on the option Aspect Build -> Inpath add the trace extractor tool.

2- Trace compressor: Unzip TraceCompressor and in sequence configure on Eclipse IDE

3- Keecle: to find key classes, follow the steps:
 
   3.1- Create Subtrees
   
   3.2- Remove identical subtrees
   
   3.3- Train & Test: creat files .arff wiht test and training data
   
   3.4- Downloading and setup Weka software (https://www.cs.waikato.ac.nz/ml/weka/) to classify the trace subtrees 
   
   3.5- Key classes: from result of the classification subtrees on Weka, 
   
