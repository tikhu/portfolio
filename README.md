# Software/Code Samples

I have worked on various different [research projects](https://mosi.informatik.uni-rostock.de/team/staff/till-koester/). The focus is usually to create a prototype to showcase a particular methodological advancement or to answer a domain-driven question with a particular model. Not all software artifacts are publicly available.

Here are some selected projects in which snapshots are available from various repositories. My focus is usually on exploring the performance.

A list of publications is available on [scholar](https://scholar.google.com/citations?user=osDesgYAAAAJ&hl=en) or university [eprints](https://eprints.mosi.informatik.uni-rostock.de/view/creators/K=F6ster=3ATill=3A=3A.html).


* [ML-Rules 3](https://git.informatik.uni-rostock.de/mosi/ml-rules3-official) is a research tool for hierarchical cell-biological reaction network methods, written in Rust. This tool reads a custom domain-specific language (modified slightly from previous work) for cell biological simulation (defined in earlier works) and executes it. A corresponding paper is currently under review.
I have written the entire code except the test cases.  
I also experiment with the idea of web hosting this tool using web assembly, available at [mlrules.pages.dev](https://mlrules.pages.dev).
ML-Rules 3 is currently used for active research projects by multiple other researchers.

* [MinimalSSA](https://git.informatik.uni-rostock.de/mosi/minimal-ssa) is a toy simulation tool to compare various SSA Algorithms written in Rust, written by me (except a few minor commits).
This includes a simulation generation tool, where custom code is generated and compiled for optimized execution. According to my measurements, this is the fastest existing SSA tool, among many, at the moment (though somewhat limited in features).

* [ML3](https://git.informatik.uni-rostock.de/mosi/ML3-Rust) is a simulator for agent-based modeling written in Rust by me. I’ve used it to explore the use of procedural macros in Rust and their potential for use in domain-specific languages. A description of the concept and the software (including some benchmarks) is available in an [open access publication](https://www.jasss.org/27/1/10.html)

* For a performance [study paper](https://ieeexplore.ieee.org/document/9384086), I implemented different versions of [Cellular Automata](https://osf.io/g5yah/) in Rust. In particular, experiments are described in relation to the application of stochastic transition functions.

* For a [research project](https://doi.org/10.1098/rsos.221177), I implemented a small simulator for spatial behavior on membranes in Rust [Code](https://osf.io/5y7cw).

* For a [parallel simulation paper](https://doi.org/10.1145/3573900.3591115) of the window racer simulator, written in C++, I contributed some optimized data structures (queue), as well as a simulation model for spatial reaction-diffusion system (nsm files) ([code link](https://doi.org/10.5281/zenodo.7829485)).

* [ML-Force](https://git.informatik.uni-rostock.de/mosi/ml-force-publication) is a spatial simulator for reactive systems I wrote in C++. This research prototype also explores the use of macros for domain-specific languages. It includes some numerical simulation approaches. The focus of the novel underlying method is outlined in an [open access publication](https://doi.org/10.1186/s12859-019-3092-y).

* I implemented some variations of [tree data structures](https://git.informatik.uni-rostock.de/mosi/dynamic_reaction_container) and algorithms for their processing for a [comparative study](https://dl.acm.org/doi/10.1145/3200921.3200943).
