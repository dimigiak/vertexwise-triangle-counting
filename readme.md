**Vertexwise triangle counting**

This project was implemented during the "Parallel and Distributed Systems" course of Electrical and Computer Engineering School, Aristotle University of Thessaloniki.
The topic of the project is counting of triangles of large unweighted and undirected graphs, by calcutaing a vector *c3*, that express the number of triangles that every node takes part in. In graph theory, the triangle graph is the complete graph K3, consisting of three vertices and three edges. 
Triangle counting has gained increased popularity in the fields of network and graph analysis. The application of triangle detection, location, and counting are multi-fold: detection of minimal cycles, graph-theoretic clustering techniques, recognition of median, claw-free, and line graphs, and test of automorphism.
Source code consist of two different algorithms (v3 and v4) of calcutaing c3 vector. For every version, there is a sequential implementation and some parallel ones, that use Cilk, OpenMP and PThreads. 
The parallel implementations were tested in the AUTh High Performance Computing (HPC) and some data were exported. Afterwards, we 
used this data to analyze the behaviour of our code...

**Project parts**:
1) graphs: Contains 5 graphs as mtx files that were used in the project.
2) hpc_data: Contains the operation times that were recorded during the experiment in HPC.
3) scripts: Contains the bash scripts that were used to run the project in HPC.
4) speedup: Contains a Matlab script that was used to export speedup diagrams with the data from HPC.
5) src: Contains the source code of the project.