std-script
==========

Primative Types
---------------
array : type : length
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

fn : return_type : arguments where arguments: has_trait(tuple)
  A function signature

int : size where size: has_trait(num) && size > 0
  The <size>bit integer type
  
``todo: write down i<size> for 8, 16, 32, 64, and 128``

ref
  ``todo: explain``

tuple : ...tuple_types
  A finite heterogeneous sequence, ``(T, U, ..)``
  
uint : size where size: has_trait(num) && size > 0
  The <size>bit unsigned integer tye

``todo: write down u<size> for 8, 16, 32, 64, and 128``

str : length
  ``todo: explain how this works with slices``
  
  ``note: slices are not a primitive type right now, maybe they should be``

  Unicode string slices

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

iter
  Composable external iteration

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

Keywords
--------

as
  Cast between types, or rename an import
  
async
  ``warn: needed but unknown how to implement``
  
  Used for asyncronous data

break
  ``todo: rethink how loops can be conceptulized and if break is needed``

  Exit early from a loop
  
const
  Compile-time constants and deterministic functions

continue
  ``todo: rethink how loops can be conceptulized and if continue is needed``

  Skip to the next iteration of a loop

else
  What to do when an if condition does not hold
  
enum
  A type that can be any one of several variants

export
  Export an item to be used by others
  
false
  A value of type ``bool`` representing logical **false**
  
fn
  A function or function signature
  
for
  Iterate over certain types of data, or in impl implementations

if
  Evaluate a block if a condition holds

import
  Import exported items from a module

impl
  Implement some functionality for a type

let
  Bind a value to a variable

match
  Control flow based on pattern matching

ref
  Create and hold a reference to a value in memory

ret
  ``note: mayble return``
  
  Return a value from a function
  
self
  The receiver of a method, or the current module
  
static
  ``todo: explain``
  
  ``note: not like the rust static``

struct
  A type that is composed of other types

super
  ``note: this differs from javascript``
  
  ``note: maybe parent would be a better name``
  
  The parent of the current module

trait
  A common interface for a class of types
  
true
  A value of type ``bool`` representing logical **true** 

type
  Define an alias for an existing type

use
  Import or rename items from other modules to use in the current module

where
  Add constraints that must be upheld to use an item











