---
layout: home 
---

## Run rules

In order to generate a valid GPU-STREAM result, you should obey the following rules:

1. The array size must be large enough that increasing the array size does not drastically change the reported bandwidth. If you satisfy this you will no longer be affected by any cache effects.

2. Each kernel should take a few milliseconds. The resolution of the host timer is probably in milliseconds so each kernel execution should be longer than the timer resolution. Increase the array size if the kernels are too fast. You are unlikely to break this rule if you follow rule 1.

If you see a single GPU-STREAM result, expect this to be the largest bandwidth reported by the benchmark unless stated otherwise.


