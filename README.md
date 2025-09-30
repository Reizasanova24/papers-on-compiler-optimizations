# Papers on Compiler Optimizations: Analysis and Transformations (1952-1994)

> [!NOTE]
> This repository is updated periodically. Contributions are welcome!

This repository curates a _chronologically_ sorted list of influential papers on compiler optimization, from the seminal works of 1952 through the advanced techniques of 1994. It's an essential resource for students, researchers, and engineers seeking to understand the foundational and critical advancements in compiler design, analysis, and optimization techniques.
The paper list is provided in two convenient formats:
- a PDF document ([papers.pdf](./papers.pdf)); a compiled $\LaTeX$ table with full bibliographic references for each paper,
- a markdown table; an easily browsed, embedded table in this `README` file. 

<details>
<summary>The $\LaTeX$ folder and its contents</summary>

The [latex folder](./latex/) contains the source files used to generate the PDF:
- the main latex document ([papers.tex](./latex/papers.tex)) that compiles the list of papers into the PDF document ([papers.pdf](./papers.pdf)), and
- a [BibTeX file](./latex/local.bib) with all bibliographic entries ready for citation purpose.
</details>

# Table of Papers

**Key for Columns**

Sources :
- A: [Advanced Compiler Design and Implementation](https://dl.acm.org/doi/10.5555/286076)
- D: [Compilers: Principles, Techniques, and Tools](https://dl.acm.org/doi/10.5555/1177220)
- E: [Engineering a Compiler](https://dl.acm.org/doi/book/10.5555/1526330)
- M: Modern Compiler Implementation in [C](https://dl.acm.org/doi/10.5555/550932)/[Java](https://dl.acm.org/doi/10.5555/599718)/[ML](https://dl.acm.org/doi/10.5555/993972)
- O: [Optimizing Compilers for Modern Architectures: A Dependence-Based Approach](https://dl.acm.org/doi/10.5555/502981) 
- S: [Compiler transformations for high-performance computing](https://dl.acm.org/doi/10.1145/197405.197406) - a 1994 survey paper

Type:
- C: Conference
- J: Journal
- W: Workshop

| Paper Title | Venue Type | Venue Name | Type | Year | Sources |
|---|---|---|---|---|---|
| The problem of simplifying truth functions | T&F | AMM | J | 1952 | O |
| Minimization of Boolean functions | Bell Labs | Bell System Tech. J. | J | 1956 | O |
| An algorithm for translating Boolean expressions | ACM | JACM | J | 1962 | S |
| High speed compilation of efficient object code | ACM | CACM | J | 1965 | D |
| Peephole optimization | ACM | CACM | J | 1965 | E |
| Index Register Allocation | ACM | JACM | J | 1966 | E |
| Analysis of Programs for Parallel Processing | IEEE | TC (TEC) | J | 1966 | O |
| Object code optimization | ACM | CACM | J | 1969 | A, D, E |
| Local optimizations | ACM | PLDI (SCO) | C | 1970 | E |
| Detection and parallel execution of independent instructions | IEEE | TCO | J | 1970 | S |
| Global common subexpression elimination | ACM | PLDI (SCO) | C | 1970 | D, E, M |
| The Generation of Optimal Code for Arithmetic Expressions | ACM | JACM | J | 1970 | D, E, M |
| Control flow analysis | ACM | PLDI (SCO) | C | 1970 | D, E |
| Flow graph reducibility | ACM | STOC | C | 1972 | D |
| Use-definition chains with applications | Elsevier | COLA (COMLAN) | C | 1972 | E |
| A global flow analysis algorithm | T&F | JCM | J | 1972 | E |
| Safety of code motion | T&F | JCM | J | 1972 | O |
| On the Number of Operations Simultaneously Executable in Fortran-Like Programs and Their Resulting Speedup | IEEE | TCO | J | 1972 | D, O |
| Testing flow graph reducibility | ACM | STOC | C | 1973 | A |
| A unified approach to global program optimization | ACM | POPL | C | 1973 | A, D, E, M, O, S |
| Fast algorithms for the elimination of common subexpressions | Springer | Acta Inf. | J | 1973 | A, D, E, O |
| Register allocation via usage counts | ACM | CACM | J | 1974 | A |
| Analysis of structured programs | ACM | STOC | C | 1974 | D |
| Characterizations of Reducible Flow Graphs | ACM | JACM | J | 1974 | D, E |
| The parallel execution of DO loops | ACM | CACM | J | 1974 | D, O |
| Interprocedural Data Flow Analysis | - | IFIP | J | 1974 | D, O |
| Time and parallel processor bounds for linear recurrence systems | IEEE | TCO | J | 1975 | S |
| A simple algorithm for global data flow analysis problems | SIAM | SICOMP | J | 1975 | A, E, O |
| A program data flow analysis procedure | ACM | CACM | J | 1976 | A |
| Recursion analysis for compiler optimization | ACM | CACM | J | 1976 | O |
| Optimal Code Generation for Expression Trees | ACM | JACM | J | 1976 | A, D, E |
| A Fast and Usually Linear Algorithm for Global Flow Analysis | ACM | JACM | J | 1976 | E, O |
| Code generation for expressions with common subexpressions | ACM | POPL | C | 1976 | E, S |
| Global data flow analysis and iterative algorithms | ACM | JACM | J | 1976 | E, O |
| On Live-Dead Analysis for Global Data Flow Problems | ACM | JACM | J | 1977 | A |
| Symbolic evaluation and the global value graph | ACM | POPL | C | 1977 | A |
| High-level data flow analysis | ACM | CACM | J | 1977 | A |
| Abstract interpretation | ACM | POPL | C | 1977 | D |
| An algorithm for reduction of operator strength | ACM | CACM | J | 1977 | E |
| A transformation system for developing recursive programs | ACM | JACM | J | 1977 | S |
| Arithmetic shifting considered harmful | ACM | SIGPLAN Notices | J | 1977 | S |
| Monotone data flow analysis frameworks | Springer | Acta Inf. | J | 1977 | A, D, E, O |
| Program Improvement by Source-to-Source Transformation | ACM | CACM | J | 1977 | D, O |
| An analysis of inline substitution for a structured programming language | ACM | CACM | J | 1977 | M, S |
| A new method for compiler code generation | ACM | POPL | C | 1978 | D |
| A practical interprocedural data flow analysis algorithm | ACM | CACM | J | 1978 | A, D, E, O |
| Data Flow Analysis for Procedural Languages | ACM | JACM | J | 1979 | A |
| Constructing the Call Graph of a Program | IEEE | TSE | J | 1979 | O |
| Data flow languages | IEEE | MARK | W | 1979 | S |
| Time and parallel processor bounds for Fortran-like loops | IEEE | TCO | J | 1979 | S |
| Unrolling loops in Fortran | Wiley | SPE | J | 1979 | S |
| A fast algorithm for finding dominators in a flowgraph | ACM | TOPLAS | J | 1979 | A, E, M, O |
| An efficient way to find the side effects of procedural calls and the aliases of variables | ACM | POPL | C | 1979 | A, D, E, S |
| Global optimization by suppression of partial redundancies | ACM | CAMC | J | 1979 | A, D, E, O, S |
| Predicting the effects of optimization on a procedure body | ACM | PLDI (SCC) | C | 1979 | E, S |
| Structural analysis: A new approach to flow analysis in optimizing compilers | Elsevier | COLA (COMLAN) | C | 1980 | A |
| The design and application of a retargetable peephole optimizer | ACM | TOPLAS | J | 1980 | E |
| Data flow supercomputers | IEEE | Computer | J | 1980 | S |
| High-speed multiprocessors and compilation techniques | IEEE | TCO | J | 1980 | S |
| Interprocedural data flow analysis in the presence of pointers, procedure variables, and label variables  | ACM | POPL | C | 1980 | A, E, O |
| Deciding Linear Inequalities by Computing Loop Residues | ACM | JACM | J | 1981 | D |
| A precise inter-procedural data flow algorithm | ACM | POPL | C | 1981 | O, S |
| Register allocation via coloring | Elsevier | COLA (COMLAN) | C | 1981 | A, D, E, O, S |
| Reduction of operator strength | NJ | Program flow analysis | J | 1981 | A, E, S |
| Dependence graphs and compiler optimizatlons | ACM | POPL | C | 1981 | O, S |
| On the performance enhancement of paging systems through program analysis and transformations | IEEE | TCO | J | 1981 | D, S |
| Optimizing delayed branches | ACM | MICRO | W | 1982 | D |
| A composite hoisting-strength reduction transformation for global program optimization part i | T&F | JCM | J | 1982 | E |
| Optimization of range checking | ACM | PLDI (SCC) | C | 1982 | E |
| Register allocation and spilling via graph coloring | ACM | PLDI | C | 1982 | A, D, E, M, O, S |
| Experience with the SETL optimizer | ACM | TOPLAS | J | 1983 | S |
| Postpass Code Optimization of Pipeline Constraints | ACM | TOPLAS | J | 1983 | A, E |
| Conversion of control dependence to data dependence | ACM | POPL | C | 1983 | O, S |
| Register allocation and exhaustive peephole optimization | Wiley | SPE | J | 1984 | E |
| Automatic generation of peephole optimizations | Springer | CC | C | 1984 | E |
| Analysis of interprocedural side effects in a parallel programming environment | Springer | ICSP | C | 1984 | O |
| Polyvariant mixed computation for analyzer programs | Springer | Acta Inf. | J | 1984 | O |
| Stream processing | ACM | LFP | C | 1984 | O |
| A hierarchical basis for reordering transformations | ACM | POPL | C | 1984 | O |
| Register allocation by priority-based coloring | ACM | PLDI (SCC) | C | 1984 | A, E, O |
| Automatic loop interchange | ACM | PLDI (SCC) | C | 1984 | O, S |
| Efficient computation of flow insensitive interprocedural summary information | ACM | PLDI (SCC) | C | 1984 | A, O |
| On linearizing parallel code | ACM | POPL | C | 1985 | O |
| Distributed execution of functional programs using serial combinators | IEEE | TCO | J | 1985 | S |
| Strictness analysis-a practical approach | Springer | FPCA | C | 1985 | S |
| A linear algorithm for finding dominators in flow graphs and related problems | ACM | STOC | C | 1985 | E, M, O |
| Efficient instruction scheduling for a pipelined architecture | ACM | PLDI (SCC) | C | 1986 | A |
| Efficient symbolic analysis of programs | ACM | JCSS | J | 1986 | A |
| Graph-Based Algorithms for Boolean Function Manipulation | IEEE | TC | J | 1986 | D |
| Loops skewing: The wavefront method revisited | Springer | JPP | J | 1986 | O |
| Highly concurrent scalar processing | ACM | CAN | J | 1986 | O |
| Multiplication by integer constants | Wiley | SPE | J | 1986 | S |
| Global register allocation at link time | ACM | PLDI | C | 1986 | A, E |
| Interprocedural constant propagation | ACM | PLDI | C | 1986 | A, D, E, O, S |
| Interprocedural optimization: eliminating unnecessary recompilation | ACM | CC | C | 1986 | A, E, O |
| Interprocedural dependence analysis and parallelization | ACM | PLDI | C | 1986 | O, S |
| Effectiveness of a machine-level, global optimizer  | ACM | PLDI (SCC) | C | 1986 | A, E |
| Direct parallelization of call statements | ACM | PLDI (SCC) | C | 1986 | O, S |
| Code motion of control structures in high-level languages | ACM | POPL | C | 1986 | E, M |
| Automatic inference and fast interpretation of peephole optimization rules | Wiley | SPE | J | 1987 | E |
| Compiler Algorithms for Synchronization | IEEE | TCO | J | 1987 | O |
| Automatic decomposition of scientific programs for parallel execution | ACM | POPL | C | 1987 | O |
| Guided Self-Scheduling: A Practical Scheduling Scheme for Parallel Supercomputers | IEEE | TCO | J | 1987 | S |
| Loop coalescing: A compiler transformation for parallel machines | ACM | ICPP | C | 1987 | S |
| Strategies for cache and local memory management by global program transformation | Springer | ICS | C | 1987 | S |
| The program dependence graph and its use in optimization | ACM | TOPLAS | J | 1987 | A, E, M, O |
| Automatic translation of Fortran programs to vector form | ACM | TOPLAS | J | 1987 | D, O, S |
| An efficient approach to data flow analysis in a multiple pass global optimizer | ACM | PLDI | C | 1988 | A |
| A solution to a problem with Morel and Renvoise's ``Global optimization by suppression of partial redundancies'' | ACM | TOPLAS | J | 1988 | E |
| Efficient computation of flow-insensitive interprocedural summary information—a correction | ACM | SIGPLAN Notices | J | 1988 | O |
| Dependence of multi-dimensional array references | ACM | ICS | C | 1988 | O |
| The importance of direct dependences for automatic parallelization | ACM | ICS | C | 1988 | O |
| Introducing symbolic problem solving techniques in the dependence testing phases of a vectorizer | ACM | ICS | C | 1988 | O |
| Generating sequential code from parallel code | ACM | SC | C | 1988 | O |
| Advanced loop optimizations for parallel computers | ACM | ICS | C | 1988 | S |
| An introduction to a formal theory of dependence analysis | Springer | JSC | J | 1988 | S |
| Analysis of interprocedural side effects in a parallel programming environment | ACM | ICS | C | 1988 | S |
| Array expansion | ACM | ICS | C | 1988 | S |
| Loop quantization: A generalized loop unwinding technique | ACM | JPDC | J | 1988 | S |
| Supernode partitioning | ACM | PLDI | C | 1988 | S |
| A fast algorithm for code movement optimisation | ACM | PLDI | C | 1988 | A, E |
| Compiling programs for distributed-memory multiprocessors | Elsevier | JSC | J | 1988 | O, S |
| Optimal loop parallelization | ACM | PLDI | C | 1988 | A, E, M, S |
| Software pipelining: an effective scheduling technique for VLIW machines | ACM | PLDI | C | 1988 | D, E |
| The program summary graph and flow-sensitive interprocedual data flow analysis | ACM | PLDI | C | 1988 | A, O |
| A framework for determining useful parallelism | ACM | ICS | C | 1988 | O, S |
| An overview of the PTRAN analysis system for multiprocessing | Elsevier | JPDC | J | 1988 | D, S |
| Efficient interprocedural analysis for program parallelization and restructuring | ACM | PPoPP (PPEALS) | C | 1988 | O, S |
| Compiling issues for supercomputers | ACM/IEEE | SC | C | 1988 | O, S |
| Minimizing register usage penalty at procedure calls | ACM | PLDI | C | 1988 | A, S |
| Estimating interlock and improving balance for pipelined architectures | Elsevier | JPDC | J | 1988 | O, S |
| Global value numbers and redundant computations | ACM | POPL | C | 1988 | E, O |
| Perfect pipelining: A new loop parallelization technique | Springer | ESOP | C | 1988 | A, S |
| Code scheduling and register allocation in large basic blocks | ACM | SC | C | 1988 | A, E |
| Interprocedural side-effect analysis in linear time | ACM | PLDI | C | 1988 | A, E, O |
| Unified management of registers and cache using liveness and cache bypass | ACM | PLDI | C | 1989 | A |
| A new algorithm for composite hoisting and strength reduction optimisation | T&F | JCM | J | 1989 | E |
| Program optimization for instruction caches | ACM | ASPLOS | C | 1989 | A |
| Dependence analysis for pointer variables | ACM | PLDI | C | 1989 | E |
| The program dependence graph and vectorization | ACM | POPL | C | 1989 | O |
| Achieving high instruction cache performance with an optimizing compiler | ACM | ISCA | C | 1989 | S |
| Evaluating the performance of four snooping cache coherency protocols | IEEE | ICSA | C | 1989 | S |
| Scans as primitive parallel operations | IEEE | TCO | J | 1989 | S |
| Code generation using tree matching and dynamic programming | ACM | TOPLAS | J | 1989 | A, D, E, M |
| Register allocation via clique separators | ACM | PLDI | C | 1989 | A, E |
| Fast interprocedual alias analysis | ACM | POPL | C | 1989 | A, E, O, S |
| Coloring heuristics for register allocation | ACM | PLDI | C | 1989 | A, E, O |
| More iteration space tiling | ACM/IEEE | SC | C | 1989 | A, S |
| Data dependence analysis on multi-dimensional array references | ACM | ICS | C | 1989 | O, S |
| Spill code minimization techniques for optimizing compliers | ACM | PLDI | C | 1989 | A, E |
| Customization: Optimizing compiler technology for SELF, a dynamically-typed OOP language  | ACM | PLDI | C | 1989 | O, S |
| An efficient method of computing static single assignment form | ACM | POPL | C | 1989 | A, O |
| An approach to ordering optimizing transformations | ACM | PPoPP | C | 1990 | A |
| Register allocation across procedure and module boundaries | ACM | PLDI | C | 1990 | A |
| Region Scheduling: An Approach for Detecting and Redistributing Parallelism | IEEE | TSE | J | 1990 | E |
| Constructing the procedure call multigraph | IEEE | TSE | J | 1990 | O |
| On the perfect accuracy of an approximate subscript analysis test | ACM | CAN | J | 1990 | O |
| Structured dataflow analysis for arrays and its use in an optimizing compiler | Wiley | Software: Practice and Experience | J | 1990 | O |
| Compilation of Haskell array comprehensions for scientific computing | ACM | PLDI | C | 1990 | S |
| How to read floating point numbers accurately | ACM | PLDI | C | 1990 | S |
| How to print floating-point numbers accurately | ACM | PLDI | C | 1990 | S |
| Profile guided code positioning | ACM | PLDI | C | 1990 | S |
| Updating distributed variables in local computations | Wiley | SPE | J | 1990 | S |
| An interval-based approach to exhaustive and incremental interprocedural data-flow analysis | ACM | TOPLAS | J | 1990 | E, O |
| The priority-based coloring approach to register allocation | ACM | TOPLAS | J | 1990 | A, D, E, S |
| Improving register allocation for subscripted variables | ACM | PLDI | C | 1990 | A, E, M, O, S |
| Analysis of pointers and structures | ACM | PLDI | C | 1990 | A, E |
| Loop distribution with arbitrary control flow | ACM | PLDI | C | 1990 | O, S |
| Graph coloring register allocation for processors with multi-register operands | ACM | PLDI | C | 1990 | A, E |
| Register allocation via hierarchical graph coloring | ACM | PLDI | C | 1991 | A |
| Circular scheduling: a new technique to perform software pipelining | ACM | PLDI | C | 1991 | A |
| Efficient DAG construction and heuristic calculation for instruction scheduling | ACM | MICRO | W | 1991 | E |
| A composite algorithm for strength reduction and code movement optimization | Springer | ACIS | J | 1991 | E |
| Efficiently computing static single assignment form and the control dependence graph | ACM | TOPLAS | J | 1991 | M |
| Software prefetching | ACM | ASPLOS | C | 1991 | O |
| Compiling global name-space parallel loops for distributed execution | IEEE | TPDS | J | 1991 | O |
| An implementation of interprocedural bounded regular section analysis | ACM | TPDS | J | 1991 | O |
| Limits of instruction-level parallelism | ACM | ASPLOS | C | 1991 | S |
| Uniform techniques for loop optimization | ACM | ICS | C | 1991 | S |
| A data locality optimizing | ACM | PLDI | C | 1991 | A, D, M, O |
| Constant propagation with conditional branches | ACM | TOPLAS | J | 1991 | A, E, M, O, S |
| Efficient and exact data dependence analysis | ACM | PLDI | C | 1991 | A, D, O |
| Efficiently computing static single assignment | ACM | TOPLAS | J | 1991 | A, D, E, O |
| Global instruction scheduling for superscalar machines | ACM | PLDI | C | 1991 | A, D, E |
| Practical adaption of the global optimization algorithm of Morel and Renvoise | ACM | TOPLAS | J | 1991 | A, E |
| The cache performance and optimizations of blocked algorithms | ACM | ASPLOS | C | 1991 | A, D |
| A loop transformation theory and an algorithm to maximize parallelism | IEEE | TPDS | J | 1991 | O, S |
| Dataflow analysis of array and scalar references | Springer | JPP | J | 1991 | A, S |
| Optimization of array accesses by collective loop transformations | ACM | SC | C | 1991 | D, O |
| Interprocedural transformations for parallel code generation | ACM/IEEE | SC | C | 1991 | O, S |
| Practical dependence testing | ACM | PLDI | C | 1991 | A, O |
| Procedure merging with instruction caches | ACM | PLDI | C | 1991 | A, S |
| An experiment with inline substitution | Wiley | SPE | J | 1991 | E, S |
| Integrating scalar optimization and parallelization | Springer | LCPC | C | 1992 | A |
| Sharlit—a tool for building optimizers | ACM | PLDI | C | 1992 | A |
| How to analyze large programs efficiently and informatively | ACM | PLDI | C | 1992 | A |
| Compiler code transformations for superscalar-based high performance systems | IEEE | SC | C | 1992 | A |
| Engineering a simple, efficient code-generator generator  | ACM | TOPLAS (LOPLAS) | J | 1992 | D |
| Some efficient solutions to the affine scheduling problem. I. One-dimensional time | Elsevier | JPP | J | 1992 | D |
| Avoiding unconditional jumps by code replication | ACM | PLDI | C | 1992 | E |
| Rematerialization | ACM | PLDI | C | 1992 | E |
| Coloring register pairs | ACM | TOPLAS (LOPLAS) | J | 1992 | E |
| Optimizing for parallelism and data locality | ACM | SC | C | 1992 | O |
| Maximizing loop parallelism and improving data locality via loop fusion and distribution | ACM | LCPC | W | 1992 | O |
| Beyond induction variables | ACM | PLDI | C | 1992 | O |
| Efficient call graph analysis | ACM | TOPLAS (LOPLAS) | J | 1992 | O |
| A safe approximate algorithm for interprocedural aliasing | ACM | PLDI | C | 1992 | O |
| Relaxing SIMD control flow constraints using loop transformations | ACM | PLDI | C | 1992 | S |
| Unexpected side effects of inline substitution: a case study | ACM | TOPLAS (LOPLAS) | J | 1992 | S |
| Eliminating false positives using the omega test | ACM | PLDI | C | 1992 | A, D, O |
| Lazy code motion | ACM | PLDI | C | 1992 | A, D, E |
| Software support for speculative loads | ACM | ASPLOS | C | 1992 | A, E |
| A practical algorithm for exact array dependence analysis | ACM | CACM | J | 1992 | O, S |
| Array privatization for parallel execution of loops | ACM | ICS | C | 1992 | O, S |
| The power test for data dependence | IEEE | TCO | J | 1992 | A, S |
| Eliminating branches using a superoptimizer and the GNU C compiler | ACM | PLDI | C | 1992 | E, S |
| Design and evaluation of a compiler algorithm for prefetching | ACM | ASPLOS | C | 1992 | D, O |
| Dependence-based program analysis | ACM | PLDI | C | 1993 | A |
| A variation of Knoop, R{"u}thing, and Steffen's lazy code motion  | ACM | PLDI | C | 1993 | E |
| Lazy strength reduction | C&H | JPL | J | 1993 | A, E |
| Collective loop fusion for array contraction | Springer | LCPC | C | 1993 | O |
| Interprocedural constant propagation: an empirical study | ACM | TOPLAS (LOPLAS) | J | 1993 | O |
| Symbolic analysis: A basis for parallelization, optimization, and scheduling of programs  | Springer | LCPC | W | 1993 | O |
| Array-data flow analysis and its use in array privatization | ACM | POPL | C | 1993 | S |
| Automatic array alignment in data-parallel programs | ACM | POPL | C | 1993 | S |
| Global optimizations for parallelism and locality on scalable parallel machines | ACM | PLDI | C | 1993 | S |
| Instruction-Level Parallel Processing: History, Overview, and Perspective  | Springer | JSC | J | 1993 | S |
| A practical system for intermodule code optimization at link-time | C&H | JPL | J | 1993 | A |
| Loop-level parallelism in numeric and symbolic programs | IEEE | TPDS | J | 1993 | S |
| Orchestrating interactions among parallel computations | ACM | PLDI | C | 1993 | S |
| The superblock: an effective technique for VLIW and superscalar compilation | Springer | JSC | J | 1993 | S |
| Optimizing array bound checks using flow analysis | ACM | PLDI | C | 1993 | A, E |
| Register allocation with instruction scheduling | ACM | PLDI | C | 1993 | A, E |
| A methodology for procedure cloning | Elsevier | COLA (COMLAN) | J | 1993 | A, O, S |
| Efficient flow-sensitive interprocedural computation of pointer-induced aliases and side effects | ACM | POPL | C | 1993 | E, O, S |
| Automatic array privatization | Springer | LCPC | W | 1993 | O, S |
| Interprocedural modification side effect analysis with pointer aliasing | ACM | PLDI | C | 1993 | M, S |
| Branch prediction for free | ACM | PLDI | C | 1993 | A, M |
| Link-time optimization of address calculation on a 64-bit architecture | ACM | PLDI | C | 1994 | A |
| Effective partial redundancy elimination | ACM | PLDI | C | 1994 | A |
| Partial dead code elimination | ACM | PLDI | C | 1994 | A |
| A general data dependence test for dynamic, pointer-based data structures  | ACM | PLDI | C | 1994 | A |
| Instruction scheduling over regions: A framework for scheduling across basic blocks | Springer | CC | C | 1994 | A |
| Value dependence graphs: representation without taxation | ACM | POPL | C | 1994 | A |
| Zero-cost range splitting | ACM | PLDI | C | 1994 | E |
| Reducing branch costs via branch alignment | ACM | OSR | J | 1994 | E |
| Improving the ratio of memory operations to floating-point operations in loops | ACM | TOPLAS | J | 1994 | M |
| Optimizing multi-method dispatch using compressed dispatch tables | ACM | OOPSLA | C | 1994 | M |
| Improving the accuracy of static branch prediction using branch correlation | ACM | ASPLOS | C | 1994 | M |
| A compiler framework for restructuring data declarations to enhance cache and TLB effectiveness | IEEE | CASCON | C | 1994 | S |
| False sharing and spatial locality in multiprocessor caches | IEEE | TCO | J | 1994 | S |
| Reassociation and strength reduction | ACM | SCO | C | 1994 | S |
| The alignment-distribution graph | Springer | LCPC | W | 1994 | S |
| Improvements to graph coloring register allocation | ACM | TOPLAS | J | 1994 | A, E, M |
| Context-sensitive interprocedural points-to analysis in the presence of function pointers | ACM | PLDI | C | 1994 | D, E |
| Interprocedural may-alias analysis for pointers: beyond k-limiting | ACM | PLDI | C | 1994 | A, E |
| Scalar replacement in the presence of conditional control flow | Wiley | SPE | J | 1994 | E, O |
<!-- | Corpus-based static branch prediction | ACM | PLDI | C | 1995 | A |
| Resource-Constrained Software Pipelining | IEEE | TPDS | J | 1995 | A |
| Elimination of redundant array subscript range checks | ACM | PLDI | C | 1995 | A |
| Improving balanced scheduling with compiler optimizations that increase instruction-level parallelism | ACM | PLDI | C | 1995 | A |
| Accurate static branch prediction by value range propagation | ACM | PLDI | C | 1995 | A |
| Tile size selection using cache organization and data layout | ACM | PLDI | C | 1995 | E |
| Combining analyses, combining optimizations  | ACM | TOPLAS | J | 1995 | E |
| Global code motion/global value numbering | ACM | PLDI | C | 1995 | E |
| A linear time algorithm for placing φ-nodes | ACM | POPL | C | 1995 | O |
| Points-to analysis in linear time | ACM | POPL | C | 1996 | D |
| Aggressive loop unrolling in a retargetable, optimizing compiler  | Springer | CC | C | 1996 | E |
| Iterated register coalescing | ACM | TOPLAS | J | 1996 | E, M |
| Improving data locality with loop transformations | ACM | TOPLAS | J | 1996 | E, O |
| Maximizing parallelism and minimizing synchronization with affine transforms | ACM | POPL | C | 1997 | D |
| Fast and accurate flow-insensitive points-to analysiS | ACM | PLDI | C | 1997 | E |
| Register promotion in C programs | ACM | PLDI | C | 1997 | E |
| Efficient procedure mapping using cache line coloring | ACM | PLDI | C | 1997 | E |
| Spill code minimization via interference region spilling | ACM | PLDI | C | 1997 | E |
| Aggressive inlining | ACM | PLDI | C | 1997 | E |
| Optimal weighted loop fusion for parallel programs | ACM | SPAA | C | 1997 | O |
| Near-optimal intraprocedural branch alignment | ACM | PLDI | C | 1997 | E, M |
| Value numbering | Wiley | SPE | J | 1997 | A, E |
| A new algorithm for scalar register promotion based on SSA form | ACM | PLDI | C | 1998 | E |
| Register promotion by sparse partial redundancy elimination of loads and stores | ACM | PLDI | C | 1998 | E |
| Cost-optimal code motion | ACM | TOPLAS | J | 1998 | E |
| International Conference on Compiler Construction | Springer | CC | C | 1998 | E |
| Complete removal of redundant expressions | ACM | PLDI | C | 1998 | E |
| Using integer sets for data-parallel program analysis and optimization | ACM | PLDI | C | 1998 | O |
| Bidirectional data flow analysis: myths and reality | ACM | SIGPLAN Notices | J | 1999 | A |
| An affine partitioning algorithm to maximize parallelism and minimize communication | ACM | SC | C | 1999 | D |
| Interprocedural pointer alias analysis | ACM | TOPLAS | J | 1999 | E |
| Dominators in linear time | SIAM | SICOMP | J | 1999 | E |
| Scalable context-sensitive flow analysis using instantiation constraints | ACM | PLDI | C | 2000 | D |
| Unification-based pointer analysis with directional assignments | ACM | PLDI | C | 2000 | E |
| Fast greedy weighted fusion | ACM | ICS | C | 2000 | O |
| Blocking and array contraction across arbitrarily nested loops using affine partitioning | ACM | PPoPP | C | 2001 | D |
| Ultra-fast Aliasing Analysis using CLA: A Million Lines of C Code in a Second | ACM | PLDI | C | 2001 | D |
| A simple, fast dominance algorithm  | Wiley | SPE | J | 2001 | E, O |
| Operator Strength Reduction | ACM | TOPLAS | J | 2001 | A, E |
| Symbolic pointer analysis | IEEE | ICCAD | C | 2002 | D |
| Cloning-based context-sensitive pointer alias analysis using binary decision diagrams | ACM | PLDI | C | 2004 | D |
| Symbolic pointer analysis Revisited | ACM | PLDI | C | 2004 | D |
| A generalized algorithm for graph-coloring register allocation | ACM | PLDI | C | 2004 | E |
| Optimistic register coalescing | ACM | TOPLAS | J | 2004 | E |
| Context-sensitive program analysis as database queries | ACM | PODS | C | 2005 | D |
| Improving software security with a C pointer analysis | IEEE | ICSE | C | 2005 | D |
| Register allocation via coloring of chordal graphs | Springer | APLAS | C | 2005 | E |
| Polynomial time graph coloring register allocation | ACM | PLDI | C | 2005 | E |
| Optimal register allocation for SSA-form programs in polynomial time | Elsevier | IPL | J | 2006 | E | -->