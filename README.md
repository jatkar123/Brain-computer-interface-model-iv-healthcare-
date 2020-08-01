# Brain-computer-interface-model-iv-healthcare-

Brain-computer interfaces (BCIs) acquire brain signals, analyze them, and translate them into commands that are relayed to output devices that carry out desired actions. BCIs do not use normal neuromuscular output pathways. The main goal of BCI is to replace or restore useful function to people disabled by neuromuscular disorders such as amyotrophic lateral sclerosis, cerebral palsy, stroke, or spinal cord injury. 

In this repository, there are various functions which are mainly used for the 4 class MI classification, mainly using SVM(Support vector Machine) algorithm to classify the data.
The main.ipynb file consists firstly splitting the data set into training and testing, the whilst using the butterworth filteration on the data, applying classification analysis and then predicting the test results.
Various libraries like Scipy, pandas etc... were implemented for the crucial requirement.

The confusion matrix is yet to be corroborated as the project is still in process. Finally, the overall subject accuracy has been improved to 74.2%.
