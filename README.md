Packet Sniffer

A lightweight Java based packet sniffer designed for learning and demonstrating how network packets are captured and interpreted. This project showcases how low level network traffic can be monitored in real time using Java and provides a clear example of how sniffing utilities work behind the scenes.

Overview

This application reads raw network packets from the system network interface and processes them to display useful information such as source and destination addresses, protocols, and payload data. It is intended for educational and demonstration purposes and offers a simple starting point for understanding network level analysis.

Features

Packet capture from active network interfaces
Protocol identification including common transport layer protocols
Real time packet stream display for monitoring traffic as it flows
Modular structure that makes it easy to extend or adapt for deeper analysis

Project Structure

src
Contains all the Java source code and logic for capturing and displaying network packets

nbproject
Standard NetBeans project configuration used to build and run the application

manifest.mf
Basic metadata for the application

README
Project documentation

Note
Build folders and output artifacts are intentionally excluded to maintain a clean repository

How It Works

The application listens on a selected network interface and reads raw data packets. It then extracts important fields from each packet and prints a structured output that helps visualize what is happening on the network in real time. The project demonstrates core networking concepts including frames, headers, protocols, and packet level inspection.

How to Build

This project can be built using NetBeans or any Java IDE that supports Ant based builds.

Steps
Open the project folder in your IDE
Ensure the Java Development Kit is configured
Build the project using the default build command in your IDE

This will compile the source code and generate the runnable output

How to Run

Launch the built application from your IDE or run the generated output JAR file using Java. Once running the program begins capturing and displaying packet details from the selected network interface.

Use Cases

Learning how packet sniffers work at a basic level
Understanding network traffic flow and inspection
A simple reference implementation for networking projects
Demonstrating packet level analysis in interviews or classroom settings

Future Improvements

Add filtering options for specific protocols
Export packet details into human readable logs
Add a graphical interface for visualizing packet flow
Implement deeper protocol level decoding
