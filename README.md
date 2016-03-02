# VariantType

A C++ union based variant type class implemented with compile time
polymorphism for EECS 281 @ The University of Michigan - Ann Arbor

### Building
This project relies on several features of C++14 that are incompatible with
previous versions of C++ so this must be compiled with C++14.  The header
`VariantType.hpp` contains all the relevant function declarations and the
implementations are in the other .cpp files.  To run the unit tests type in 
``make test``
