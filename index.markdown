# Thesis Website
## About and Overview of Reserach 
I earned my PhD in Computational Science through a joint program between San Diego State University and UC Irvine, where I focused on using computational methods to understand and model complex biological systems. Specifically, I developed software and algorithms to simulate Dynamical Graph Grammars (DGGs) for the cortical microtubule array in plant cells. DGGs themselves are expressive and can effectively model and simulate the dynamics of complex biological systems, but the exact simulation algorithm traditionally used is slow for large systems. 

To overcome this limitation, Professor Eric Mjolsness and I developed an approximate simulation algorithm that maintains compatibility with the DGG formalism. This new algorithm employs a spatial decomposition approach at the system's time-evolution operator level, improving efficiency while allowing some rules or reactions to fire out of order, thus introducing potential errors. By partitioning the domain into subdomains, we exposed the potential for parallelism and confined errors to interactions between adjacent subdomains. Additional efficiency is achieved by maintaining an incrementally updated match data structure for all possible rule matches. 

I demonstrated these principles through the Dynamical Graph Grammar Modeling Library (DGGML) and developed two DGG models for the plant cell cortical microtubule array. These models provided insights into different behaviors such as network formation and local alignment, and explored the effects of different face shapes and boundary conditions on the cortical microtubule array. My work highlighted the flexibility and utility of DGGML, showcasing its viability for testing, screening, and inventing hypotheses to explain emergent phenomena in biological systems.

Additionally, during my PhD, I gained valuable experience in scientific computing and high-performance computing (HPC) through internships at Lawrence Livermore National Laboratory and Los Alamos National Laboratory. During these internships, I worked on projects involving plasma physics, machine learning, and asteroid detection. 

## Thesis and Papers
You can find a copy of my thesis [here](assets/img/thesis_compressed.pdf) or from the UCI or SDSU library. It offers a great tutorial and deeper undertanding of dynamical graph grammars and the design and implementation of the dynamical graph grammar modeling library [(DGGML)](https://github.com/emedwede/DGGML).

I have published a first-author paper in the journal Physical Biology, and another paper is currently available on arXiv. In the past, I have also contributed to a workshop paper on performance portability in Fortran and conducted an editorial review of a computer vision paper published in IEEE Transactions on Neural Networks and Learning Systems.

You can find my work associated with my [OrcID](https://orcid.org/0000-0001-7729-0614) or below:

* ["Advances in the Simulation and Modeling of Complex Systems using Dynamical Graph Grammars"](https://doi.org/10.48550/arXiv.2407.10072)
* [Approximate simulation of cortical microtubule models using dynamical graph grammars](https://doi.org/10.1088/1478-3975/acdbfb)
* ["Improving Fortran Performance Portability"](https://doi.org/10.1007/978-3-030-95953-1_6)
* ["Learning Semisupervised Multilabel Fully Convolutional Network for Hierarchical Object Parsing"](https://doi.org/10.1109/tnnls.2019.2931183)

## Software
Here you can find the open source softwared developed during my PhD:

* [The Dynamical Graph Grammar Modeling Library (DGGML)](https://github.com/emedwede/DGGML)
* [Yet Another Graph Library (YAGL)](https://github.com/emedwede/YAGL)
* [CajeteCMA](https://github.com/emedwede/CajeteCMA)

## Presentations
Plese click the link to access the web version of my disseration slides, with effects and all!
* [Defense Slides](phd_work/defense_slides_final/index.html)
