# XilinxFPGA
This project entails the development of a high-frequency trading (HFT) subsystem designed for Xilinx FPGAs. It offers an exceptionally low latency, with a roundtrip time of less than 450 nanoseconds, to provide an abstracted view of a FAST (FIX Adapted For Streaming) financial data Ethernet feed. The primary concept behind this subsystem is to separate the common components of an HFT system, such as efficient networking, encoding/decoding, market data sorting, and storage, into a user-friendly module accessible entirely through AXI Streams. This modular approach enables the construction of more specialized HFT trading algorithms on top of it.

Additionally, the module supports timestamping outgoing orders, allowing for in-hardware latency profiling.
