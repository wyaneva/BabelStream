---
layout: page
title: Documentation
permalink: /docs/
---

## Compiling the benchmark
Build instructions are available in the [README](https://github.com/UoB-HPC/BabelStream/blob/master/README.md).

## Running the benchmark
To see the available options when running the benchmark, execute `./<model>-stream --help`

In summary:

* `--help` (`-h`) Lists these options

* `--list` List the available OpenCL/CUDA devices

* `--device INDEX` Select the device to run the benchmark on

* `--arraysize SIZE` (`-s`) Use SIZE elements in array instead of the default 50 million

* `--numtimes NUM` (`-n`) Run the test NUM times. NUM >= 2 as first result is ignored for warm-up

* `--float` Use single precision floating point data types rather than double precision


