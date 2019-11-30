std-script
==========

Primative Types
---------------
array
  An array

bool
  The boolean type

rune
  A single ``i32`` that holds a unicode encoded character

float : size where size: 32 || 64
  The <size>bit floating point type

f32 : where self impl float<32>
  The 32bit floating poitn type

f64 : where self impl float<64>
  The 64bit floating poitn type

fn : return_type : ...argument_types
  A function signature

int : size where size: has_trait(num) && size > 0
  The <size>bit integer type
  
``todo: write down i<size> for 8, 16, 32, 64, and 128``

ref
  ``todo: explain``

tuple
  ``todo: explain``
  
uint : size where size: has_trait(num) && size > 0
  The <size>bit unsigned integer tye

``todo: write down u<size> for 8, 16, 32, 64, and 128``

str
  Unicode string slices
  ``todo: explain how this works``

string
  A UTF-8 growable string
  
never
  A type used for exhaustiveness checks that will error at pre-compilation if it's found to be used

Modules
-------
any
  ``todo: explain``

array
  Implementations for generic arrays

cmp
  Functionality for ordering and comparing

default
  The Default trait for types which may have meaningful default values

env
  Inspection and manipulation of the process's environment

error
  Traits for working with Errors
  
ffi
  Utilities related to FFI bindings
  For example importing or exporting from wasm

fmt
  Utilities for formatting and printing ``Strings``

io
  Traits, helpers, and type definitions for core I/O functionality

net
  Networking primitives for TCP/UDP communication

num
  Additional functionality for numerics
  
mem
  Basic functions for dealing with memory

option
  Optional values
  
outside
  ``todo: explain, rename``

os
  OS information and metadata

panic
  Panic support in the standard library

path
  Cross-platform path manipulation

result
  Error handling with the Result type

rune
  A rune type

task
  Types and Traits for working with asynchronous tasks

threads  
  ``todo: explain``

time
  Temporal quantification

vfs
  Cross-platform virtual file system

wasm
  Tools and utilities for working with wasm

Keywords `/keywords/:keyword`
- as
- async `// warn: needed but unknown how implement`
- break
- const
- continue
- else
- enum
- export
- false
- fn
- for
- if
- import
- impl
- let
- match
- ret `// note: maybe return`
- self
- static `// todo: explain, node: maybe not like the rust static`
- struct 
- super `// todo: explain`
- trait
- true
- type
- use
- where `// todo: explain`












