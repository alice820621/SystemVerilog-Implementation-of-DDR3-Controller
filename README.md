# SystemVerilog-Implementation-of-DDR3-Controller
This is a group project. The controller is a Verilog implementation through a state machine structure per Micro datasheet specifications, and connected to a predefined DDR3 memory. Successful design verification is achieved via a specialized test bench and connected to provided AHB by a SystemVerilog interface.


- top.sv			top module
- ddr3_controller.sv		a ddr3 memory controller
- st_defs.svh			a parameter for ddr3_controller.sv, controller states
- intf.sv			an interface to connect ddr3_controller.sv and ddr3.v

- ddr3.v			a given ddr3 memory
- 1024Mb_ddr3_parameters.vh	a given parameter for ddr3.v
- sg093.v			a given parameter for ddr3.v
- defs.svh			a given parameter for ddr3.v





