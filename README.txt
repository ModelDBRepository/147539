
This directory contains NEURON files associated with computing
neuronal response to a Chirp stimulus. These files, and the functions
there in, could be used to generate traces that shed light on the
sensitivity of impedance measurements (both amplitude- and
phase-related) to various parameters associated with the h channel
and passive properties of a single compartmental model. These files
will help recreate results presented in Fig. 7 of the 2007 paper
and in Fig. 3 of the 2008 paper, both referenced below.

Rishikesh Narayanan and Daniel Johnston, “Long-term potentiation
in rat hippocampal neurons is accompanied by spatially widespread
changes in intrinsic oscillatory dynamics and excitability,” Neuron,
56(6), pp.  1061–1075, December 2007.

Rishikesh Narayanan and Daniel Johnston, “The h channel mediates
location dependence and plasticity of intrinsic phase response in
rat hippocampal neurons,” The Journal of Neuroscience, 28(22), pp.
5846–5860, May 2008.

An example output voltage file, named "ChirpGh_10.00.txt", is saved
in the Output directory.  It corresponds to default values for all
other parameters, with the h conductance set at 100 uS/cm2.  This
was generated using the "Chirp_Gh()" function.  The corresponding
current values are in the file "ChirpI.txt". Both files contain
1002000 points, corresponding to a time period of 25050 ms, with
40 points per ms. If impedance analyses were to be performed with
values in the "ChirpGh_10.00.txt" file as the voltage response, and
values in the file "ChirpI.txt" as the current input, then the
measurements should read as follows:

Resonance frequency (f_R): 6.77 Hz 
Resonance strength (Q): 1.338
Maximal impedance amplitude (|Z|_Max): 50.9 MOhm 
Total inductive area (Phi_L): 0.0545 rad.Hz

For details about each of these measurements, refer to the two
papers mentioned above.

Written by Rishikesh Narayanan. Contact: rishi.n@gmail.com
