## io
Common snippets for I/O operations.

## Current contents

* for-each-test-case.hpp : minimalistic main performing T iterations (T read from cin)

* io_manipulators.h
  * __as_line__ : reads a line to a string, with a stream-like syntax

* read-vector-cin.hpp
  * __read_vector_from_stdin__ : reads an int vector of size n from cin
  * __read_vector_from_stdin__ : reads an int vector and its size from cin
  * __read_vector_from_stdin__ : reads a T vector of size n from cin
  * __read_vector_from_stdin__ : reads a T vector and its size from cin

* tuple_from_istream.h
  * __tuple_from__ : reads a tuple from an istream
  * __tuple_from__ : reads a tuple from cin

## This is NOT a library
.hpp files in this folder are not intended to be included somewhere. They contain snippets, easy to copy-and-paste into the challenge editor.

__However__ .h files can be used as header-only.
