# RISC-V Softcore

A 5-stage pipelined RV32I processor implemented in SystemVerilog on an Arty A7-35T FPGA.

## Project Structure
- `rtl/` — SystemVerilog source files (ALU, register file, decoder, pipeline stages)
- `tb/` — Testbenches for each module
- `sw/` — Assembly and C software (test programs, benchmarks)
- `docs/` — Architecture documentation and diagrams

## Toolchain
- Simulator: Icarus Verilog (`iverilog -g2012`)
- Waveform viewer: GTKWave
- RISC-V GCC: xPack `riscv-none-elf-gcc`
- FPGA: Vivado 2025.2 (Arty A7-35T, XC7A35T)

## Status
- [ ] Phase 1 — Toolchain setup
- [ ] Phase 2 — Single-cycle core
- [ ] Phase 3 — 5-stage pipeline
- [ ] Phase 4 — SoC integration
- [ ] Phase 5 — Polish and stretch goals