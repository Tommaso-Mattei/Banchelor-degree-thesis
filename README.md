# Banchelor-degree-thesis
This is the thesis for my banchelor's degree in the academic year 2023/2024 at "La Sapienza - university of Rome". Both the pdf and the ppt are in italian. 
In the pdf we have the thesis in its entirety while in the ppt we have a short presentation of the work.

# The idea
The work focuses on the topic of human action recognition, in particular dealing with machine learning. At first, i analyzed the state of the art for human action recognition to identify the most prominent modalities and methods, ending up choosing the skeletal modality with 3D coordinates. After that many different machine learning architectures were considered and, at the time, the most prominent one was the GCN or Graph-Convolutional network. 
A good portion of the thesis reviews and summarizes machine learning in general, from a small introduction to feature engineering to how deep learning works. 

The particular architecture i chose to analyze and run locally was the HD-GCN from this repository (https://github.com/Jho-Yonsei/HD-GCN), of which i thank the authors who shared their code.
To work with this model i mainly used the NTU RGB+D 60/120 dataset, for which i thank the ROSE lab in Singapore (https://rose1.ntu.edu.sg) who made it available to me.

Working with the model and the dataset i split it a little differently then how it was usually used, making sure to have a very big training, a validation and a completely unseen test. Beyond that i also changes some hyperparameters to better work with my machine and for experimentations.

All the details are inside the report.
