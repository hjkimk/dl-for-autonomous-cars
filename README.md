# Semi-Supervised Learning in Simulation

Topic: Semi-Supervised Learning in OpenAI's Car-Racing Simulation\
Abstract: Semi-Supervised Learning is a highly efficient method to leverage unlabeled data in cases
where labeling data is expensive for large datasets. This paper aims to investigate whether
Semi-Supervised Learning algorithms, namely MixMatch and FixMatch from Google Research,
can be used to automate a car agent in OpenAI’s car-racing simulation environment. The
performance of various models is tested through statistical analysis for 50 consecutive trials in
the simulation. Convolutional Neural Networks trained using FixMatch with Selective MixUp,
a novel modification of the original FixMatch algorithm, generally perform better than models
trained using the MixMatch approach. FixMatch with Selective MixUp using 800 labels (10% of
the total training data) achieved an average car-racing score of 719 and a median of 775.71 for 50
successive trials in the simulation. This result is comparable to the performance of Supervised
Learning with 8000 labels.\
View the detailed project report [here](final_report.pdf).