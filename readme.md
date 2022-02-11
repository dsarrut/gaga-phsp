
GAGA = GAN for GATE

```pip install gaga-phsp```

 Scripts associated with the publication :
Phys Med Biol. 2019 doi: https://doi.org/10.1088/1361-6560/ab3fc1
Generative adversarial networks (GAN) for compact beam source modelling in Monte Carlo simulations
Sarrut D, Krah N, Letang JM.
https://www.ncbi.nlm.nih.gov/pubmed/31470418

A method is proposed and evaluated to model large and inconvenient phase space files used in Monte Carlo simulations by a compact Generative Adversarial Network (GAN). The GAN is trained based on a phase space dataset to create a neural network, called Generator (G), allowing G to mimic the multidimensional data distribution of the phase space. At the end of the training process, G is stored with about 0.5 million weights, around 10MB, instead of few GB of the initial file. Particles are then generated with G to replace the phase space dataset.&amp;#13; &amp;#13; This concept is applied to beam models from linear accelerators (linacs) and from brachytherapy seed models. Simulations using particles from the reference phase space on one hand and those generated by the GAN on the other hand were compared. 3D distributions of deposited energy obtained from source distributions generated by the GAN were close to the reference ones, with less than 1\% of voxel-by-voxel relative difference. Sharp parts such as the brachytherapy emission lines in the energy spectra were not perfectly modeled by the GAN. Detailed statistical properties and limitations of the GAN-generated particles still require further investigation, but the proposed exploratory approach is already promising and paves the way for a wide range of applications

Examples :
https://github.com/OpenGATE/GateContrib/tree/master/dosimetry/gaga-phsp
