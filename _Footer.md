**C++ compilers**

There are many compilers for C+++and theses are some of them..

1
C++Builder
Auth:	Embarcadero (CodeGear)

2
Turbo C++ Explorer	
Auth : Embarcadero (CodeGear)

3
C++ Compiler
Auth: 	Embarcadero (CodeGear)

4
CINT	
Auth : CERN

5
Borland C++	
Auth :Borland (CodeGear)

6
Turbo C++ for DOS	
Auth: Borland (CodeGear)

7
Clang	
Auth :LLVM Project	

8
CodeWarrior	
Auth: Metrowerks	

9
Comeau C/C++
Auth:	Comeau Computing

10
CoSy compiler development system	
Auth: ACE Associated Compiler Experts

11	
Digital Mars	
Auth:Digital Mars	

12
EDGE ARM C/C++	
Auth:Mentor Graphics	

13
Edison Design Group
Auth:	Edison Design Group	

14
GCC	
Auth:GNU Project

15
HP aC++	
Auth:Hewlett-Packard

16
IAR C/C++ Compilers	
Auth: IAR Systems 

17
Intel C++ Compiler	
Auth: Intel	

18
KAI C++ Compiler	
Auth:Kuck & Associates, Inc. (bought by Intel)	

19
Microtec
Auth:	Mentor Graphics

20
MULTI
Auth:	Green Hills Software

21
Open Watcom
Auth:	Sybase

22
Open64
Auth:	HP, AMD, Tsinghua University and others	

23
PathScale	
Auth :PathScale and others

24
PGCPP	
Auth:The Portland Group	
 
25
ProDev WorkShop	
Auth: Silicon Graphics

26
RealView C/C++ Compiler (armcc)	
Auth: Keil (ARM Limited)	

27
Salford C++ Compiler	
Auth; Silverfrost	

28
SAS/C C++	
Auth:SAS Institute

29
SCORE C++ (tpp)
Auth:	DDC-I	

30
Systems/C,C++
Auth:	Dignus	

31
Solaris Studio	
Auth:Oracle	

32
Solaris Studio Express
Auth:	Oracle	

33
TenDRA	
Auth:TenDRA Project

34
VectorC	
Auth:Codeplay	

35
Visual C++	
Auth:Microsoft	

36
VisualAge C++	
Auth: IBM	

37
XL C/C++
Auth:	IBM	

38
Wind River (Diab) Compiler
Auth:	Wind Rivers systems
.

**What is the difference between the compilers in C++ programming?**

The differences between compilers in C++ are very large in number .Few of them are  :
Optimization - routines are completely different. Clang/LLVm or Visual C++ are good for link-time optimization.
Economy - some are available for free : GCC, Clang/LLVM, Visual Studio Express, etc.
Back-end Tools - are completely different Visual Studio uses masm , link , cl and GCC uses gcc , g++ , cc1 , cc1plus and binutils .
Exception Handling - Visual Studio is the "best" in terms of exception handling.
Compiler which is mostly used on majority of online judges is the GCC.
GCC means the GNU Compiler Collection, it is the front end for a collection of compilers and linkers. When compiling C++ it will usually call g++.
As for g++ vs VC++, they are completely different compilers so there are a ton of differences.
For example they will optimize code in different ways, they may have minor syntactical differences based on not following the standard correctly, different libraries, different headers, different implementations, etc...
g++ can be used to compile projects on various different platforms, whereas VC++ is meant to only compile programs for the Windows platform.

**..**
**What are the different c++ standards?**

The C++ standard consists of two parts: the core language and the C++ Standard Library. C++ programmers expect the latter on every major implementation of C++; it includes vectors, lists, maps, algorithms (find, for_each, binary_search, random_shuffle, etc.), sets, queues, stacks, arrays, tuples, input/output facilities (iostream, for reading from and writing to the console and files), smart pointers for automatic memory management, regular expression support, multi-threading library, atomics support (allowing a variable to be read or written to be at most one thread at a time without any external synchronisation), time utilities (measurement, getting current time, etc.), a system for converting error reporting that doesn't use C++ exceptions into C++ exceptions, a random number generator and a slightly modified version of the C standard library (to make it comply with the C++ type system).

A large part of the C++ library is based on the Standard Template Library (STL). Useful tools provided by the STL include containers as the collections of objects (such as vectors and lists), iterators that provide array-like access to containers, and algorithms that perform operations such as searching and sorting.

Furthermore, (multi)maps (associative arrays) and (multi)sets are provided, all of which export compatible interfaces. Therefore, using templates it is possible to write generic algorithms that work with any container or on any sequence defined by iterators. As in C, the features of the library are accessed by using the #include directive to include a standard header. C++ provides 105 standard headers, of which 27 are deprecated.

The standard incorporates the STL that was originally designed by Alexander Stepanov, who experimented with generic algorithms and containers for many years. When he started with C++, he finally found a language where it was possible to create generic algorithms (e.g., STL sort) that perform even better than, for example, the C standard library qsort, thanks to C++ features like using inlining and compile-time binding instead of function pointers. The standard does not refer to it as "STL", as it is merely a part of the standard library, but the term is still widely used to distinguish it from the rest of the standard library (input/output streams, internationalization, diagnostics, the C library subset, etc.).

Most C++ compilers, and all major ones, provide a standards conforming implementation of the C++ standard library.
