# Topics of interest
This is a  comprehensive list of topics covered in CSC 411. The idea is that during our research, we will fill in information under the topics that we come across as they relate to TPUs.
The purpose of this document is to show, as much as we possibly can, how our understanding of TPUs also shows a complete understanding of material covered in CSC 411.

## Number Systems
- 
## Bitwise Operations
- 
## Integers (signed and unsigned, representing data as bits)
- 
## Debugging(gdb)
- Debugging specialized processors like TPUs requires understanding their instruction flow and behavior under different workloads. Debugging tools are used to trace operations at the binary level. For example, analyzing TPU performance involves profiling individual matrix operations and their interaction with memory hierarchies. These tasks parallel debugging C programs with tools like GDB, as discussed in the lecture slides
## Memory 
- 
### Casting Integer Values
- 
### Byte ordering
- TPUs use big endian
### Pointers
- 
## Floating Point Number Representation
- 
### IEEE Standard
- 
## Computer Systems
- TPUs exemplify the design principles of domain-specific processors. Unlike CPUs or GPUs, which are general-purpose, TPUs are tailored for neural network inference.
### High Performance Computing
- 
### Abstractions
- 
### Instruction Set Architecture (ISA)
- TPUs use a simplified instruction set closer to the RISC (Reduced Instruction Set Computer) philosophy. This streamlined instruction set minimizes decoding complexity and maximizes execution efficiency.
### Chip Manufacturing
- 
## RISC-V
- Although the simplicity of CPUs running with RISC-V ISAs allows for clock speeds in the GHz range, large matrices of operations can greatly slow down these processors.
## Executing Instructions
- To speed up large matrix operations, RISC-V processors are able to preform vector processing, where operations are applied to an entire vector in parallel. This is commonly found in Graphics Processing Units (GPUs).
- The TPU takes this idea a step further, allowing for parallel matrix processing. This means that a TPU has the ability to preform an operation on a large matrix, all at the same time. This jurastically reduces execution time compared to the scalar processing of CPUs.
### Executing Memory Instructions
- 
### RISC-V Procedures
- 
## Representing Instructions
- 
### Control Instructions
- 
## Compiling, Interpreting, Running Programs
- 
### Compiling and Linking
- 
### Loading
- 
### Interpreters
- 
### Impacts on Performance
- 
### Optimization 
- The TPU features a large (28 MB) on-chip memory to minimize latency from accessing external memory. This design reflects the importance of efficient memory hierarchy in computer architecture.
- With performance per watt being 30–80 times higher than contemporary CPUs and GPUs, TPUs exemplify the trade-offs between general-purpose flexibility and domain-specific efficiency [reference](https://cloud.google.com/blog/products/ai-machine-learning/an-in-depth-look-at-googles-first-tensor-processing-unit-tpu)
## Performance
- 
### Amdahl's Law
- 
### Measuring Performance
- 
## Logic Design
- 
### Transistors
- 
### Digtial Logic
- 
## Boolean Algebra
- 
### Logic Circuits
- 
### Decoders
- 
### Multiplexers
- 
## Adders and ALUs
- 
### Adders
- 
### ALUs
- 
### Delays
- 
# Conclusion

The study of TPUs through the lens of computer organization highlights the relevance of foundational principles like number systems, Boolean algebra, and processor design in addressing real-world computational challenges. By focusing on domain-specific needs, TPUs achieve unparalleled efficiency in machine learning, making them a benchmark for future hardware innovations.

## 

## 

## 

