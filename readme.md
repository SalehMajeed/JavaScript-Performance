# 3 Different Types of Perfomance

1. Network Load Performance.
2. JavaScript(Parsing/Compiling) Perfomance.
3. Rendering Perfomance.

## RAIL -> Response Animation Idle Load

JS Commonly use JIT(Just In Time) Compiler.
V8 Ignition Compiler In Chrome.
Turbo Fan Compiler.

# Parsing

AS slow as 1MB/s on mobile.
Parsing has 2 phases ->

1. Eager.
2. Lazy.

use () outside function for eager parsing.

Parse -> Abstract Syntax Tree.

# Compiler ->

1. Speculative Optimization.
2. Hidden Classes for dynamic lookups.
3. Function Inlining.

node --trace-opt filename.js | grep add
ndoe --trace-opt --trace--deopt filename.js | grep
node --allow-natives-syntax filename.js
node --trace-turbo-inlining filename.js

monomorphism
polymorphism
megamorphism

hidden class

style calculation ->

1. which rules apply to which element.
2. end result of an element with multiple rules.

layout and reflow
change in geometry -> reflow -> blocking operation.
force synchronous layout -> layout thrashing.
fastdom -> measure and mutate

thread ->

1. UI thread
2. The Renderer thread
3. The Compositor thread
