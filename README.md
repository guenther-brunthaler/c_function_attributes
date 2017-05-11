C Function Attributes
=====================

"CFA" stands for "C Function Attributes" and is a set of
conventions for naming C functions and their parameters,
effectively annotating them.

This set of conventions attaches semantic meaning in the form of
attributes to the names, for which the C language does not
provide any means of declaring such attributes.

The documentation of those semantic attributes can then be
removed from the documentation of the individual functions or
their parameters, and can be replaced by a single copy of the CFA
conventions which applies to all documented functions at once.

CFA is therefore a particular method for manual "name-mangling"
by humans to be used in C source code, rather than automatic
name-mangling at the linker-level performed by a compiler (such
as a C++ compiler).
