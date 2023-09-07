# AMBA-APB-Protocol-Design-and-Verification-using-SV
# Introduction
This project designs and verifies the AMBA APB protocol using SystemVerilog. The AMBA APB protocol is a low-speed, low-complexity bus protocol that connects peripherals to a processor. The protocol is designed to be simple and efficient, making it ideal for low-cost and low-power applications.

The project is implemented using SystemVerilog, a hardware description language (HDL) used to describe electronic systems' behaviour. SystemVerilog is a powerful language that can be used to model systems' functional and timing behaviour.

The project is divided into two parts: the design and the verification. The design part describes the AMBA APB protocol and the implementation of the protocol in SystemVerilog. The verification part describes the test cases used to verify the design.

# Design
The AMBA APB protocol consists of four main components: the master, the slave, the bus, and the arbiter. The master is the device that initiates a bus transaction. The slave is the device that responds to a bus transaction. The bus is the medium that connects the master and the slave. The arbiter is the device that arbitrates between multiple masters for access to the bus.

The design of the AMBA APB protocol in SystemVerilog is divided into two parts: the master and the slave. The master is implemented as a module with four ports: the address port, the data port, the control port, and the clock port. The address port is used to send the address of the data that is being accessed. The data port is used to send and receive data. The control port sends control signals, such as read and write. The clock port synchronises the transactions between the master and the slave.

The slave is also implemented as a module with four ports: the address port, the data port, the control port, and the clock port. The address port is used to receive the address of the data that is being accessed. The data port is used to send and receive data. The control port receives control signals, such as read and write. The clock port synchronises the transactions between the master and the slave.

# Verification
The AMBA APB protocol was verified using a combination of manual and automated testing. Manual testing was done to verify the basic functionality of the protocol. The automated testing was done to verify the protocol under various conditions.

The manual testing was done by writing a testbench that simulates the AMBA APB protocol. The testbench sends various bus transactions to the master and slave modules and verifies that the modules respond correctly.

The automated testing was done using a tool called SystemVerilog Testbench Compiler (STVC). STVC is a tool that generates test cases from a formal protocol specification. The test cases were then used to verify the protocol under various conditions, such as bus speeds and data sizes.

# Conclusion
This project has successfully designed and verified the AMBA APB protocol using SystemVerilog. Using the AMBA APB protocol, the project can be used as a starting point for other projects.

The project can be improved by adding more features to the protocol, such as support for interrupts and DMA. Adding more test cases to the verification suite can also improve the project.
