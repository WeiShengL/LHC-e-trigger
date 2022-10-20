# LHC_e_trigger

This was a summer internship project attempting to use machine learning models for classification of electrons and jets (particularly $\pi_0$ jets which have a double peak structure in the electromagnetic calorimeter layer) at ATLAS. An attempt has been made to train several machine learning algorithms (Convolutional Neural Network (CNN), Boosted Decision Tree, AdaBoost....) and evaluate its performance using simulated data provided by University College London Department of Physics and Astronomy. The algorithms are then compared against an existing algorithm (e-ratio algorithm) which is also aim to classify electrons and $\pi_0$ jets.


This repository consists of jupyter notebooks written to build, train and save models for further evaluation. Within the "saved_model" directories, you may find models that are saved which is then used to compare against the e-ratio algorithm based on their Pt dependency and rejection rate.

A brief summary of the project is included in "*Summary.pdf*"

With an improved in performance using CNN, the project will continue to be carry out by future students with an attempt to implement the models into FPGA circuits which could be used at the ATLAS detector as a hardware-based trigger system to select interesting events.

# Author
- Wei Sheng Lai 


# Acknowledgements
- The author would express his great thanks to his teammates on the physics project: Mr. Ibrahim Almasri and Mr. Zian Huang, for providing the foundation of Machine Learning Models.
- This physics project was supervised by Prof. Nikolaos Konstantinidis at UCL Department of Physics and Astronomy.
- We also really appreciate all of the supports from Dr. Naoki Kimura and Dr. Alex Christopher Martyniuk at CERN.
