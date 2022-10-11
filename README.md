# Reservoir-Computing-Force-Learning
Implementation of the Paper Generating coherent pattern of activity from chaotic neural networks 
@ https://www.sciencedirect.com/science/article/pii/S0896627309005479

This paper uses recursive least squares to modify readout weights in conventional echo state network. 
therefore, this model assumes there is feedback connections from readout neurons to the reservoir.
it shows that there is no need to satisfy echo state property and gets rid of the need to be at the edge of chaos. 
it shows that a chaotic reservoir could be controlled using online learning of the readout weights by RLS. 
