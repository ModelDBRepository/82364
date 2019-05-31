NEURON files from the paper:

Ingrid van Welie, Michiel W.H. Remme, Johannes A. van Hooft, and Wytse
J. Wadman Different levels of Ih determine distinct temporal
integration in bursting and regular-spiking neurons in rat subiculum,
Journal of Physiology (2006). DOI:10.1113/jphysiol.2006.1139441

The subiculum.hoc file will run four 800ms simulations plotting the
membrane potential at the soma

The cell morphology is the one illustrated in figure 6A (now with the
axon).  The morphology of this typical subiculum neuron is given in
the S40.hoc file

The simulation produces part of the data illustrated in figure 6D and
6E.

Regular and burst firing pyramidal neurons from the subiculum differ
in the levels of Ih. In the simulations a fraction of the AMPA
synapses distributed over the apical dendrites are simultaneously
activated at eiter 20 Hz or 50 Hz in both types of neurons. The
simulations support the experimental results from the paper,
illustrating that the different densities of Ih affect the summation
of the synaptic input when recorded from the soma.

Under unix systems:
to compile the mod files use the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui subiculum.hoc

Under Windows systems:
to compile the mod files use the "mknrndll" command.
A double click on the simulation file
subiculum.hoc 
will open the simulation window.

Questions on how to use this model should be directed to
wadman@science.uva.nl
