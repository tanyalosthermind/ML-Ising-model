# ML-Ising-model
Machine learning with Monte-Carlo data for the 2D classical Ising model.

We study the 2D square lattice Ising model at two different temperatures using Monte-Carlo
generation of spin configurations by Swendsen–Wang algorithm. We generate the spin configurations
at two different temperatures: above and below the critical Tc ≈ 2.27. We use this data to train
two types of neural networks in order to predict exact temperatures for different phases. It can bee
seen from the results that an approach with only two temperatures provides not enough reliable
predictions. The accuracy can be improved using more temperatures for training of the network.

The code fully works in Google Collab, I didn't debug it yet to compile here :)
