

---
<p align="center"> <img src="https://img.shields.io/badge/License-GPLv3-blue.svg"> <img height=21  src="https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white"> 
<img height=21  src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
</p>



<br>
<br>

---
# Inspiration

My inspiration to work on Quantum Gravity is drawn from the movie [Interstellar](https://en.wikipedia.org/wiki/Interstellar_(film)) by [Chris Nolan](https://en.wikipedia.org/wiki/Christopher_Nolan). 
The black hole shown in the movie uses actual calculations which took more than 100+ hours to render.

Noble Price winer and theoretical physicist [Kip Thorne](https://en.wikipedia.org/wiki/Kip_Thorne), was the scientific consultant for this movie. He is a long time friend and colleague Stephen Hawking and Carl Sagan. 


This [Book](https://en.wikipedia.org/wiki/The_Science_of_Interstellar) explains movie's technical details.


# Basics

<img width="666" alt="image" src="https://github.com/rvbug/q-gravity/assets/10928536/777d6cca-3701-4bd8-8a5d-b0b67b733a65">



<br>

# Quantum Gravity (QG)

Quantum Gravity (QG) helps describe gravity according to the principles of quantum mechanics and will help us to understand what happens near black hole and at the moment of singularity.
<br>


# Wormhole program

### Wormhole Distance Equation:
The function wormhole_distance() implements the simplified equation we discussed in the blog post:

d = c * t / √(1 - v²/c²)  

Where   
d is distance  
c is speed of light  
t is time   
v is velocity  


### Visualization Approach:

The code generates a plot showing how distance changes as velocity increases
It calculates normalized distances at different percentages of light speed
The x-axis represents velocity (0-100% of light speed)
The y-axis shows the normalized distance


### Key Observations:

As velocity approaches the speed of light, the distance increases dramatically
This illustrates the time dilation effect described in Kip Thorne's book
The green dots and red line help visualize how distance behaves non-linearly



### Dependencies:

Add plotters = "0.3.0" to  Cargo.toml file
The code generates a PNG image called wormhole_distance_plot.png

# Practical Implications:
This visualization helps beginners understand how:

- Time and distance are not absolute
- Velocity dramatically affects spacetime
- Concepts from "Interstellar" have real mathematical foundations


## Penrose Diagram
Penrose diagram helps in navigating inside a black hole







<br>

---
# References

* [arXiv](https://arxiv.org/)
* [Interstellar](https://en.wikipedia.org/wiki/Interstellar_(film))
* [Thought Experiment](https://en.wikipedia.org/wiki/Einstein%27s_thought_experiments)
* [Interstellar Visualization](https://www.space.com/27692-science-of-interstellar-infographic.html)
* [Quil](https://github.com/quil-lang/quil)
* [quil-rs](https://docs.rs/quil-rs/latest/quil_rs/)
* [qcs](https://docs.rs/qcs/latest/qcs/)
* [Autograd](https://docs.rs/autograd/latest/autograd/)
* [NDArray](https://docs.rs/ndarray/0.15.6/ndarray/)
* [NLOpt](https://docs.rs/nlopt/latest/nlopt/)  
* [roqoqo](https://hqsquantumsimulations.github.io/qoqo_examples/)  
* [Plotter](https://plotters-rs.github.io/book/basic/overview.html)   
* [Relativity](https://geometry-of-relativity.net/rotations-in-spacetime/)    
* [rustworkx](https://github.com/Qiskit/rustworkx/tree/main)    
* [Petgraph](https://docs.rs/petgraph/0.6.4/petgraph/index.html)    
* [MdBook](https://rust-lang.github.io/mdBook/guide/creating.html)      
* [Rust Book](https://doc.rust-lang.org/book/)  
* [Rust by examples](https://doc.rust-lang.org/rust-by-example/hello/print/print_debug.html)    
* [System Design](https://github.com/systemdesign42/system-design)    
* [Cargo Build](https://doc.rust-lang.org/cargo/commands/build-commands.html)   
* [Rust Practice](https://doc.rust-lang.org/)  
* [Rust for Rustaceans](https://rust-for-rustaceans.com/)


