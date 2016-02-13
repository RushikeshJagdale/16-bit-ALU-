# 16-bit-ALU-
Design 16-bit ALU using Verilog

In a top-down design approach, the top-level block/module and identify the sub-blocks/modules necessary to build the top-level block/module Main_module. Further subdivide the sub-blocks/modules adder, subtractor, multiplier and shifter until we come to leaf cells, which are the cells that cannot further be divided. Here the leaf cells are cla_logic and PFAdder block/module, in which gate level design is done. The multiplier and shifter modules are designed using behavioral approach.

The Adder used is the Carry Look Ahead Adder of 16 bit wide. The main top level module Main_module for 16 bit ALU calls the sub-module adder, subtractor, multiplier and shifter depending upon the select lines of the mux. Further the sub-modules are constructed by designing leaf cells cla_logic and PFAdder. These leaf cells are designed using gate level approach.
