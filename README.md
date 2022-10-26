# LMEE-dataset
This consists of the dataset named 'parameters1.csv'used in our project in which the microstuctures of liquid metal embedded elastomers were linked to material properties via a machine learning model.
The first column in the dataset is the microstructure ID. It is redundant data and is not used.
The second column is the volume fraction of the inclusion. It ranges between 0 and 30%.
The third column is the number of ellipsoidal inclusions. Since there are also an equal number of spherical inclusions, the total number of inclusions are obtained by multiplying the number in this column by 2. 
The fourth column is the mean size of the inclusions and this has been normalized with respect to the RVE size.
The fifth column is the standard deviation of the inclusion size and this has also been normalized with respect to the RVE size.
The sixth column is the aspect ratio of inclusions.
The seventh and eighth column are thermal conductivity and dielectric constant. These are obtained for every microstructure with the help of FFT simulations.
The ninth column is the hyperelastic parameter and this is obtained by running FE simulations on each simulation using Abaqus CAE subroutines.
