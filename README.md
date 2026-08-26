# awesome-opensource-hardware with stars

A curated list of awesome open source hardware tools, generators, and reusable designs.

* Categorized
* Alphabetical (per category)
* Requirements
  * link should be to source code repository
  * open source projects only
  * working projects only (not WIP/rusty)
* One tag line sentence per project

# Table of Contents

## PDKs

* [Manufacturable PDKs](#manufacturable-pdks)
* [Virtual PDKs](#virtual-pdks)

## Compilers

* [Build systems](#build-systems)
* [Circuit compilers](#circuit-compilers)
* [FPGA compilers](#fpga-compilers)
* [Layout compilers](#layout-compilers)

## Project

* [Documentation](#documentation)

## Design and Verification Tools

* [Benchmarks](#benchmarks)
* [Board design](#board-design)
* [Digital design](#digital-design)
* [FPGA design](#fpga-design)
* [Formal verification](#formal-verification)
* [Linters](#linters)
* [Register design](#register-design)
* [Schematics](#scehamtics)
* [Simulators](#simulators)
* [Verification frameworks](#verification-frameworks)
* [Physics](#physics)
* [Waveform Viewers](#waveform-viewers)

## Designs & Generators

* [Accelerators](#accelerators)
* [AIB](#aib)
* [AXI](#axi)
* [Analog circuits](#analog-circuits)
* [Chip packaging](#chip-packages)
* [Boards](#board-designs)
* [Connectivity](#connectivity)
* [CPUs](#cpus)
* [FPGA architectures](#fpga-architectures)
* [Libraries](#libraries)
* [Memory](#memory)
* [Systems](#systems)

## Education

* [Analog design](#analog-design)
* [ASIC design](#asic-design)
* [Digital design](#digital-design)
* [FPGA design](#fpga-design)

# PDKs

## Manufacturable PDKs

* [sky130](https://github.com/google/skywater-pdk) ⭐ 3,669 | 🐛 199 | 🌐 Python | 📅 2026-07-21
  * Skywater 130nm CMOS PDK
* [sg13g2](https://github.com/IHP-GmbH/IHP-Open-PDK) ⭐ 806 | 🐛 245 | 🌐 HTML | 📅 2026-08-26
  * IHP 130nm BiCMOS PDK
* [gf180](https://github.com/google/gf180mcu-pdk) ⭐ 521 | 🐛 24 | 🌐 Makefile | 📅 2023-05-31
  * GlobalFoundries 180nm CMOS PDK

## Virtual PDKs

* [freepdk45](https://github.com/siliconcompiler/siliconcompiler/tree/main/third_party/pdks/virtual/freepdk45) ⭐ 1,202 | 🐛 34 | 🌐 Python | 📅 2026-08-26
  * Predictive 45nm PDK
* [asap7](https://github.com/The-OpenROAD-Project/asap7) ⭐ 333 | 🐛 31 | 📅 2025-03-12
  * Predictive 7nm PDK
* [probe3.0](https://github.com/ABKGroup/PROBE3.0) ⭐ 59 | 🐛 7 | 🌐 Perl | 📅 2024-04-08
  * Process/design DTCO path finding technology

# AI

* [AnalogCoder](https://github.com/laiyao1/AnalogCoder) ⭐ 193 | 🐛 0 | 🌐 Python | 📅 2026-02-22
* [Masala-CHAI](https://github.com/jitendra-bhandari/Masala-CHAI) ⭐ 125 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-09
* [hagent](https://github.com/masc-ucsc/hagent) ⭐ 32 | 🐛 10 | 🌐 Python | 📅 2026-08-25
* Analog Circuit Design via Training-Free Code Generation
* hardware agent
* Large-Scale SPICE Netlist Dataset for Analog Circuits

# Compilers

## Build Systems

* [chipyard](https://github.com/ucb-bar/chipyard) ⭐ 2,366 | 🐛 200 | 🌐 Scala | 📅 2026-08-19
  * Agile RISC-V SoC Design Framework.
* [fusesoc](https://github.com/olofk/fusesoc) ⭐ 1,453 | 🐛 153 | 🌐 Python | 📅 2026-08-24
  * Package manager and build abstraction tool for FPGA/ASIC development.
* [siliconcompiler](https://github.com/siliconcompiler/siliconcompiler) ⭐ 1,202 | 🐛 34 | 🌐 Python | 📅 2026-08-26
  * Python based build system and package manager for hardware.
* [edalize](https://github.com/olofk/edalize) ⭐ 789 | 🐛 157 | 🌐 Python | 📅 2026-08-12
  * Abstraction library for interfacing EDA tools.
* [bender](https://github.com/pulp-platform/bender) ⭐ 387 | 🐛 52 | 🌐 Rust | 📅 2026-08-20
  * Dependency management tool for hardware projects.
* [hammer](https://github.com/ucb-bar/hammer) ⭐ 324 | 🐛 229 | 🌐 Python | 📅 2026-08-07
  * Agile physical design component part of UC Berkeley Chipyard framework.
* [mflowgen](https://github.com/mflowgen/mflowgen) ⭐ 294 | 🐛 12 | 🌐 Python | 📅 2026-06-18
  * Build-system generator for ASIC and FPGA design-space exploration.
* [bazelhdl](https://github.com/hdl/bazel_rules_hdl) ⭐ 167 | 🐛 82 | 🌐 Starlark | 📅 2026-08-25
  * Bazel based hdl build system
* [orbit](https://github.com/chaseruskin/orbit) ⭐ 67 | 🐛 2 | 🌐 Rust | 📅 2026-07-29
  * Package manager and build tool for HDLs
* [cocoon](https://github.com/pku-dasys/cocoon) ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2023-07-20
  * Infrastructure for integrated EDA
* [SoCMake](https://github.com/HEP-SoC/SoCMake) ⭐ 44 | 🐛 22 | 🌐 CMake | 📅 2026-08-17
  * Hardware and software build system and package manager based on CMake
* [flgen](https://github.com/pezy-computing/flgen) ⭐ 21 | 🐛 3 | 🌐 Ruby | 📅 2026-08-11
  * Generate a filelist for EDA tools
* [hbs](https://github.com/m-kru/hbs) ⭐ 12 | 🐛 1 | 🌐 Tcl | 📅 2026-07-26
  * Tcl-based, minimal common abstraction build system for hardware design projects.
* [hwtbuildsystem](https://github.com/Nic30/hwtBuildsystem) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-06-09
  * Library of utils for interaction with the vendor tools.

## Circuit Compilers

* [halide](https://github.com/halide/Halide) ⭐ 6,590 | 🐛 769 | 🌐 C++ | 📅 2026-08-26
  * Language for fast, portable data-parallel computation
* [chisel](https://github.com/chipsalliance/chisel3) ⭐ 4,763 | 🐛 511 | 🌐 Scala | 📅 2026-08-23
  * Scala based hardware description language
* [yosys](https://github.com/YosysHQ/yosys) ⭐ 4,704 | 🐛 560 | 🌐 C++ | 📅 2026-08-26
  * Yosys Open SYnthesis Suite
* [circt](https://github.com/llvm/circt) ⭐ 2,226 | 🐛 1,128 | 🌐 C++ | 📅 2026-08-26
  * Circuit IR Compilers and Tools
* [amaranth](https://github.com/amaranth-lang/amaranth) ⭐ 2,074 | 🐛 130 | 🌐 Python | 📅 2026-08-23
  * Python based hardware design framework
* [spinalhdl](https://github.com/SpinalHDL/SpinalHDL) ⭐ 2,031 | 🐛 172 | 🌐 Scala | 📅 2026-08-12
  * Scala based HDL
* [verible](https://github.com/chipsalliance/verible) ⭐ 1,918 | 🐛 615 | 🌐 C++ | 📅 2026-08-16
  * SystemVerilog developer tools, including a parser, style-linter, and formatter
* [xls](https://github.com/google/xls) ⭐ 1,834 | 🐛 1,127 | 🌐 C++ | 📅 2026-08-26
  * Google framework for hardware synthesis
* [skidl](https://github.com/devbisme/skidl) ⭐ 1,636 | 🐛 46 | 🌐 Python | 📅 2026-08-20
  * SKiDL is a module that extends Python with the ability to design electronic circuits
* [clash](https://github.com/clash-lang/clash-compiler) ⭐ 1,606 | 🐛 406 | 🌐 Haskell | 📅 2026-08-25
  * Haskell to VHDL/Verilog/SystemVerilog compiler
* [silice](https://github.com/sylefeb/Silice) ⭐ 1,430 | 🐛 71 | 🌐 C++ | 📅 2026-08-23
  * Language that simplifies prototyping and writing algorithms on FPGA architectures
* [abc](https://github.com/berkeley-abc/abc) ⭐ 1,215 | 🐛 229 | 🌐 C | 📅 2026-08-25
  * System for sequential logic synthesis and formal verification
* [bsc](https://github.com/B-Lang-org/bsc) ⭐ 1,141 | 🐛 336 | 🌐 Haskell | 📅 2026-08-24
  * Compiler, simulator, and tools for the Bluespec Hardware Description Language
* [myhdl](https://github.com/myhdl/myhdl) ⭐ 1,126 | 🐛 131 | 🌐 Python | 📅 2025-04-10
  * Python based hardware description and verification language
* [slang](https://github.com/MikePopoloski/slang) ⭐ 1,122 | 🐛 26 | 🌐 C++ | 📅 2026-08-26
  * Library for lexing, parsing, type checking, and elaborating SystemVerilog code
* [finn](https://github.com/Xilinx/finn) ⭐ 1,044 | 🐛 113 | 🌐 Python | 📅 2026-08-26
  * Dataflow compiler for QNN inference
* [veryl](https://github.com/veryl-lang/veryl) ⭐ 1,026 | 🐛 145 | 🌐 Rust | 📅 2026-08-26
  * Modern Hardware Description Language based on Rust/SV
* [pyverilog](https://github.com/PyHDI/Pyverilog) ⭐ 798 | 🐛 82 | 🌐 Python | 📅 2024-06-15
  * Python design toolkit for Verilog HDL
* [sv2v](https://github.com/zachjs/sv2v) ⭐ 748 | 🐛 38 | 🌐 Haskell | 📅 2026-08-18
  * SystemVerilog to Verilog conversion
* [firrtl](https://github.com/chipsalliance/firrtl) ⚠️ Archived
  * Intermediate Representation for RTL
* [pipelinec](https://github.com/JulianKemmerer/PipelineC) ⭐ 744 | 🐛 56 | 🌐 Python | 📅 2026-08-26
  * C-like hardware description language (HDL) with automatic pipelining
* [systemc](https://github.com/accellera-official/systemc) ⭐ 687 | 🐛 43 | 🌐 C++ | 📅 2026-08-25
  * SystemC system design and verification language that spans hardware and software
* [scip](https://github.com/scipopt/scip) ⭐ 640 | 🐛 27 | 🌐 C | 📅 2026-08-24
  * Solving Constraint Integer Problems
* [calyx](https://github.com/cucapra/calyx) ⭐ 612 | 🐛 175 | 🌐 Rust | 📅 2026-08-19
  * Intermediate language and compilers that generate custom hardware accelerators
* [aihwkit](https://github.com/IBM/aihwkit) ⭐ 503 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2026-08-13
  * IBM Analog Hardware Acceleration Kit
* [rohd](https://github.com/intel/rohd) ⭐ 488 | 🐛 138 | 🌐 Dart | 📅 2026-08-25
  * Dart based framework for describing and verifying hardware
* [sv-parser](https://github.com/dalance/sv-parser) ⭐ 481 | 🐛 40 | 🌐 Rust | 📅 2026-06-10
  * SystemVerilog IEEE 1800-2017 parser library
* [surelog](https://github.com/chipsalliance/Surelog) ⭐ 472 | 🐛 47 | 🌐 C++ | 📅 2026-08-26
  * SystemVerilog IEEE 2017 Pre-processor, Parser, Elaborator, UHDM Compiler
* [pymtl3](https://github.com/pymtl/pymtl3) ⭐ 465 | 🐛 12 | 🌐 Python | 📅 2026-07-02
  * Python hardware generation, simulation, and verification framework
* [llhd](https://github.com/fabianschuiki/llhd) ⭐ 437 | 🐛 39 | 🌐 Rust | 📅 2022-04-20
  * Intermediate representation for digital circuit descriptions
* [ghdl-yosys-plugin](https://github.com/ghdl/ghdl-yosys-plugin) ⭐ 367 | 🐛 38 | 🌐 VHDL | 📅 2026-06-22
  * VHDL synthesis (based on ghdl)
* [panda-bambu](https://github.com/ferrandi/PandA-bambu) ⭐ 350 | 🐛 32 | 🌐 C++ | 📅 2026-08-04
  * High level synthesis (HLS) C/C++ framework
* [hdlconvertor](https://github.com/Nic30/hdlConvertor) ⭐ 332 | 🐛 32 | 🌐 C++ | 📅 2025-06-30
  * Verilog/VHDL parser preprocessor and code generator for C++/Python based on ANTL4
* [veriloggen](https://github.com/PyHDI/veriloggen) ⭐ 327 | 🐛 26 | 🌐 Python | 📅 2026-03-08
  * Mixed-Paradigm Hardware Construction Framework
* [hastlayer](https://github.com/Lombiq/Hastlayer-SDK) ⭐ 319 | 🐛 37 | 🌐 VHDL | 📅 2026-08-08
  * VHDL generator from .NET languages (C#, F#, and others) and FPGA framework for .NET hardware acceleration
* [systemc-compiler](https://github.com/intel/systemc-compiler) ⭐ 317 | 🐛 1 | 🌐 C++ | 📅 2026-08-13
  * Translates synthesizable SystemC to synthesizable Verilog
* [mockturtle](https://github.com/lsils/mockturtle) ⭐ 304 | 🐛 10 | 🌐 C++ | 📅 2026-08-07
  * C++ logic network library
* [pyrtl](https://github.com/UCSBarchlab/PyRTL) ⭐ 303 | 🐛 20 | 🌐 Python | 📅 2026-08-13
  * Python integrated design and simulation framework
* [matchlib](https://github.com/NVlabs/matchlib) ⭐ 300 | 🐛 1 | 🌐 C++ | 📅 2026-07-23
  * Synthesizable SystemC/C++ library of commonly-used hardware functions
* [uhdm](https://github.com/chipsalliance/UHDM) ⭐ 267 | 🐛 14 | 🌐 C++ | 📅 2026-08-24
  * Universal object model for IEEE SystemVerilog designs
* [magma](https://github.com/phanrahan/magma/) ⭐ 265 | 🐛 195 | 🌐 Python | 📅 2024-10-19
  * Python based hardware design language
* [livehd](https://github.com/masc-ucsc/livehd) ⭐ 239 | 🐛 5 | 🌐 C++ | 📅 2026-08-26
  * Infrastructure for live interactive synthesis and simulation
* [synlig](https://github.com/chipsalliance/synlig) ⭐ 235 | 🐛 87 | 🌐 Verilog | 📅 2025-03-10
  * SystemVerilog support for Yosys
* [lstools](https://github.com/lsils/lstools-showcase) ⭐ 208 | 🐛 1 | 🌐 CSS | 📅 2024-04-05
  * Showcase examples for EPFL logic synthesis libraries
* [fault](https://github.com/AUCOHL/Fault) ⭐ 202 | 🐛 15 | 🌐 Swift | 📅 2025-08-30
  * Design-for-testing (DFT) Solution
* [tce](https://github.com/cpc/tce) ⭐ 192 | 🐛 26 | 🌐 C | 📅 2026-07-27
  * Application-specific instruction-set processor (ASIP) toolset
* [kami](https://github.com/mit-plv/kami) ⭐ 169 | 🐛 4 | 🌐 Rocq Prover | 📅 2026-05-26
  * Platform for High-Level Parametric Hardware Specification and Verification
* [naja](https://github.com/xtofalex/naja) ⭐ 160 | 🐛 13 | 🌐 Verilog | 📅 2026-08-26
  * Structural Netlist API for EDA post synthesis flow development
* [pygears](https://github.com/bogdanvuk/pygears) ⭐ 146 | 🐛 10 | 🌐 Python | 📅 2023-06-26
  * Python based hardware design framework
* [ipyxact](https://github.com/olofk/ipyxact) ⭐ 141 | 🐛 10 | 🌐 Python | 📅 2024-06-13
  * Python-based IP-XACT parser
* [circuitgraph](https://github.com/circuitgraph/circuitgraph) ⭐ 131 | 🐛 14 | 🌐 Verilog | 📅 2023-11-17
  * Tools for working with circuits as graphs in python
* [act](https://github.com/asyncvlsi/act) ⭐ 130 | 🐛 1 | 🌐 C++ | 📅 2026-08-26
  * Asynchronous circuit compiler tools
* [tapasco](https://github.com/esa-tu-darmstadt/tapasco) ⭐ 127 | 🐛 52 | 🌐 Verilog | 📅 2026-06-23
  * Heterogeneous system composer
* [spydrnet](https://github.com/byuccl/spydrnet) ⭐ 116 | 🐛 46 | 🌐 Python | 📅 2026-04-27
  * Framework for analyzing and transforming Verilog netlists
* [lsoracle](https://github.com/lnis-uofu/LSOracle) ⭐ 115 | 🐛 25 | 🌐 Verilog | 📅 2026-04-15
  * Famework built on EPFL logic synthesis libraries.
* [coreir](https://github.com/rdaly525/coreir) ⭐ 106 | 🐛 156 | 🌐 C++ | 📅 2022-06-27
  * LLVM-style hardware compiler with first class support for generators
* [circuitops](https://github.com/NVlabs/CircuitOps) ⭐ 102 | 🐛 3 | 🌐 Python | 📅 2025-06-24
  * Infrastructure for dataset generation and model deployment in Generative AI
* [dfiant](https://github.com/DFiantHDL/DFiant) ⭐ 97 | 🐛 1 | 🌐 Scala | 📅 2026-08-25
  * Dataflow Hardware Description Language
* [hdl21](https://github.com/dan-fritchman/Hdl21) ⭐ 96 | 🐛 48 | 🌐 Python | 📅 2026-02-17
  * Hardware Description Library
* [hs-to-coq](https://github.com/plclub/hs-to-coq) ⭐ 96 | 🐛 63 | 🌐 Rocq Prover | 📅 2026-07-09
  * Convert Haskell source code to Coq source code
* [sodaopt](https://github.com/pnnl/soda-opt) ⭐ 63 | 🐛 3 | 🌐 C++ | 📅 2026-08-18
  * Optimizer leveraging mlir to extract, optimize, translate HLSinto LLVM IR
* [gamora](https://github.com/Yu-Utah/Gamora) ⭐ 59 | 🐛 4 | 🌐 C | 📅 2025-01-08
  * Graph Learning based Symbolic Reasoning for Large-Scale Boolean Networks
* [pysysc](https://github.com/accellera-official/PySysC) ⭐ 56 | 🐛 6 | 🌐 Python | 📅 2023-12-26
  * Python package to make SystemC usable from Python
* [verik](https://github.com/frwang96/verik) ⭐ 47 | 🐛 0 | 🌐 Kotlin | 📅 2022-12-24
  * Kotlin based hardware description language
* [gamma](https://github.com/maestro-project/gamma) ⭐ 45 | 🐛 6 | 🌐 Python | 📅 2024-06-30
  * Optimizes mapping of DNN models on DNN Accelerators
* [matchclib\_connections](https://github.com/hlslibs/matchlib_connections) ⭐ 43 | 🐛 2 | 🌐 C++ | 📅 2026-07-06
  * Synthesizable SystemC library implementing latency-insensitive channels
* [vlsir](https://github.com/Vlsir/Vlsir) ⭐ 40 | 🐛 29 | 🌐 TypeScript | 📅 2026-02-15
  * Interchange formats for chip design
* [bigspicy](https://github.com/google/bigspicy) ⚠️ Archived
  * Tool for merging circuit descriptions
* [netlist-paths](https://github.com/jameshanlon/netlist-paths) ⚠️ Archived
  * A library and command-line tool for querying a Verilog netlist
* [halide-to-hardware](https://github.com/StanfordAHA/Halide-to-Hardware) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-08-26
  * Hardware generator combining halide and coreir

## FPGA Compilers

* [nextpnr](https://github.com/YosysHQ/nextpnr) ⭐ 1,735 | 🐛 146 | 🌐 C++ | 📅 2026-08-26
  * FPGA place and route tool
* [vtr](https://github.com/verilog-to-routing/vtr-verilog-to-routing) ⭐ 1,258 | 🐛 120 | 🌐 C++ | 📅 2026-08-26
  * FPGA place and route tool
* [flowtune](https://github.com/Yu-Utah/FlowTune) ⭐ 184 | 🐛 1 | 🌐 C | 📅 2022-11-12
  * FPGA synehsis and PNR optimizer
* [amf-placer](https://github.com/zslwyuan/AMF-Placer) ⭐ 116 | 🐛 4 | 🌐 C++ | 📅 2024-03-09
  * Timing-driven analytical mixed-size FPGA placer
* [dreamplacefpga](https://github.com/rachelselinar/DREAMPlaceFPGA) ⭐ 98 | 🐛 6 | 🌐 C++ | 📅 2025-04-30
  * Analytical Placer for Large Scale Heterogeneous FPGA

## Layout Compilers

* [openroad](https://github.com/The-OpenROAD-Project/OpenROAD) ⭐ 3,021 | 🐛 199 | 🌐 Verilog | 📅 2026-08-26
  * Complete RTL2GDS platform
* [klayout](https://github.com/KLayout/klayout) ⭐ 1,182 | 🐛 217 | 🌐 C++ | 📅 2026-08-26
  * Layout viewer
* [dreamplace](https://github.com/limbo018/DREAMPlace) ⭐ 1,044 | 🐛 92 | 🌐 C++ | 📅 2026-07-18
  * Deep learning toolkit-enabled VLSI placement
* [gdsfactory](https://github.com/gdsfactory/gdsfactory) ⭐ 1,022 | 🐛 122 | 🌐 Python | 📅 2026-08-25
  * Platform for chip design and layout
* [magic](https://github.com/RTimothyEdwards/magic) ⭐ 693 | 🐛 191 | 🌐 C | 📅 2026-08-08
  * Magic VLSI layout tool
* [ieda](https://github.com/OSCC-Project/iEDA) ⭐ 540 | 🐛 8 | 🌐 C++ | 📅 2026-07-09
  * RTL2GDS infrastructure
* [gdstk](https://github.com/heitzmann/gdstk) ⭐ 496 | 🐛 52 | 🌐 C++ | 📅 2026-07-24
  * C++/Python library for creation and manipulation of GDSII and OASIS files.
* [align](https://github.com/ALIGN-analoglayout/ALIGN-public) ⭐ 386 | 🐛 6 | 🌐 Python | 📅 2026-08-18
  * Automatic layout generator for analog circuits
* [gdspy](https://github.com/heitzmann/gdspy) ⚠️ Archived
  * Python module for creating GDSII stream files, usually CAD layouts.
* [magical](https://github.com/magical-eda/MAGICAL) ⭐ 293 | 🐛 17 | 🌐 C++ | 📅 2024-04-24
  * Machine Generated Analog IC Layout
* [gds3d](https://github.com/trilomix/GDS3D) ⭐ 266 | 🐛 17 | 🌐 C++ | 📅 2024-08-20
  * Render GDS files in 3D
* [phidl](https://github.com/amccaugh/phidl) ⭐ 234 | 🐛 4 | 🌐 Python | 📅 2025-08-08
  * Python GDS layout and CAD geometry creation
* [bag](https://github.com/ucb-art/BAG_framework) ⭐ 172 | 🐛 12 | 🌐 Python | 📅 2022-12-04
  * Berkeley analog layout generator
* [autodmp](https://github.com/NVlabs/AutoDMP) ⭐ 169 | 🐛 9 | 🌐 C++ | 📅 2023-07-12
  * Automated DREAMPlace-based Macro Placement
* [layout21](https://github.com/dan-fritchman/Layout21) ⭐ 62 | 🐛 17 | 🌐 Rust | 📅 2025-02-25
  * Integrated Circuit Layout
* [gdsiistl](https://github.com/dteal/gdsiistl) ⭐ 54 | 🐛 3 | 🌐 Python | 📅 2020-04-22
  * Converts GDSII files to STL files
* [kweb](https://github.com/gdsfactory/kweb) ⚠️ Archived
  * Klayout Web Viewer
* [coriolis](https://gitlab.lip6.fr/vlsi-eda/coriolis.git)
  * RTL2GDS toolchain for mature nodes
* [lclayout](https://codeberg.org/librecell/lclayout)
  * Layout generator for CMOS standard-cells

# Design and Verification Tools

## Benchmarks

* [verilog-eval](https://github.com/NVlabs/verilog-eval) ⭐ 465 | 🐛 21 | 🌐 SystemVerilog | 📅 2025-07-14
  * Verilog evaluation benchmark for large language model
* [sv-tests](https://github.com/chipsalliance/sv-tests) ⭐ 388 | 🐛 82 | 🌐 SystemVerilog | 📅 2026-08-25
  * SystemVerilog compliance test suite
* [epfl-benchmarks](https://github.com/lsils/benchmarks) ⭐ 263 | 🐛 2 | 🌐 Verilog | 📅 2026-08-13
  * Combinational Benchmark Suite for logic synthesis
* [bringup-bench](https://github.com/toddmaustin/bringup-bench) ⭐ 227 | 🐛 2 | 🌐 C | 📅 2026-06-05
  * Collection of minimal programs useful for system bringup
* [corescore](https://github.com/olofk/corescore) ⭐ 178 | 🐛 14 | 🌐 Verilog | 📅 2026-06-09
  * Benchmark for FPGAs and their synthesis/P\&R tools
* [fpga-tool-perf](https://github.com/chipsalliance/fpga-tool-perf) ⭐ 109 | 🐛 91 | 🌐 Python | 📅 2024-02-24
  * FPGA tool performance profiling
* [opdb](https://github.com/PrincetonUniversity/OPDB) ⭐ 28 | 🐛 0 | 🌐 Verilog | 📅 2023-03-06
  * Princeton design benchmark generators
* [rdf-2020](https://github.com/ieee-ceda-datc/RDF-2020) ⭐ 16 | 🐛 1 | 🌐 Verilog | 📅 2022-01-08
  * IEEE CEDA eda benchmark flow
* [bsg\_pipeclean\_suite](https://github.com/bespoke-silicon-group/bsg_pipeclean_suite) ⭐ 11 | 🐛 0 | 🌐 Verilog | 📅 2020-01-09
  * Collection of designs used to stress test new CAD flows
* [big-doe-openroad](https://github.com/msaligane/Big-DoE-OpenROAD) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-03-10
  * Framework for launching massive RTL2GDS experiements

## Board Design

* [freecad](https://github.com/FreeCAD/FreeCAD) ⭐ 33,075 | 🐛 4,109 | 🌐 C++ | 📅 2026-08-26
  * 3D parametric CAD system
* [librepcb](https://github.com/LibrePCB/LibrePCB) ⭐ 2,971 | 🐛 215 | 🌐 C++ | 📅 2026-08-25
  * Board design framework
* [kicad](https://github.com/KiCad/kicad-source-mirror) ⭐ 2,901 | 🐛 0 | 🌐 C++ | 📅 2026-08-26
  * Board design framework
* [kikit](https://github.com/yaqwsx/KiKit) ⭐ 2,011 | 🐛 98 | 🌐 Python | 📅 2026-08-05
  * Automation tools for kicad
* [freerouting](https://github.com/freerouting/freerouting) ⭐ 1,907 | 🐛 42 | 🌐 Java | 📅 2026-08-24
  * PCB auto-router
* [kicanvas](https://github.com/theacodes/kicanvas) ⭐ 1,127 | 🐛 55 | 🌐 TypeScript | 📅 2026-04-28
  * KiCAD web viewer
* [cuflow](https://github.com/jamesbowman/cuflow) ⭐ 274 | 🐛 5 | 🌐 Python | 📅 2026-08-25
  * Experimental procedural PCB layout program
* [kicad-skip](https://github.com/psychogenic/kicad-skip) ⭐ 228 | 🐛 29 | 🌐 Python | 📅 2024-05-26
  * kicad s-expression schematic/layout file manipulation
* [pcbflow](https://github.com/michaelgale/pcbflow) ⭐ 194 | 🐛 4 | 🌐 Python | 📅 2025-02-12
  * Python based Printed Circuit Board (PCB) layout and design package based on CuFlow
* [boardview](https://github.com/whitequark/kicad-boardview) ⭐ 181 | 🐛 3 | 🌐 Python | 📅 2025-02-11
  * Reads KiCAD PCB layout files and writes ASCII Boardview files
* [datasheet-scrubber](https://github.com/idea-fasoc/datasheet-scrubber) ⭐ 62 | 🐛 12 | 🌐 Python | 📅 2025-05-16
  * Scrubs PDF datasheets/documents in order to extract key circuit information
* [kicad-footprint-generator](https://gitlab.com/kicad/libraries/kicad-footprint-generator)
  * kicad footprint generator using python scripts
* [kicad-library-utils](https://gitlab.com/kicad/libraries/kicad-library-utils)
  * scripts for helping with library development

## Digital Design

* [digital](https://github.com/hneemann/Digital) ⭐ 5,943 | 🐛 197 | 🌐 Java | 📅 2026-06-12
  * Digital logic designer and circuit simulator
* [vscode-teroshdl](https://github.com/TerosTechnology/vscode-terosHDL) ⭐ 739 | 🐛 231 | 🌐 VHDL | 📅 2026-08-07
  * Full IDE for RTL development in VS Code
* [vscode-systemverilog](https://github.com/eirikpre/VSCode-SystemVerilog) ⭐ 156 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-11
  * SystemVerilog support in VS Code
* [vsrtl](https://github.com/mortbopet/VSRTL/) ⭐ 115 | 🐛 30 | 🌐 C++ | 📅 2026-08-17
  * Visual Simulation of Register Transfer Logic
* [DigSim](https://github.com/freand76/digsim) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-04-02
  * An interactive digital logic simulator with verilog support (Yosys)
* [verilog-mode](https://www.veripool.org/verilog-mode/)
  * Popular free Verilog mode for Emacs

## Documentation

* [sphinx](https://github.com/sphinx-doc/sphinx) ⭐ 7,989 | 🐛 1,419 | 🌐 Python | 📅 2026-08-23
  * Document builder
* [nn-svg](https://github.com/alexlenail/NN-SVG) ⭐ 5,686 | 🐛 27 | 🌐 JavaScript | 📅 2026-06-02
  * Publication-ready NN-architecture schematics
* [wireviz](https://github.com/wireviz/WireViz) ⭐ 5,230 | 🐛 195 | 🌐 Python | 📅 2026-06-06
  * Docuyment cables and wiring harnesses
* [wavedrom](https://github.com/wavedrom/wavedrom) ⭐ 3,473 | 🐛 204 | 🌐 JavaScript | 📅 2026-07-08
  * Digital timing diagram rendering engine
* [kythe](https://github.com/chipsalliance/verible/blob/master/verilog/tools/kythe) ⭐ 1,918 | 🐛 615 | 🌐 C++ | 📅 2026-08-16
  * Verible based SystemVerilog source file indexer
* [graphviz](https://github.com/xflr6/graphviz) ⭐ 1,804 | 🐛 10 | 🌐 Python | 📅 2026-07-11
  * Python library for graph cration and rendering in DOT language
* [pcbdraw](https://github.com/yaqwsx/PcbDraw) ⭐ 1,414 | 🐛 10 | 🌐 Python | 📅 2026-08-07
  * Convert KiCAD board into 2D drawing suitable for pinout diagrams
* [netlistsvg](https://github.com/nturley/netlistsvg) ⭐ 820 | 🐛 55 | 🌐 JavaScript | 📅 2024-01-25
  * Draws an SVG schematic from a JSON netlist
* [pinion](https://github.com/yaqwsx/Pinion) ⭐ 496 | 🐛 0 | 🌐 Python | 📅 2026-08-23
  * Generate interactive Diagrams for your PCBs
* [pinout](https://github.com/j0ono0/pinout) ⭐ 431 | 🐛 10 | 🌐 Python | 📅 2026-04-20
  * Python package that generates hardware pinout diagrams as SVG images
* [elk](https://github.com/eclipse/elk) ⭐ 368 | 🐛 126 | 🌐 Java | 📅 2026-08-05
  * Eclipse Layout Kernel - Automatic layout for Java applications.
* [gds3d](https://github.com/trilomix/GDS3D) ⭐ 266 | 🐛 17 | 🌐 C++ | 📅 2024-08-20
  * Reads GDSII layout and renders in 3D
* [symbolator](https://github.com/kevinpt/symbolator) ⭐ 205 | 🐛 16 | 🌐 Python | 📅 2023-02-02
  * HDL symbol generator
* [wavedrompy](https://github.com/wallento/wavedrompy) ⭐ 116 | 🐛 20 | 🌐 Python | 📅 2023-06-02
  * Python comptabled Wavedrom module
* [netlist-viewer](https://github.com/f18m/netlist-viewer) ⭐ 94 | 🐛 16 | 🌐 C++ | 📅 2026-07-31
  * SPICE netlist visualizer
* [hdelk](https://github.com/davidthings/hdelk) ⭐ 86 | 🐛 13 | 🌐 JavaScript | 📅 2023-05-01
  * Web-based HDL diagramming tool
* [sphinxcontrib-hdl-diagrams](https://github.com/SymbiFlow/sphinxcontrib-hdl-diagrams) ⭐ 65 | 🐛 12 | 🌐 Python | 📅 2023-09-25
  * Sphinx plugin to automatically generate diagrams from RTL.
* [memory-layout-diagram](https://github.com/gerph/memory-layout-diagram) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2026-01-11
  * Diagrams for memory map layouts
* [undulate](https://github.com/LudwigCRON/undulate) ⭐ 37 | 🐛 5 | 🌐 Python | 📅 2024-09-19
  * Python compatible wavedrom module with extensions and console rendering support
* [sphinx-verilog-domain](https://github.com/SymbiFlow/sphinx-verilog-domain) ⭐ 27 | 🐛 7 | 🌐 Python | 📅 2021-03-01
  * Sphinx package for integration SystemVerilog documentation into Sphinx.

## FPGA Design

* [icestudio](https://github.com/FPGAwars/icestudio) ⭐ 1,923 | 🐛 21 | 🌐 JavaScript | 📅 2026-08-21
  * Visual editor for open FPGA boards
* [openfpgaloader](https://github.com/trabucayre/openFPGALoader) ⭐ 1,716 | 🐛 137 | 🌐 C++ | 📅 2026-08-26
  * Universal utility for programming FPGA
* [f4fpga](https://github.com/chipsalliance/f4pga) ⭐ 447 | 🐛 26 | 🌐 Python | 📅 2025-01-06
  * FPGA toolchain
* [f4pga/f4pga-arch-defs](https://github.com/f4pga/f4pga-arch-defs) ⭐ 313 | 🐛 367 | 🌐 Jupyter Notebook | 📅 2026-08-26
  * FPGA architecture definitions for F4FPGA
* [pyfpga](https://github.com/PyFPGA/pyfpga) ⭐ 149 | 🐛 5 | 🌐 Python | 📅 2025-03-22
  * Python based FPGA compilation
* [foedag](https://github.com/os-fpga/FOEDAG) ⭐ 74 | 🐛 15 | 🌐 C++ | 📅 2024-12-11
  * Framework Open EDA Gui
* [logik](https://github.com/zeroasiccorp/logik) ⭐ 63 | 🐛 2 | 🌐 Python | 📅 2026-08-10
  * FPGA toolchain
* [byteman](https://github.com/FPGA-Research-Manchester/byteman) ⭐ 56 | 🐛 0 | 🌐 C++ | 📅 2026-02-20
  * Bitstream relocation and manipulation tool
* [rphax](https://github.com/shariethernet/RPHAX) ⭐ 21 | 🐛 0 | 🌐 Tcl | 📅 2023-02-25
  * Automation flow to develop and prototype hardware accelerators on Xilinx FPGAs

## Formal Verification

* [z3](https://github.com/Z3Prover/z3) ⭐ 12,608 | 🐛 57 | 🌐 C++ | 📅 2026-08-26
  * Microsoft research theorem prover
* [cvc5](https://github.com/cvc5/cvc5) ⭐ 1,356 | 🐛 215 | 🌐 SMT | 📅 2026-08-25
  * SMT automatic theorem prover
* [sby](https://github.com/YosysHQ/sby) ⭐ 542 | 🐛 56 | 🌐 Python | 📅 2026-08-05
  * Front-end for Yosys-based formal verification flows.
* [boolector](https://github.com/boolector/boolector) ⚠️ Archived
  * SMT solver for tfixed-size bit-vectors, arrays and uninterpreted functions
* [pono](https://github.com/upscale-project/pono) ⭐ 133 | 🐛 43 | 🌐 C++ | 📅 2026-08-26
  * Extensible SMT-based model checker implemented in C++.
* [autosva](https://github.com/PrincetonUniversity/AutoSVA) ⭐ 103 | 🐛 0 | 🌐 Python | 📅 2024-03-29
  * Generates FV testbenches and SVA properties based on interface annotations + GPT4
* [ilang](https://github.com/PrincetonUniversity/ILAng) ⭐ 81 | 🐛 18 | 🌐 C++ | 📅 2024-07-03
  * Princeton modeling and Verification Platform for SoCs using ILAs
* [autocc](https://github.com/morenes/AutoCC) ⭐ 24 | 🐛 0 | 🌐 Standard ML | 📅 2024-10-25
  * Frontend for JG/SBY to automatically discover covert channels in time-shared hardware

## Linters

* [verilator](https://github.com/verilator/verilator) ⭐ 3,875 | 🐛 319 | 🌐 SystemVerilog | 📅 2026-08-26
  * SystemVerilog simulator and lint system
* [verible](https://github.com/chipsalliance/verible) ⭐ 1,918 | 🐛 615 | 🌐 C++ | 📅 2026-08-16
  * SystemVerilog developer tools, including a parser, style-linter, and formatter
* [svlint](https://github.com/dalance/svlint) ⭐ 390 | 🐛 24 | 🌐 Rust | 📅 2025-11-06
  * SystemVerilog linter
* [svlint-action](https://github.com/dalance/svlint-action) ⭐ 9 | 🐛 2 | 🌐 SystemVerilog | 📅 2023-08-25
  * GitHub action for svlint

## Register Design

* [rggen](https://github.com/rggen/rggen) ⭐ 468 | 🐛 23 | 🌐 Ruby | 📅 2026-08-16
  * Configuration and status register generator
* [systemrdl](https://github.com/SystemRDL/systemrdl-compiler) ⭐ 282 | 🐛 19 | 🌐 C++ | 📅 2026-04-10
  * Generic compiler front-end for SystemRDL 2.0 register description language
* [peakrdl](https://github.com/SystemRDL/PeakRDL) ⭐ 209 | 🐛 6 | 🌐 Python | 📅 2026-07-14
  * SystemRDL based control & status register (CSR) toolchain
* [open-register-design-tool](https://github.com/Juniper/open-register-design-tool) ⭐ 208 | 🐛 25 | 🌐 Verilog | 📅 2026-06-03
  * Generate register RTL, models, and docs using SystemRDL or JSpec input
* [hdl-registers](https://github.com/hdl-registers/hdl-registers) ⭐ 91 | 🐛 19 | 🌐 Python | 📅 2026-08-10
  * Fast HDL register code generator
* [gen\_registers](https://github.com/lsteveol/gen_registers) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2021-11-10
  * Python based tool for generating hardware registers and their associated files

## Schematics

* [qucs\_s](https://github.com/ra3xdh/qucs_s) ⭐ 1,356 | 🐛 32 | 🌐 C++ | 📅 2026-08-18
  * Integrated circuit simulator with Graphical User Interface
* [openplc\_editor](https://github.com/thiagoralves/OpenPLC_Editor) ⚠️ Archived
  * IDE capable of creating programs for the OpenPLC Runtime
* [xschem](https://github.com/StefanSchippers/xschem) ⭐ 488 | 🐛 38 | 🌐 C | 📅 2026-08-24
  * Schematic editor for VLSI/Asic/Analog custom designs
* [kaktus2dev](https://github.com/kactus2/kactus2dev) ⭐ 260 | 🐛 34 | 🌐 C++ | 📅 2026-07-31
  * Graphical EDA tool based on the IP-XACT standard
* [oregano](https://github.com/drahnr/oregano) ⭐ 232 | 🐛 61 | 🌐 C | 📅 2024-08-28
  * Schematic capture and circuit simulator
* [d3-hwschematics](https://github.com/Nic30/d3-hwschematic) ⭐ 122 | 🐛 20 | 🌐 JavaScript | 📅 2026-05-13
  * Schematic visualizer
* [hdl21schematics](https://github.com/Vlsir/Hdl21Schematics) ⭐ 17 | 🐛 24 | 🌐 TypeScript | 📅 2024-01-24
  * Hdl21 Schematics

## Electronics Simulators

* [qemu](https://github.com/qemu/qemu) ⭐ 13,628 | 🐛 0 | 🌐 C | 📅 2026-08-26
  * Generic and open source machine & userspace emulator and virtualizer
* [logisim-evolution](https://github.com/logisim-evolution/logisim-evolution) ⭐ 7,486 | 🐛 127 | 🌐 Java | 📅 2026-08-26
  * Digital logic design tool and simulator
* [verilator](https://github.com/verilator/verilator) ⭐ 3,875 | 🐛 319 | 🌐 SystemVerilog | 📅 2026-08-26
  * SystemVerilog simulator and lint system
* [icarus](https://github.com/steveicarus/iverilog.git) ⭐ 3,608 | 🐛 188 | 🌐 C++ | 📅 2026-08-23
  * Verilog IEEE-1364 simulator
* [ghdl](https://github.com/ghdl/ghdl) ⭐ 2,868 | 🐛 352 | 🌐 VHDL | 📅 2026-08-26
  * VHDL 2008/93/87 simulator
* [gem5](https://github.com/gem5/gem5) ⭐ 2,769 | 🐛 203 | 🌐 C++ | 📅 2026-08-26
  * Modular simulator platform for computer-system architecture research
* [renode](https://github.com/renode/renode) ⭐ 2,768 | 🐛 428 | 🌐 RobotFramework | 📅 2026-08-26
  * Generic and open source machine emulator
* [firesim](https://github.com/firesim/firesim) ⭐ 1,036 | 🐛 239 | 🌐 Scala | 📅 2026-06-26
  * FPGA-accelerated Cycle-accurate Hardware Simulation in the Cloud
* [nvc](https://github.com/nickg/nvc) ⭐ 878 | 🐛 107 | 🌐 C | 📅 2026-08-20
  * VHDL compiler and simulator
* [champsim](https://github.com/ChampSim/ChampSim) ⭐ 746 | 🐛 60 | 🌐 C++ | 📅 2026-07-28
  * Trace-based simulator for a microarchitecture study
* [ramulator2](https://github.com/CMU-SAFARI/ramulator2) ⭐ 625 | 🐛 1 | 🌐 C++ | 📅 2026-08-04
  * Cycle accurate DRAM simulator
* [noxim](https://github.com/davidepatti/noxim) ⭐ 332 | 🐛 9 | 🌐 C++ | 📅 2026-06-09
  * Network on Chip Simulator
* [libsystemctlm-soc](https://github.com/Xilinx/libsystemctlm-soc) ⭐ 304 | 🐛 16 | 🌐 Verilog | 📅 2026-06-26
  * SystemC/TLM-2.0 Co-simulation framework
* [simulide](https://github.com/SimulIDE/SimulIDE) ⭐ 303 | 🐛 22 | 🌐 C++ | 📅 2021-11-04
  * SimulIDE is a simple real-time electronic circuit simulator
* [dromajo](https://github.com/chipsalliance/dromajo) ⭐ 244 | 🐛 26 | 🌐 C++ | 📅 2024-11-20
  * RISC-V RV64GC functional emulator
* [SST](https://github.com/sstsimulator/sst-core) ⭐ 204 | 🐛 110 | 🌐 C++ | 📅 2026-08-11
  * Simulation platform to connect multiple simulated hardware objects
* [essent](https://github.com/ucsc-vama/essent) ⭐ 195 | 🐛 0 | 🌐 Scala | 📅 2026-08-04
  * High-performance FIRRTL (Chisel) simulator
* [xictools](https://github.com/wrcad/xictools) ⭐ 184 | 🐛 27 | 🌐 C++ | 📅 2026-08-20
  * Circuit simulation package
* [eesim](https://github.com/danchitnis/EEsim) ⭐ 182 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-23
  * Browser-based SPICE circuit simulator
* [xyce](https://github.com/Xyce/Xyce) ⭐ 168 | 🐛 45 | 🌐 C | 📅 2026-08-10
  * Parallel spice simulator from Sandia national labs
* [systemc-components](https://github.com/Minres/SystemC-Components) ⭐ 139 | 🐛 9 | 🌐 C++ | 📅 2026-08-24
  * SystemC simulation productivity library
* [sax](https://github.com/flaport/sax) ⭐ 129 | 🐛 8 | 🌐 Python | 📅 2026-06-19
  * S-parameter based frequency domain circuit simulation
* [SimEng](https://github.com/UoB-HPC/SimEng) ⭐ 109 | 🐛 65 | 🌐 C++ | 📅 2026-06-17
  * Fast, easily modifiable, cycle-level CPU simulator framework
* [muchisim](https://github.com/PrincetonUniversity/muchisim) ⭐ 76 | 🐛 1 | 🌐 C++ | 📅 2024-06-30
  * Cycle-level simulator for PPA analysis of distributed multi-chiplet designs.
* [tiny-five](https://github.com/OpenMachine-ai/tinyfive) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2023-11-01
  * Lightweight RISC-V emulator and assembler written entirely in Python
* [pysysc](https://github.com/accellera-official/PySysC) ⭐ 56 | 🐛 6 | 🌐 Python | 📅 2023-12-26
  * Python package to make SystemC usable from Python
* [irsim](https://github.com/RTimothyEdwards/irsim) ⭐ 39 | 🐛 8 | 🌐 C | 📅 2025-11-13
  * Switch-level simulator for digital circuits
* [lwtr4sc](https://github.com/Minres/LWTR4SC) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2026-08-15
  * Transaction recording for SystemC
* [ngspice](http://ngspice.sourceforge.net/)
  * Spice simulator

## Verification Frameworks

* [cocotb](https://github.com/cocotb/cocotb) ⭐ 2,483 | 🐛 410 | 🌐 Python | 📅 2026-08-24
  * Python based cosimulation library for VHDL and Verilog testbenches
* [openplc\_v3](https://github.com/thiagoralves/OpenPLC_v3) ⚠️ Archived
  * OpenPLC Runtime version 3
* [riscv-dv](https://github.com/chipsalliance/riscv-dv) ⭐ 1,350 | 🐛 166 | 🌐 Python | 📅 2026-04-03
  * Random instruction generator for RISC-V processor verification
* [pyspice](https://github.com/PySpice-org/PySpice) ⭐ 862 | 🐛 205 | 🌐 Python | 📅 2024-08-13
  * Python interface for ngspice and xyce
* [vunit](https://github.com/VUnit/vunit) ⭐ 843 | 🐛 269 | 🌐 VHDL | 📅 2026-08-13
  * Unit testing framework for VHDL/SystemVerilog
* [core-v-verif](https://github.com/openhwgroup/core-v-verif) ⭐ 713 | 🐛 157 | 🌐 Assembly | 📅 2026-08-13
  * Functional verification project for the CORE-V family of RISC-V cores
* [opentimer](https://github.com/OpenTimer/OpenTimer) ⭐ 713 | 🐛 63 | 🌐 Verilog | 📅 2025-12-26
  * High performance static timing analysis
* [opensta](https://github.com/The-OpenROAD-Project/OpenSTA) ⭐ 609 | 🐛 35 | 🌐 Verilog | 📅 2026-08-19
  * Signoff quality STA engine used by OpenRoad
* [pyuvm](https://github.com/pyuvm/pyuvm) ⭐ 568 | 🐛 7 | 🌐 Python | 📅 2026-08-24
  * SystemVerilog UVM written in Python
* [uvvm](https://github.com/UVVM/UVVM) ⭐ 461 | 🐛 24 | 🌐 VHDL | 📅 2026-04-22
  * Library for making very structured VHDL-based testbenches.
* [cocotbext-axi](https://github.com/alexforencich/cocotbext-axi) ⭐ 355 | 🐛 63 | 🌐 Python | 📅 2026-08-24
  * AXI interface modules for Cocotb
* [switchboard](https://github.com/zeroasiccorp/switchboard/) ⭐ 319 | 🐛 42 | 🌐 Python | 📅 2026-08-03
  * Communication framework for RTL simulation and emulation
* [force-riscv](https://github.com/openhwgroup/force-riscv) ⭐ 313 | 🐛 19 | 🌐 C++ | 📅 2023-10-17
  * Instruction Set Generator for RISC-V
* [maestro](https://github.com/maestro-project/maestro) ⭐ 261 | 🐛 19 | 🌐 MATLAB | 📅 2024-04-15
  * Analytical cost model evaluating DNN mappings (dataflows and tiling)
* [cocotbext-pcie](https://github.com/alexforencich/cocotbext-pcie) ⭐ 210 | 🐛 16 | 🌐 Python | 📅 2026-08-25
  * PCI express simulation framework for Cocotb
* [openvaf](https://github.com/pascalkuthe/OpenVAF) ⭐ 195 | 🐛 69 | 🌐 Rust | 📅 2024-08-20
  * Next generation Verilog-A compiler
* [systemctlm-cosim-demo](https://github.com/Xilinx/systemctlm-cosim-demo) ⭐ 169 | 🐛 24 | 🌐 C++ | 📅 2026-06-25
  * Demo system for libsystemctlm-soc library
* [pcievhost](https://github.com/wyvernSemi/pcievhost) ⭐ 149 | 🐛 1 | 🌐 C | 📅 2026-06-16
  * PCIe (1.0a to 2.0) Virtual host model for verilog
* [pyvsc](https://github.com/fvutils/pyvsc) ⭐ 148 | 🐛 52 | 🌐 Python | 📅 2026-07-05
  * Python packages for SystemVerilog UVM style Verification Stimulus and Coverage
* [netgen](https://github.com/RTimothyEdwards/netgen) ⭐ 141 | 🐛 50 | 🌐 C | 📅 2026-07-07
  * LVS tool for comparing SPICE or verilog netlists
* [ddr5\_phy](https://github.com/Shehab-Naga/ddr5_phy) ⭐ 90 | 🐛 2 | 🌐 SystemVerilog | 📅 2024-03-21
  * UVM testbench for DDR5 PHY
* [osvvm](https://github.com/OSVVM/OsvvmLibraries) ⭐ 86 | 🐛 4 | 📅 2026-08-21
  * A VHDL verification framework
* [vidbo](https://github.com/olofk/vidbo) ⭐ 64 | 🐛 2 | 🌐 C | 📅 2021-11-26
  * Virtual development board
* [svreal](https://github.com/sgherbst/svreal) ⭐ 52 | 🐛 6 | 🌐 SystemVerilog | 📅 2021-01-13
  * Synthesizable real number library in SystemVerilog (fixed & floating point formats)
* [msdsl](https://github.com/sgherbst/msdsl) ⭐ 49 | 🐛 13 | 🌐 Python | 📅 2024-04-02
  * Automatic generation of real number models from analog circuits
* [fault](https://github.com/leonardt/fault) ⭐ 48 | 🐛 71 | 🌐 Python | 📅 2024-03-11
  * Python package for testing hardware
* [rohd-vf](https://github.com/intel/rohd-vf) ⭐ 48 | 🐛 5 | 🌐 Dart | 📅 2026-07-13
  * ROHD-based verification and testbench framework in Dart.
* [anasysmod](https://github.com/sgherbst/anasymod) ⭐ 39 | 🐛 23 | 🌐 Python | 📅 2021-07-28
  * Framework for FPGA emulation of mixed-signal systems
* [frame](https://github.com/maestro-project/frame) ⭐ 39 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-10-13
  * Fast Roofline Analytical Modeling and Estimation
* [cvc](https://github.com/d-m-bailey/cvc) ⭐ 38 | 🐛 211 | 🌐 C++ | 📅 2026-04-09
  * CVC: Circuit Validity Checker
* [pyucis](https://github.com/fvutils/pyucis) ⭐ 38 | 🐛 15 | 🌐 Python | 📅 2026-03-07
  * Python API to Unified Coverage Interoperability Standard (UCIS) Data
* [raft](https://github.com/Xilinx/RAFT) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2026-06-17
  * Rapid Abstraction FPGA Toolbox
* [rohd-cosim](https://github.com/intel/rohd-cosim) ⭐ 29 | 🐛 23 | 🌐 Dart | 📅 2026-05-20
  * Framework for cosimulation between the ROHD and SystemVerilog simulators.
* [fstdumper](https://github.com/semify-eda/fstdumper) ⭐ 24 | 🐛 4 | 🌐 C | 📅 2023-09-19
  * Verilog VPI module to dump FST (Fast Signal Trace) databases
* [adc-eval](https://github.com/esynr3z/adc-eval) ⭐ 22 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2023-06-26
  * Python tools for ADC performance analysis
* [awsteria\_infra](https://github.com/bluespec/AWSteria_Infra) ⭐ 20 | 🐛 1 | 🌐 VHDL | 📅 2024-09-26
  * Middleware for AWS hosted FPGA applications
* [constrainedrandom](https://github.com/imaginationtech/constrainedrandom) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2024-10-14
  * Python package for creating and solving constrained randomization problems
* [sv\_waveterm](https://github.com/PeterMonsson/sv_waveterm) ⭐ 10 | 🐛 1 | 🌐 SystemVerilog | 📅 2023-11-02
  * Generate text waves in simulation log file
* [v2k-top](https://github.com/kev-cam/v2k-top) ⭐ 8 | 🐛 1 | 🌐 C++ | 📅 2025-12-02
  * Parser/simulation framework for Verilog & C++
* [lctime](https://codeberg.org/librecell/lctime)
  * Library cell characterization

## Physics

* [meep](https://github.com/NanoComp/meep) ⭐ 1,750 | 🐛 379 | 🌐 C++ | 📅 2026-08-25
  * Finite-difference-time-domain (FDTD) electromagneic simulation
* [paraview](https://github.com/Kitware/ParaView) ⭐ 1,689 | 🐛 8 | 🌐 C++ | 📅 2026-08-26
  * Data Analysis and Visualization Application
* [elmer](https://github.com/ElmerCSC/elmerfem) ⭐ 1,676 | 🐛 79 | 🌐 Fortran | 📅 2026-08-26
  * Finite Element Solver
* [scikit-rf](https://github.com/scikit-rf/scikit-rf) ⭐ 926 | 🐛 54 | 🌐 Python | 📅 2026-08-26
  * RF and Microwave Engineering Scikit
* [femwell](https://github.com/HelgeGehring/femwell) ⭐ 178 | 🐛 64 | 🌐 Python | 📅 2026-05-04
  * Finite element based simulation tool for integrated circuits, electric and photonic
* [hotspot](https://github.com/uvahotspot/HotSpot) ⭐ 166 | 🐛 14 | 🌐 C | 📅 2023-11-06
  * Thermal modeling tool for use in architectural studies
* [pact](https://github.com/peaclab/PACT) ⭐ 67 | 🐛 7 | 🌐 Python | 📅 2026-01-16
  * Thermal simulator
* [devsim](https://github.com/devsim)
  * TCAD Semiconductor Device Simulator

## Waveform Viewers

* [gtkwave](https://github.com/gtkwave/gtkwave) ⭐ 1,009 | 🐛 207 | 🌐 C | 📅 2026-08-23
  * GTK+ based VCD waveform viewer
* [konata](https://github.com/shioyadan/Konata) ⭐ 562 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26
  * Instruction pipeline visualizer for Gem5
* [scopy](https://github.com/analogdevicesinc/scopy) ⭐ 499 | 🐛 78 | 🌐 C++ | 📅 2026-08-25
  * Software oscilloscope and signal analysis toolset
* [iio-oscilloscope](https://github.com/analogdevicesinc/iio-oscilloscope) ⭐ 342 | 🐛 38 | 🌐 C | 📅 2026-08-18
  * GTK+ based oscilloscope application for interfacing with various IIO devices
* [npTDMS](https://github.com/adamreeve/npTDMS) ⭐ 274 | 🐛 20 | 🌐 Python | 📅 2026-08-02
  * Python module for reading TDMS files produced by LabView
* [verilog-vcd-parser](https://github.com/ben-marshall/verilog-vcd-parser) ⭐ 104 | 🐛 9 | 🌐 C++ | 📅 2022-03-06
  * Parser for Value Change Dump (VCD) files
* [waveforms-live](https://github.com/Digilent/waveforms-live) ⭐ 100 | 🐛 38 | 🌐 TypeScript | 📅 2020-07-07
  * Browser based analog waveform viewer
* [simview](https://github.com/pieter3d/simview) ⭐ 99 | 🐛 8 | 🌐 C++ | 📅 2026-07-22
  * Text-based SystemVerilog design browser and waveform viewer
* [wavebin](https://github.com/sam210723/wavebin) ⭐ 88 | 🐛 5 | 🌐 Python | 📅 2024-05-05
  * Oscilloscope waveform capture viewer and converter
* [sootty](https://github.com/Ben1152000/sootty) ⭐ 71 | 🐛 26 | 🌐 Python | 📅 2024-02-19
  * Command-line tool for displaying vcd waveforms
* [d3wave](https://github.com/Nic30/d3-wave) ⭐ 68 | 🐛 6 | 🌐 TypeScript | 📅 2026-06-09
  * D3.js based wave (signal) visualizer
* [spyci](https://github.com/gmagno/spyci) ⭐ 54 | 🐛 10 | 🌐 Python | 📅 2022-12-26
  * Python package to parse spice raw data files
* [scviewer](https://github.com/Minres/SCViewer) ⭐ 22 | 🐛 0 | 🌐 Java | 📅 2026-08-17
  * Eclipse plugins to display VCD (e.g. created by SystemC VCD trace).
* [sigrok](https://github.com/sigrokproject)
  * Portable, signal analysis software suite (logic analyzers, scopes, multimeters, and more)

# Designs & Generators

## Accelerators

* [vortex](https://github.com/vortexgpgpu/vortex) ⭐ 2,220 | 🐛 16 | 🌐 Verilog | 📅 2026-08-20
  * Full-system RISCV-based GPGPU processor
* [nyuziprocessor](https://github.com/jbush001/NyuziProcessor) ⭐ 2,218 | 🐛 91 | 🌐 C | 📅 2024-11-08
  * GPGPU microprocessor architecture
* [nvdla](https://github.com/nvdla/hw) ⭐ 2,141 | 🐛 202 | 🌐 Verilog | 📅 2022-03-02
  * NVIDIA Deep Learning Accelerator (NVDLA)
* [gemmini](https://github.com/ucb-bar/gemmini) ⭐ 1,436 | 🐛 107 | 🌐 Scala | 📅 2026-06-30
  * Berkeley Spatial Array Generator
* [verigpu](https://github.com/hughperkins/VeriGPU) ⭐ 1,364 | 🐛 11 | 🌐 SystemVerilog | 📅 2024-11-22
  * OpenSource GPU, loosely based on RISC-V ISA
* [finn](https://github.com/Xilinx/finn) ⭐ 1,044 | 🐛 113 | 🌐 Python | 📅 2026-08-26
  * Quantized NN to FPGA dataflow accelerator generator
* [fpu](https://github.com/dawsonjon/fpu) ⭐ 754 | 🐛 13 | 🌐 Verilog | 📅 2023-03-13
  * Synthesizable ieee 754 floating point library in verilog
* [pyfda](https://github.com/chipmuenk/pyFDA) ⭐ 730 | 🐛 39 | 🌐 Python | 📅 2026-08-26
  * Python Filter Design Analysis Tool
* [gplgpu](https://github.com/asicguy/gplgpu) ⭐ 703 | 🐛 7 | 🌐 VHDL | 📅 2014-08-31
  * GPL v3 2D/3D graphics engine in verilog
* [ara](https://github.com/pulp-platform/ara) ⭐ 538 | 🐛 134 | 🌐 C | 📅 2026-08-19
  * Vector Unit, compatible with the RISC-V Vector Extension
* [openofdm](https://github.com/jhshi/openofdm) ⭐ 481 | 🐛 17 | 🌐 Verilog | 📅 2023-01-29
  * 802.11 OFDM PHY decoder
* [aes](https://github.com/secworks/aes) ⭐ 462 | 🐛 0 | 🌐 Verilog | 📅 2025-12-29
  * Symmetric block cipher AES (Advanced Encryption Standard)
* [sha256](https://github.com/secworks/sha256) ⭐ 387 | 🐛 0 | 🌐 Verilog | 📅 2025-12-15
  * SHA-256 hash function (NIST FIPS 180-4)
* [nngen](https://github.com/NNgen/nngen) ⭐ 367 | 🐛 34 | 🌐 Python | 📅 2023-10-17
  * Fully-Customizable Hardware Synthesis Compiler for Deep Neural Network
* [tvm-vta](https://github.com/apache/tvm-vta) ⭐ 360 | 🐛 5 | 🌐 Scala | 📅 2024-04-10
  * Opwn, modular, deep learning accelerator
* [project-zipline](https://github.com/opencomputeproject/Project-Zipline) ⭐ 294 | 🐛 9 | 🌐 Verilog | 📅 2023-04-11
  * Zipline lossless compression implementation
* [h265-encoder-rtl](https://github.com/openasic-org/h265-encoder-rtl) ⭐ 286 | 🐛 4 | 🌐 Verilog | 📅 2023-04-09
  * H.265 Video Encoder IP Core
* [core\_jpeg](https://github.com/ultraembedded/core_jpeg) ⭐ 278 | 🐛 7 | 🌐 Verilog | 📅 2022-03-05
  * High throughput JPEG decoder in Verilog for FPGA
* [spiral](https://github.com/spiral-software/spiral-software) ⭐ 242 | 🐛 14 | 🌐 Shell | 📅 2026-08-16
  * Spiral based FFT generator
* [opencgra](https://github.com/pnnl/OpenCGRA) ⭐ 180 | 🐛 4 | 🌐 Verilog | 📅 2026-03-04
  * Parametrizable Coarse-Grained Reconfigurable Array (CGRA) Generator
* [openspike](https://github.com/sfmth/OpenSpike) ⭐ 177 | 🐛 0 | 🌐 Verilog | 📅 2023-02-13
  * Spiking neural network accelerator
* [verilog-lfsr](https://github.com/alexforencich/verilog-lfsr) ⭐ 163 | 🐛 2 | 🌐 Python | 📅 2025-02-27
  * Parametrizable combinatorial parallel LFSR/CRC module
* [bismp](https://github.com/EECS-NTNU/bismo/) ⭐ 150 | 🐛 2 | 🌐 Scala | 📅 2019-12-25
  * Chisel-based bit-serial matrix multiplication accelerator generator
* [garnet](https://github.com/StanfordAHA/garnet) ⭐ 119 | 🐛 79 | 🌐 Python | 📅 2026-08-26
  * CGRA generator
* [logicnets](https://github.com/Xilinx/logicnets) ⭐ 119 | 🐛 9 | 🌐 Python | 📅 2024-06-12
  * Train and generate LUT-based neural networks
* [sextans](https://github.com/linghaosong/Sextans) ⭐ 95 | 🐛 0 | 🌐 C++ | 📅 2026-08-11
  * FPGA accelerator for Sparse-Matrix Dense-Matrix Multiplication (SpMM)
* [sha3](https://github.com/ucb-bar/sha3) ⭐ 81 | 🐛 2 | 🌐 Verilog | 📅 2024-02-27
  * Berkeley SHAR3 ROCC Accelerator
* [verigood-ml](https://github.com/VeriGOOD-ML/public) ⭐ 70 | 🐛 3 | 🌐 Verilog | 📅 2025-04-30
  * Verilog Generator, Optimized for Designs for Machine Learning
* [Viterbi](https://github.com/jfoshea/Viterbi-Decoder-in-Verilog) ⭐ 63 | 🐛 2 | 🌐 Verilog | 📅 2024-03-15
  * Viterbi decoder (2,1,3) (3,2,2) (2,1,3) (3,2,2)
* [ranc](https://github.com/UA-RCL/RANC) ⭐ 59 | 🐛 7 | 🌐 VHDL | 📅 2024-01-29
  * Reconfigurable architecture for neuromorphic computing
* [sha512](https://github.com/secworks/sha512) ⭐ 47 | 🐛 1 | 🌐 Verilog | 📅 2026-01-17
  * SHA-512 hash function (NIST FIPS 180-4)
* [serpens](https://github.com/linghaosong/Serpens) ⭐ 19 | 🐛 2 | 🌐 C++ | 📅 2024-08-29
  * HBM FPGA based SpMV Accelerator
* [bfg](https://github.com/growly/bfg) ⭐ 18 | 🐛 9 | 🌐 SourcePawn | 📅 2026-08-25
  * Compiler for Reduced-Complexity Reconfigurable Fabrics
* [Viterbi](https://github.com/Archit-halder/Viterbi-Algorithm) ⭐ 14 | 🐛 1 | 🌐 Verilog | 📅 2020-08-12
  * Viterbi encoder/decoder (2,1,4)
* [fftgenerator](https://github.com/ucb-bar/FFTGenerator) ⭐ 13 | 🐛 0 | 🌐 Scala | 📅 2025-09-01
  * MMIO-Based FFT Generator
* [fftgenerator](https://github.com/ucb-bar/FFTGenerator) ⭐ 13 | 🐛 0 | 🌐 Scala | 📅 2025-09-01
  * Chisel based FFT generator

## AIB

* [aib](https://github.com/chipsalliance/aib-phy-hardware) ⭐ 149 | 🐛 0 | 🌐 Verilog | 📅 2024-09-23
  * Advanced Interface Bus (AIB) die to die hardware
* [aib-protocols](https://github.com/chipsalliance/aib-protocols) ⭐ 32 | 🐛 0 | 🌐 SystemVerilog | 📅 2024-02-20
  * Advanced Interface Bus (AIB) Protocol IP
* [axi4\_aib\_bridge](https://github.com/lmco/axi4_aib_bridge) ⚠️ Archived
  * AXI4/AIB Bridge RTL

## AXI

* [axi](https://github.com/pulp-platform/axi) ⭐ 1,665 | 🐛 74 | 🌐 SystemVerilog | 📅 2026-08-26
  * (Pulp) AXI SystemVerilog synthesizable IP
* [verilog-axis](https://github.com/alexforencich/verilog-axis) ⭐ 912 | 🐛 22 | 🌐 Python | 📅 2025-02-27
  * (Forencich) Verilog AXI stream components for FPGA implementation
* [wb2axip](https://github.com/ZipCPU/wb2axip) ⭐ 697 | 🐛 6 | 🌐 Verilog | 📅 2026-06-02
  * AXI-Wishbone bus bridges
* [tvip-axi](https://github.com/taichi-ishitani/tvip-axi) ⭐ 474 | 🐛 8 | 🌐 SystemVerilog | 📅 2024-06-28
  * UVM based AMBA AXI VIP
* [cocotbext-axi](https://github.com/alexforencich/cocotbext-axi) ⭐ 355 | 🐛 63 | 🌐 Python | 📅 2026-08-24
  * AXI interface modules for Cocotb
* [axi-crossbar](https://github.com/dpretet/axi-crossbar) ⭐ 241 | 🐛 12 | 🌐 SystemVerilog | 📅 2026-05-25
  * AXI4 crossbar implemented in SystemVerilog
* [tvip-apb](https://github.com/taichi-ishitani/tvip-apb) ⭐ 35 | 🐛 1 | 🌐 SystemVerilog | 📅 2023-11-07
  * UVM based AMBA APB VIP

## Analog Circuits

* [openfasoc](https://github.com/idea-fasoc/OpenFASOC) ⭐ 350 | 🐛 41 | 🌐 Python | 📅 2025-10-22
  * Automated Mixed Signal SoC Synthesis Framework
* [ams\_kgd](https://github.com/USCPOSH/AMS_KGD) ⭐ 42 | 🐛 1 | 🌐 MATLAB | 📅 2021-06-10
  * Repository for Known Good Analog Designs (KGDs)
* [open-pmic](https://github.com/westonb/open-pmic) ⭐ 39 | 🐛 0 | 🌐 Tcl | 📅 2021-06-17
  * Current mode buck converter on the SKY130 PDK
* [analog\_blocks](https://github.com/mabrains/Analog_blocks) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2022-07-30
  * Basic building blocks (OTA, BandGap and LDO) in Skywater 130nm.

## Chip Packaging

* [bsg\_packaging](https://github.com/bespoke-silicon-group/bsg_packaging) ⭐ 11 | 🐛 7 | 🌐 Tcl | 📅 2025-07-07
  * Open-Source Hardware Accelerator Packages and Sockets

## Boards

* [parallella-hw](https://github.com/parallella/parallella-hw) ⭐ 421 | 🐛 6 | 🌐 VHDL | 📅 2022-02-12
  * Collection of open source boards from Adapteva
* [google-coral-baseboard](https://github.com/antmicro/google-coral-baseboard) ⭐ 80 | 🐛 3 | 📅 2023-08-07
  * Open hardware baseboard for the Google Coral i.MX8 + Edge TPU SoM
* [hardware-components](https://github.com/antmicro/hardware-components) ⭐ 53 | 🐛 0 | 🌐 Python | 📅 2026-07-27
  * Collection of KiCad components
* [gmm7550](https://github.com/ak-fau/gmm7550) ⭐ 36 | 🐛 0 | 📅 2026-01-17
  * CologneChip GateMate FPGA Module: GMM-7550
* [bsg\_motherboards](https://github.com/bespoke-silicon-group/bsg_motherboards) ⭐ 10 | 🐛 3 | 🌐 Verilog | 📅 2023-08-30
  * BaseJump Hardware Accelerator Motherboards

## Connectivity

* [verilog-ethernet](https://github.com/alexforencich/verilog-ethernet) ⭐ 3,074 | 🐛 141 | 🌐 Verilog | 📅 2025-02-27
  * Verilog Ethernet components for FPGA implementation
* [verilog-pcie](https://github.com/alexforencich/verilog-pcie) ⭐ 1,646 | 🐛 42 | 🌐 Verilog | 📅 2024-04-26
  * Verilog PCI express components
* [hdmi](https://github.com/hdl-util/hdmi) ⭐ 1,290 | 🐛 17 | 🌐 SystemVerilog | 📅 2026-07-13
  * Send video/audio over HDMI on an FPGA
* [usb3\_camera](https://github.com/circuitvalley/USB_C_Industrial_Camera_FPGA_USB3) ⭐ 1,145 | 🐛 0 | 🌐 Verilog | 📅 2026-08-21
  * USB C Industrial Camera Project
* [verilog-i2c](https://github.com/alexforencich/verilog-i2c) ⭐ 723 | 🐛 11 | 🌐 Verilog | 📅 2025-02-27
  * Verilog I2C interface for FPGA implementation
* [litepice](https://github.com/enjoy-digital/litepcie) ⭐ 721 | 🐛 31 | 🌐 Python | 📅 2026-08-25
  * Small footprint and configurable PCIe core
* [vivado-library](https://github.com/Digilent/vivado-library) ⭐ 696 | 🐛 26 | 🌐 C | 📅 2025-12-31
  * IP cores and interface definitions compatible with Xilinx Vivado IP Catalog
* [core\_ddr3\_controller](https://github.com/ultraembedded/core_ddr3_controller) ⭐ 626 | 🐛 4 | 🌐 Verilog | 📅 2021-10-10
  * DDR3 memory controller in Verilog for various FPGAs
* [verilog-uart](https://github.com/alexforencich/verilog-uart) ⭐ 577 | 🐛 10 | 🌐 Verilog | 📅 2025-02-27
  * Verilog UART
* [litedram](https://github.com/enjoy-digital/litedram) ⭐ 540 | 🐛 49 | 🌐 Python | 📅 2026-08-06
  * Small footprint and configurable DRAM (litex)
* [openserdes](https://github.com/SparcLab/OpenSERDES) ⭐ 300 | 🐛 8 | 🌐 Verilog | 📅 2022-03-26
  * Digitally synthesizable architecture for SerDes using Skywater130
* [liteeth](https://github.com/enjoy-digital/liteeth) ⭐ 295 | 🐛 33 | 🌐 Python | 📅 2026-07-02
  * Small footprint and configurable Ethernet core
* [idma](https://github.com/pulp-platform/iDMA) ⭐ 234 | 🐛 30 | 🌐 SystemVerilog | 📅 2026-08-24
  * Modular, parametrizable, and highly flexible Data Movement Accelerator
* [tnoc](https://github.com/taichi-ishitani/tnoc) ⭐ 211 | 🐛 5 | 🌐 SystemVerilog | 📅 2022-08-27
  * Network on Chip Implementation written in SytemVerilog
* [litescope](https://github.com/enjoy-digital/litescope) ⭐ 206 | 🐛 6 | 🌐 Python | 📅 2026-07-25
  * Small footprint and configurable embedded FPGA logic analyzer
* [ravenoc](https://github.com/aignacio/ravenoc) ⭐ 197 | 🐛 1 | 🌐 SystemVerilog | 📅 2024-11-18
  * Configurable HDL NoC (Network-On-Chip)
* [usb\_cdc](https://github.com/ulixxe/usb_cdc/) ⭐ 193 | 🐛 0 | 🌐 Verilog | 📅 2024-03-10
  * Minimal USB CDC (ACM) implementation in verilog
* [umi](https://github.com/zeroasiccorp/umi) ⭐ 162 | 🐛 20 | 🌐 SystemVerilog | 📅 2026-08-25
  * Universal Memory Interface
* [nocrouter](https://github.com/agalimberti/NoCRouter) ⭐ 156 | 🐛 0 | 🌐 SystemVerilog | 📅 2018-03-19
  * Network-on-Chip Router
* [wav-lpddr-hw](https://github.com/waviousllc/wav-lpddr-hw) ⭐ 142 | 🐛 4 | 🌐 SystemVerilog | 📅 2021-07-22
  * DDR (WDDR) Physical interface (PHY) Hardware
* [verilog-wishbone](https://github.com/alexforencich/verilog-wishbone) ⭐ 135 | 🐛 5 | 🌐 Python | 📅 2024-01-05
  * Verilog wishbone components
* [opencapi\_accel](https://github.com/OpenCAPI/oc-accel) ⭐ 77 | 🐛 6 | 🌐 Verilog | 📅 2024-08-29
  * OpenCAPI acceleration framework
* [pymtl3-net](https://github.com/cornell-brg/pymtl3-net) ⭐ 53 | 🐛 14 | 🌐 Python | 📅 2025-03-18
  * Cornell parameterizable OCN (on-chip network) generator
* [i2c](https://github.com/hdl-util/i2c) ⭐ 35 | 🐛 0 | 🌐 SystemVerilog | 📅 2020-05-17
  * Fully featured implementation of Inter-IC (I2C) bus master
* [wav-slink-hw](https://github.com/waviousllc/wav-slink-hw) ⭐ 29 | 🐛 0 | 🌐 Verilog | 📅 2021-07-26
  * Chiplet link
* [usb\_dfu](https://github.com/ulixxe/usb_dfu/tree/main) ⭐ 21 | 🐛 0 | 🌐 Verilog | 📅 2024-03-10
  * Verilog implementation of the USB Device Class Specification
* [vis4mesh](https://github.com/ueqri/vis4mesh) ⭐ 17 | 🐛 1 | 🌐 TypeScript | 📅 2024-01-21
  * Visualization tool for designing mesh Network-on-Chips
* [opencapi\_client](https://github.com/OpenCAPI/OpenCAPI3.0_Client_RefDesign) ⭐ 16 | 🐛 0 | 🌐 Verilog | 📅 2022-11-07
  * OpenCAPI client reference design
* [wav-wlink-hw](https://github.com/waviousllc/wav-wlink-hw) ⭐ 12 | 🐛 1 | 🌐 Scala | 📅 2021-10-28
  * Chiplet link
* [wav-d2d-hw](https://github.com/waviousllc/wav-d2d-hw) ⭐ 11 | 🐛 0 | 🌐 SystemVerilog | 📅 2021-10-13
  * 8lane Wlink with D2D and a single AXI Target/Initiator
* [bsg\_ddr3\_io](https://github.com/bespoke-silicon-group/bsg_ddr3_io) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-03-06
  * BaseJump DDR3 I/O Design
* [io-gen](https://github.com/GT-CHIPS/IO-Gen) ⭐ 3 | 🐛 0 | 🌐 Pascal | 📅 2018-11-11
  * IO cell generator
* [ctucanfd\_ip\_core](https://gitlab.fel.cvut.cz/canbus/ctucanfd_ip_core)
  * CAN with Flexible Data-rate
* [omi\_device\_ice](https://github.eom/OpenCAPI/omi_device_ice)
  * Open memory interface example device

## CPUs

* [openxiangshan](https://github.com/OpenXiangShan/XiangShan) ⭐ 7,213 | 🐛 269 | 🌐 Scala | 📅 2026-08-26
  * Open-source high-performance RISC-V processor
* [picorv32](https://github.com/YosysHQ/picorv32) ⭐ 4,361 | 🐛 87 | 🌐 Verilog | 📅 2026-07-31
  * Size-Optimized RISC-V CPU
* [rocket-chip](https://github.com/chipsalliance/rocket-chip) ⭐ 3,849 | 🐛 344 | 🌐 Scala | 📅 2026-06-02
  * Linux capable RISC-V Rocket Chip Generator
* [cva6](https://github.com/openhwgroup/cva6) ⭐ 3,080 | 🐛 287 | 🌐 Assembly | 📅 2026-08-26
  * Linux capable RISC-V CPU
* [neorv32](https://github.com/stnolting/neorv32) ⭐ 2,241 | 🐛 11 | 🌐 VHDL | 📅 2026-08-22
  * Customizable and highly extensible MCU-class 32-bit RISC-V (VHDL)
* [ibex](https://github.com/lowRISC/ibex) ⭐ 2,026 | 🐛 264 | 🌐 SystemVerilog | 📅 2026-08-20
  * Small 32 bit RISC-V CPU core
* [serv](https://github.com/olofk/serv) ⭐ 1,875 | 🐛 35 | 🌐 Verilog | 📅 2026-08-25
  * SErial RISC-V CPU
* [cores-swerv](https://github.com/chipsalliance/Cores-SweRV) ⭐ 963 | 🐛 28 | 🌐 SystemVerilog | 📅 2026-07-16
  * SweRV EH1 RISC-Vcore
* [black-parrot](https://github.com/black-parrot/black-parrot) ⭐ 827 | 🐛 57 | 🌐 SystemVerilog | 📅 2026-07-13
  * Linux-capable RISC-V multicore
* [microwatt](https://github.com/antonblanchard/microwatt) ⭐ 724 | 🐛 48 | 🌐 Verilog | 📅 2026-08-12
  * Open POWER ISA softcore written in VHDL 2008
* [core-v-verif](https://github.com/openhwgroup/core-v-verif) ⭐ 713 | 🐛 157 | 🌐 Assembly | 📅 2026-08-13
  * Functional verification project for the CORE-V family of RISC-V cores
* [cvw](https://github.com/openhwgroup/cvw) ⭐ 608 | 🐛 31 | 🌐 SystemVerilog | 📅 2026-08-26
  * Configurable RISC-V Processor for RISC-V System-on-Chip Design textbook.
* [cfu-playground](https://github.com/google/CFU-Playground/) ⭐ 561 | 🐛 142 | 🌐 Verilog | 📅 2026-02-26
  * Famework for playing with custom opcodes to accelerate TensorFlow Lite for Microcontrollers
* [ara](https://github.com/pulp-platform/ara) ⭐ 538 | 🐛 134 | 🌐 C | 📅 2026-08-19
  * 64-bit Vector unit coprocessor to Ccva6
* [vroom](https://github.com/MoonbaseOtago/vroom) ⭐ 522 | 🐛 8 | 🌐 Verilog | 📅 2024-09-02
  * High performance RISC-V CPU
* [cores-swerv-el2](https://github.com/chipsalliance/Cores-SweRV-EL2) ⭐ 344 | 🐛 57 | 🌐 SystemVerilog | 📅 2026-08-26
  * SweRV EL2 RISC-V Core
* [veer](https://github.com/chipsalliance/Cores-VeeR-EL2) ⭐ 344 | 🐛 57 | 🌐 SystemVerilog | 📅 2026-08-26
  * 32-bit integer machine-mode RISC-V CPU
* [cv32e40x](https://github.com/openhwgroup/cv32e40x) ⭐ 277 | 🐛 42 | 🌐 SystemVerilog | 📅 2024-11-06
  * RV32IMFCX RISC-V 4-stage compute RISC-V CPU
* [a2i](https://github.com/openpower-cores/a2i) ⚠️ Archived
  * A2I POWER processor core RTL (VHDL)
* [minimax](https://github.com/gsmecher/minimax) ⭐ 228 | 🐛 3 | 🌐 Verilog | 📅 2026-02-19
  * A Compressed-First, Microcoded RISC-V CPU
* [snitch](https://github.com/pulp-platform/snitch) ⚠️ Archived
  * Lean but mean RISC-V system
* [cv32e40s](https://github.com/openhwgroup/cv32e40s) ⭐ 160 | 🐛 6 | 🌐 SystemVerilog | 📅 2024-10-31
  * RV32IMFCX RISC-V 4-stage secure RISC-V CPU
* [muntjac](https://github.com/lowRISC/muntjac) ⭐ 120 | 🐛 4 | 🌐 SystemVerilog | 📅 2025-04-28
  * Simple 64-bit RISC-V multicore processor
* [lizard](https://github.com/cornell-brg/lizard) ⭐ 92 | 🐛 1 | 🌐 Python | 📅 2019-07-29
  * Cornell modular RV64IM Out-of-Order Processor Built with PyMTL
* [cve2](https://github.com/openhwgroup/cve2) ⭐ 68 | 🐛 170 | 🌐 SystemVerilog | 📅 2026-08-19
  * Small two-stage 32 bit RISC-V CPU core (RV32IMC/EMC)
* [rioschip](https://github.com/b224hisl/rioschip) ⭐ 33 | 🐛 0 | 🌐 Verilog | 📅 2022-11-25
  * Out of order RISC-V core

## FPGA Architectures

* [openfpga](https://github.com/lnis-uofu/OpenFPGA) ⭐ 1,136 | 🐛 148 | 🌐 Verilog | 📅 2026-08-26
  * FPGA IP Generator
* [fabulous](https://github.com/FPGA-Research-Manchester/FABulous) ⭐ 285 | 🐛 90 | 🌐 Python | 📅 2026-08-25
  * Fabric generator and CAD tools
* [prga](https://github.com/PrincetonUniversity/prga) ⭐ 211 | 🐛 8 | 🌐 SCSS | 📅 2024-08-08
  * Open-source FPGA research and prototyping framework
* [fabric\_team](https://github.com/ucb-cs250/fabric_team) ⭐ 5 | 🐛 1 | 🌐 Verilog | 📅 2021-06-15
  * Simple Berkeley FPGA generator class project

## Libraries

* [basic\_verilog](https://github.com/pConst/basic_verilog) ⭐ 2,015 | 🐛 0 | 🌐 Verilog | 📅 2026-03-12
  * Library of SystemVerilog components
* [hdl](https://github.com/analogdevicesinc/hdl) ⭐ 2,000 | 🐛 61 | 🌐 Verilog | 📅 2026-08-26
  * Library of Analog Deveices specific components
* [oh](https://github.com/aolofsson/oh) ⚠️ Archived
  * Library of Verilog components
* [Open Logic](https://github.com/open-logic/open-logic) ⭐ 1,006 | 🐛 15 | 🌐 VHDL | 📅 2026-08-25
  * Open Logic FPGA Standard Library
* [common\_cells](https://github.com/pulp-platform/common_cells) ⭐ 791 | 🐛 8 | 🌐 SystemVerilog | 📅 2026-08-21
  * Library of SystemVerilog components
* [basejump\_stl](https://github.com/bespoke-silicon-group/basejump_stl) ⭐ 680 | 🐛 167 | 🌐 SystemVerilog | 📅 2026-07-07
  * Library of SystemVerilog components
* [cvfpu](https://github.com/openhwgroup/cvfpu) ⭐ 632 | 🐛 53 | 🌐 SystemVerilog | 📅 2026-07-24
  * Parametric floating-point unit
* [surf](https://github.com/slaclab/surf) ⭐ 477 | 🐛 11 | 🌐 VHDL | 📅 2026-08-26
  * Giant VHDL library for FPGA development
* [async\_fifo](https://github.com/dpretet/async_fifo) ⭐ 474 | 🐛 1 | 🌐 Verilog | 📅 2026-02-13
  * Dual clock asynchronous FIFO
* [berkeley-hardfloat](https://github.com/ucb-bar/berkeley-hardfloat) ⭐ 390 | 🐛 23 | 🌐 Scala | 📅 2026-08-19
  * Berkeley hardware floating point units
* [lambdapdk](https://github.com/siliconcompiler/lambdapdk) ⭐ 127 | 🐛 3 | 🌐 SourcePawn | 📅 2026-08-19
  * Library of open source Process Design Kits (PDKs)
* [vlsiffra](https://github.com/antonblanchard/vlsiffra) ⭐ 124 | 🐛 17 | 🌐 Python | 📅 2023-09-20
  * Fast and efficient standard cell based adders and multipliers
* [rohd-hcl](https://github.com/intel/rohd-hcl) ⭐ 115 | 🐛 76 | 🌐 Dart | 📅 2026-07-01
  * Library of reusable & configurable hardware components developed with ROHD
* [lambdalib](https://github.com/siliconcompiler/lambdalib) ⭐ 53 | 🐛 7 | 🌐 Python | 📅 2026-08-03
  * Hardware abstraction library
* [pzbcm](https://github.com/pezy-computing/pzbcm) ⭐ 48 | 🐛 0 | 🌐 SystemVerilog | 📅 2026-07-16
  * Basic common modules
* [libsv](https://github.com/bensampson5/libsv) ⭐ 33 | 🐛 5 | 🌐 SystemVerilog | 📅 2024-05-26
  * Parameterized SystemVerilog digital hardware library
* [mathlib](https://github.com/asfigo/mathlib) ⭐ 13 | 🐛 5 | 🌐 SystemVerilog | 📅 2023-09-11
  * SystemVerilog MathLib
* [pztb-core](https://github.com/pezy-computing/pztb-core) ⭐ 11 | 🐛 0 | 🌐 SystemVerilog | 📅 2026-06-24
  * Collection of class libraries for testbench development

## Memory

* [openram](https://github.com/VLSIDA/OpenRAM) ⭐ 1,119 | 🐛 61 | 🌐 Python | 📅 2026-08-16
  * Static random access memory (SRAM) compiler.
* [cv-hpdcache](https://github.com/openhwgroup/cv-hpdcache) ⭐ 112 | 🐛 5 | 🌐 SystemVerilog | 📅 2026-08-19
  * High-Performance L1 Dcache
* [huancun](https://github.com/OpenXiangShan/HuanCun) ⭐ 100 | 🐛 3 | 🌐 Scala | 📅 2026-06-17
  * Open-source high-performance non-blocking cache
* [core\_axi\_cache](https://github.com/ultraembedded/core_axi_cache) ⭐ 59 | 🐛 0 | 🌐 Verilog | 📅 2021-05-10
  * 128KB AXI cache (32-bit in, 256-bit out)
* [bsg\_fakeram](https://github.com/bespoke-silicon-group/bsg_fakeram) ⭐ 44 | 🐛 5 | 🌐 Python | 📅 2023-01-13
  * Fake RAM generator
* [lake](https://github.com/StanfordAHA/lake) ⭐ 24 | 🐛 14 | 🌐 Python | 📅 2026-08-26
  * Synthesizable memory generator

## Systems

* [litex](https://github.com/enjoy-digital/litex) ⭐ 4,061 | 🐛 110 | 🌐 Python | 📅 2026-08-25
  * SoC builder framework
* [opentitan](https://github.com/lowRISC/opentitan) ⭐ 3,607 | 🐛 2,048 | 🌐 SystemVerilog | 📅 2026-08-26
  * Open source silicon root of trust
* [metroboy](https://github.com/aappleby/metroboy) ⭐ 1,170 | 🐛 4 | 🌐 C++ | 📅 2025-02-23
  * Gate-level simulators and tools for the original Game Boy
* [openwifi-hw](https://github.com/open-sdr/openwifi-hw) ⭐ 891 | 🐛 19 | 🌐 Verilog | 📅 2025-09-23
  * IEEE 802.11 WiFi baseband FPGA (chip) design
* [openpiton](https://github.com/PrincetonUniversity/openpiton) ⭐ 810 | 🐛 60 | 🌐 Assembly | 📅 2026-02-25
  * General purpose, multithreaded manycore processor
* [pulp](https://github.com/pulp-platform/pulp) ⭐ 565 | 🐛 39 | 🌐 SystemVerilog | 📅 2024-11-26
  * Multicore RISC-V based SoC
* [verilogboy](https://github.com/zephray/VerilogBoy) ⭐ 542 | 🐛 5 | 🌐 Verilog | 📅 2022-12-10
  * Game Boy compatible machine with Verilog
* [beagle\_sdr\_gps](https://github.com/jks-prv/Beagle_SDR_GPS) ⚠️ Archived
  * KiwiSDR: BeagleBone web-accessible GPS/SDR
* [pulpissimo](https://github.com/pulp-platform/pulpissimo) ⭐ 493 | 🐛 138 | 🌐 SystemVerilog | 📅 2026-05-08
  * Single core RISC-V based SoC
* [caliptra](https://github.com/chipsalliance/caliptra) ⭐ 457 | 🐛 134 | 📅 2026-08-17
  * Caliptra Root of Trust Architecture
* [esp](https://github.com/sld-columbia/esp) ⭐ 421 | 🐛 40 | 🌐 C | 📅 2026-08-25
  * Heterogeneous SoC architecture and IP design platform
* [falcon](https://github.com/falkenber9/falcon) ⭐ 360 | 🐛 16 | 🌐 C++ | 📅 2023-10-13
  * Fast Analysis of LTE Control channels
* [openfasoc](https://github.com/idea-fasoc/OpenFASOC) ⭐ 350 | 🐛 41 | 🌐 Python | 📅 2025-10-22
  * Open Source FASOC generators
* [bsg\_manycore](https://github.com/bespoke-silicon-group/bsg_manycore) ⭐ 302 | 🐛 93 | 🌐 SystemVerilog | 📅 2026-07-27
  * Tile based architecture designed for efficiency & scalability
* [x-heep](https://github.com/esl-epfl/x-heep) ⭐ 294 | 🐛 136 | 🌐 C | 📅 2026-08-26
  * Extendable and configurable RISC-V SoC
* [caliptra-rtl](https://github.com/chipsalliance/caliptra-rtl) ⭐ 150 | 🐛 153 | 🌐 SystemVerilog | 📅 2026-08-26
  * Caliptra Root of Trust (RTL)
* [wulpus](https://github.com/pulp-bio/wulpus) ⭐ 118 | 🐛 6 | 🌐 C | 📅 2026-08-11
  * Wearable low-power ultrasound probe
* [hero](https://github.com/pulp-platform/hero) ⚠️ Archived
  * FPGA-based research platform for heterogeneous design
* [rose](https://github.com/ucb-bar/RoSE) ⭐ 47 | 🐛 3 | 🌐 C | 📅 2026-08-10
  * Unified simulation platform for robotic systems
* [senseq](https://github.com/EMIL-YORKU/SensSeq) ⭐ 35 | 🐛 1 | 📅 2022-11-30
  * Mixed-signal system on chip for nanopore-based DNA sequencing
* [cep](https://github.com/CommonEvaluationPlatform/CEP) ⭐ 26 | 🐛 26 | 🌐 C | 📅 2024-09-26
  * RISC-V based Common Evaluation Platform (CEP)

## Boards

* [icebreaker](https://github.com/icebreaker-fpga/icebreaker) ⚠️ Archived
  * Low cost FPGA development board
* [PicoEVB](https://github.com/RHSResearchLLC/PicoEVB) ⭐ 270 | 🐛 5 | 🌐 C | 📅 2025-12-03
  * M.2 80mm Artix FPGA evaluation board
* [fomu](https://github.com/im-tomu/fomu-hardware) ⭐ 233 | 🐛 4 | 📅 2023-01-10
  * Tiny USB FPGA board
* [scalenode-cm4-baseboard](https://github.com/antmicro/scalenode-cm4-baseboard) ⭐ 151 | 🐛 3 | 📅 2024-04-03
  * Antmicro basedboard for RPI CM4
* [artix-dc-scm](https://github.com/antmicro/artix-dc-scm) ⭐ 71 | 🐛 5 | 📅 2025-12-11
  * Antmicro OCP data center secure control module
* [qomu-dev-board](https://github.com/QuickLogic-Corp/qomu-dev-board) ⭐ 43 | 🐛 3 | 📅 2021-03-24
  * Quicklogic efpga USB dev board
* [sodimm-ddr5-tester](https://github.com/antmicro/sodimm-ddr5-tester) ⭐ 34 | 🐛 0 | 📅 2025-12-11
  * Antmicro ddr5 tester board
* [lpddr5-testbed](https://github.com/antmicro/lpddr5-testbed) ⭐ 14 | 🐛 0 | 📅 2025-12-11
  * Antmicro lpddr5 testbed
* [arty-mpw-tester](https://github.com/antmicro/arty-mpw-tester) ⭐ 5 | 🐛 0 | 📅 2025-12-11
  * Antmicro Caravel fanout board

# Education

## Analog Design

* [book-on-mos-stagse](https://github.com/bmurmann/Book-on-MOS-stages) ⭐ 391 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-17
  * Analysis and Design of Elementary MOS Amplifier Stages
* [SiliWiz](https://tinytapeout.com/siliwiz/introduction/)
  * Browser based interactive circuit design tool.

## Board Design

## Digital Design

* [cornell-ece4750](https://github.com/cornell-ece4750)
  * ECE 4750 Computer Architecture
* [cornell-ece5745](https://github.com/cornell-ece5745)
  * ECE 5745 Complex Digital ASIC Design
* [stanford-ee272a](https://priyanka-raina.github.io/ee272a-winter2021)
  * EE272A Design Projects in VLSI Systems I
* [stanford-ee272b](https://priyanka-raina.github.io/ee272b-spring2021)
  * EE272B Design Projects in VLSI Systems II

## FPGA Design

***

# Other Awesome Lists

* [drom](https://github.com/drom/awesome-hdl) ⭐ 1,169 | 🐛 2 | 📅 2026-07-09
  * HDL languages
* [delftopenhardware](https://github.com/delftopenhardware/awesome-open-hardware) ⭐ 1,033 | 🐛 2 | 📅 2026-08-20
  * Open hardware materials
* [kicad-3rd-party-tools](https://github.com/devbisme/kicad-3rd-party-tools) ⭐ 839 | 🐛 4 | 📅 2026-05-15
  * List of 3rd party KiCad software packages
* [semiconduoctor-startups](https://github.com/aolofsson/awesome-semiconductor-startups) ⭐ 771 | 🐛 74 | 🌐 Python | 📅 2026-05-30
  * Semiconductor startups
* [computer-engineering-resources](https://github.com/rajesh-s/computer-engineering-resources) ⭐ 627 | 🐛 1 | 📅 2026-01-30
  * A curated list of Computer Engineering/Architecture resources
* [joamateb](https://github.com/joamatab/awesome_photonics) ⭐ 623 | 🐛 7 | 🌐 Makefile | 📅 2026-01-05
  * Photonics
* [ben-marshall](https://github.com/ben-marshall/awesome-open-hardware-verification) ⭐ 619 | 🐛 3 | 📅 2026-01-03
  * Hardware verification
* [mattvenn](https://github.com/mattvenn/awesome-opensource-asic-resources) ⭐ 413 | 🐛 1 | 📅 2023-04-13
  * ASIC resources
* [hdl](https://github.com/hdl/awesome) ⭐ 176 | 🐛 18 | 🌐 Shell | 📅 2026-08-21
  * Hardware description resources
* [pkuzjx](https://github.com/pkuzjx/eda-collection) ⭐ 113 | 🐛 0 | 📅 2019-12-05
  * Open source EDA resources

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
