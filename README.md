# synsha
Optimized implementation of the SHA-256 hashing algorithm in the synchronous language Quartz. The implementation has been synthesized to Verilog using the [averest](http://www.averest.org) framework. Testing on Xilinx FPGA resulted in more that 1 Gbps throughput. Documentation is available in /doc. The project includes the following:
 * **UserModule.qrz**: main implementation.
 * **TestModule.qrz**: Test wrapper.
 * **ROMHashRead.qrz**: inner-loop hashing seperated to enable Xilinx tools to infer a BROM.
 * **InitializeConstants**: initializes the 64 constants required by SHA-256.
  
 

