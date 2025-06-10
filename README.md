# ARM6Support
ARM610/710 support module for RISC OS 3.1.

This is intended for Archimedes machines with experimental ARM610/710 CPU board.

# Version history
* 0.01 - Basic MMU initialisation (identity mapping for first 64 MB)
* 0.02 - Add Arm710 support
* 0.03 - Correct control register number (1 not 0)
* 0.04 - Correct page table alignment handling.  Enable cache for first 16MB.
