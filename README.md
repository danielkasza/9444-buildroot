# Buildroot 2020.02 for 9444 CPU

The [9444 CPU](https://github.com/danielkasza/9444) is a tiny RISC-V (RV64IMA) compatible experimental CPU.

Kernel patches are included for enabling peripherals used on FPGAS, and a kernel configuration is provided that should
work on FPGAs or on the simulator.

Buildroot is pre-configured (see `.config`) to build the patched system, so you just have to run `make`.
