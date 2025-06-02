# Network Traffic Capture and Analysis

This repository contains a **Wireshark packet capture** file (`network_capture.pcapng`) and a **detailed report** (`Report.md`) summarizing the captured network traffic and identified protocols. The objective of this task was to capture and analyze live network packets and recognize various protocols such as HTTP, DNS, and TCP.

## Project Overview
The primary goal of this project was to demonstrate the ability to:
- Capture live network traffic using **Wireshark**.
- Analyze and identify various network protocols from the captured data.
- Understand the behavior of protocols such as **HTTP**, **DNS**, and **TCP** in a typical network environment.

## Files
This repository includes the following files:
- **`network_capture.pcapng`**: A packet capture file containing network traffic, showing the interaction of **HTTP**, **DNS**, and **TCP** protocols. This file was captured using Wireshark.
- **`Report.md`**: A markdown file containing a summary and analysis of the captured protocols. It includes details on how HTTP, DNS, and TCP traffic was captured, as well as an explanation of what was observed in the packet analysis.

## How to Use
- To view the packet capture, download the **`network_capture.pcapng`** file and open it in **Wireshark**. Wireshark will display detailed packet-level information.
- Use the filter options in Wireshark to focus on specific protocols such as `http`, `dns`, or `tcp`.
- The **`Report.md`** provides a detailed breakdown of the protocols identified during the capture, and it explains the packet analysis process.

## Analysis Highlights
- **HTTP (HyperText Transfer Protocol)**: Used for loading web pages and transmitting data between web browsers and servers.
- **DNS (Domain Name System)**: Responsible for resolving domain names (like google.com) into their corresponding IP addresses.
- **TCP (Transmission Control Protocol)**: A connection-oriented protocol used for reliable data transmission across the network.

## Conclusion
This project serves as an introduction to network traffic capture and protocol analysis, enhancing the understanding of how different protocols operate within a network and how to monitor and troubleshoot network traffic effectively using tools like Wireshark.

---

Feel free to open the **.pcapng** file in Wireshark to explore the packet-level details or refer to the **`Report.md`** for a deeper understanding of the analysis.
