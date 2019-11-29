std-script
==========

Primative Types
-----------------------------------
array:
  An array

bool
  The boolean type

rune
  A single ``i32`` that holds a unicode encoded character

float : size where size: 32 || 64
  The <size>bit floating point type

fn : return_type : ...argument_types
  A function signature

int : size where size: has_trait(num) && size > 0
  The <size>bit integer type

ref
  ``todo: explain``

tuple
  ``todo: explain``
  
uint : size where size: has_trait(num) && size > 0
  The <size>bit unsigned integer tye

str
  Unicode string slices
  ``todo: explain how this works``

string
  A UTF-8 growable string
  
never
  A type used for exhaustiveness checks that will error at pre-compilation if it's found to be used

Modules `/modules/:type`
- any `// todo: explain`
- array
- cmp `// todo: explain`
- env
- error
- fmt
- ffi `// remember: wasm, js`
- io
- net
- num
- mem `// todo: explain`
- option
- outside `//todo: explan, rename`
- panic
- result
- slice 
- task
- threads
- time
- vfs `// todo: explain`
- wasm

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












