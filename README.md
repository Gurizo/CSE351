# CSE351

Course Goals
This course will develop your sense of what really happens when software runs at several levels of abstraction, including the hardware architecture level, the assembly level, the C programming level, and the Java programming level. The core around which the course is built is C, assembly, and low-level data representation, but this is connected to higher levels (roughly how basic Java could be implemented), lower levels (the general structure of a processor), and the role of the operating system (but not how the operating system is implemented).

We also want to provide room for exploring the design goals of the abstractions on which computing is built, both explicit and implicit. These goals can, unintentionally or intentionally, make it difficult for everyone to benefit equally from computing. Thus, this course aims to not only pull back the curtain on how computing is structured right now, but also to empower you to be a force of change in ensuring that it works better for everyone. Knowing why abstractions exist alongside how they work is critically important in understanding how to improve them.

Course Themes
The course has three principal themes:

Representation: How different data types (from simple integers to arrays of data structures) are represented in memory, how instructions are encoded, and how memory addresses (pointers) are generated and used to create complex structures.
Translation: How high-level languages are translated into the basic instructions embodied in process hardware with a particular focus on C and Java.
Control Flow: How computers organize the order of their computations, keep track of where they are in large programs, and provide the illusion of multiple processes executing in parallel
History and Society: How the principles that computers are built upon were influenced by the societal context of the historical periods in which they were designed and, in turn, how computers influence society in ways far beyond pure computational power.

Course Objectives
At the end of this course, students should be able to:

Describe the multi-step process by which a high-level program becomes a stream of instructions executed by a processor;
Describe the basic organization of the memory hierarchy and the effect of its parameters on system performance;
Trace the execution of assembly code (x86-64), map the assembly to high-level language constructs, and write simple pieces of assembly programs;
Write C code using pointers to create and manipulate complex data structures;
Write (or rewrite) code to be take advantage of the computer execution model to improve execution efficiency;
Debug small-ish C and assembly programs using GDB;
Explain the role of an operating system;
Describe fundamental differences between Java and C;
Identify the design priorities present in technical systems, both explicit and implicit, and how they relate to historical context.
Course Topics
Approximate list of topics:

Memory and data representation
Number representation for integers and floats
Machine code and the C programming language
x86-64 assembly language
Procedures and stacks
Arrays and other data structures
Memory and caches
Operating system process model
Virtual memory
Memory allocation
Implementation of high-level languages (e.g., Java)
Note that even more important than the topics at various levels of abstraction is the connection between them: students should get an informal sense of how Java could be translated to C, C to assembly, and assembly to binary.
