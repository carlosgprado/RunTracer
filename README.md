RunTrace - Prospector components (part of COSEINC's BugMine)
============================================================

This fork contains changes to make the tools work under Linux. Currently the following changes are implemented:

*   Updated Makefiles
*   Updated ccovtrace

RunTracers
----------

### ccovtrace

Code coverage tracer.

### runtrace

Complex runtime trace analysis tool with more options that necessary.

### exceptiondump

RunTracer to dump the last basic block executed before a first chance execption (windows only).

### redflag
Heap corruption trace tool, logs writes to areas outside allocated heap chunks (windows only).

More information
----------------

For more information please check the original repo at https://github.com/grugq/RunTracer

