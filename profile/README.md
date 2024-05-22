RISCY-Lib
=========

RISCY-Lib is an opensource collection of RTL (mainly SystemVerilog) design and verification Tools.

Interfaces
-----------

- [interfaces](https://github.com/RISCY-Lib/interfaces)
  - A repo which contains the latest of every interface
- [uart_if](https://github.com/RISCY-Lib/uart_if)
- [axilite_if](https://github.com/RISCY-Lib/axilite_if)

UVM Packages
------------

### Agents

- [uart_agent](https://github.com/RISCY-Lib/uart_agent)
  - A full featured UART agent
- [sram_reactive_agent](https://github.com/RISCY-Lib/sram_reactive_agent)
  - A reactive agent acting as an SRAM block
- [clk_rst_agent](https://github.com/RISCY-Lib/clk_rst_agent)
  - A driver agent for Clock and Reset Signals

### Layering Agents

- [uart2register_layering_agent](https://github.com/RISCY-Lib/uart2register_layering_agent)
  - A UVM Layering Agent for the UART2Register Packet

### Misc

- [uvm_utils](https://github.com/RISCY-Lib/uvm_utils)
  - A collection of useful UVM headers
- [colored_reporter](https://github.com/RISCY-Lib/colored_reporter)
  - A UVM Report Server which adds color to outputs

RTL Modules
-----------

- [uart2sram](https://github.com/RISCY-Lib/uart2sram)
  - A module which converts the UART2Register Packet to an SRAM interface
