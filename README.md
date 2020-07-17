# Neural-Net-for-SUSY-Dataset

The SUSY dataset can be found here:https://archive.ics.uci.edu/ml/datasets/SUSY

I have achieved 80% accuracy on the training as well as test dataset.

## Description of the SUSY dataset:

In high energy physics experiments, such as the ATLAS and CMS detectors at the CERN LHC, one major hope is the discovery of new particles. To accomplish this task, physicists attempt to sift through data events and classify them as either a signal of some new physics process or particle, or instead a background event .Here instead we will use logistic regression in order to attempt to find out the relative probability that an event is from a signal or a background event and rather than using the kinematic quantities of final state particles directly we will use the output of our logistic regression to define a part of phase space that is enriched in signal events. 
The dataset we are using has the value of 18 kinematic variables (‘‘features’’) of the event. The first 8 features are direct measurements of final state particles, in this case the pT , pseudo-rapidity, and azimuthal angle of two leptons in the event and the amount of missing transverse momentum (MET) together with its azimuthal angle. The last ten features are functions of the first 8 features; these are high-level features derived by physicists to help discriminate between the two classes.
The dataset consists of 5 million events, the first 4,500,000 of which we will use for training the model and the last 500,000 examples will be used as a test set. 
