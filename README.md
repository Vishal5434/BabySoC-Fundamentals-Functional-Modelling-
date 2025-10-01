# Introduction
VSDbabySoC is a compact SoC design that includes a RISCV-based processor named RVMYTH, along with analog components like a PLL (Phase-Locked Loop) and DAC (Digital-to-Analog Converter). It serves as a practical platform to explore and simulate the integration of digital and analog circuits in a modern chip design.
# Pre synthesis simulation
Pre-synthesis simulation of BabySoC involves verifying the RTL code behavior before synthesizing it into hardware. It checks the functional correctness of the design using test benches without considering gate-level details, ensuring the logic functions as intended. This step helps catch errors early in the design flow before moving to synthesis and physical implementation.

```
cd VSDBabySoc
make pre_synth_sim
```
This command lines generates vcd file of pre_synth_sim from the  makefile present in the directory VSDBabySoC

```
gtkwave output/pre_synth_sim/pre_synth_sim.vcd

GTKwave Analyzer v3.3.116 (w)1999-2000 BSI

[0] start time
[84999000] end time
```
