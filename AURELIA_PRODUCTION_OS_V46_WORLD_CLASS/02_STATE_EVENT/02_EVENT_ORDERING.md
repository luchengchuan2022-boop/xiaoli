# EVENT ORDERING

The system distinguishes:
- causal order
- logical sequence
- wall-clock time
- production order
- narrative chronology

Do not use timestamps as a substitute for causality.
Out-of-order delivery must be detectable.
A replay must reproduce the same committed semantic result.
