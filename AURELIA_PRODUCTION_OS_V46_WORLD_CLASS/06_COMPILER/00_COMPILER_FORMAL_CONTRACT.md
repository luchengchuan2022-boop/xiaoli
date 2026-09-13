# COMPILER FORMAL CONTRACT

Compiler stages are pure where declared pure and stateful only where explicitly declared.

Each stage declares:
input schema
output schema
semantic guarantees
allowed transformations
loss budget
failure modes
evidence
compiler version

A stage may not silently perform the authority work of another stage.
