# Wave-Terrain-Synths
Exploring Wave Terrain Synthesis on Max/MSP


Wave Terrain Synthesis with real time genexpr functions.
This is an attempt to develop a wave terrain synthesizer (aka tridimensional wavetable synth) without using buffer, instead performing a f(z) according to a two-dimensional input [x, y].
In this text the orbit (the trajectory of [x, y]) is simply formed by two ramps with independent frequency control, but it could be implemented a more complex system. 
The Terrain (function $1) parameter allows to select between three different f(z) functions which form a different terrain. These were arbitrarily chosen considering their output in a tridimensional graph, but a very extensive number of functions could be applied, including chaotic ones. Usually only functions  -1 < z < 1 are used for this synthesis technique. 
This patch is modified starting from an attempt to implement a wave terrain synth from Max user NOAH, which was porting a C++ script from Aaron Anderson.
More ideas could be found in the Computer Music Tutorial by Curtis Roads and in Stuart James' papers.

www.olbos.xyz
