# ZeroTier Software Switched Network Exercise

Welcome to the ZeroTier Software Switched Network Exercise repository. This project involves creating a software-switched network using ZeroTier and connecting two computers. Below you will find detailed steps for setting up your network, verifying connections, and submitting proof of your successful configuration.

## Overview of ZeroTier

ZeroTier is a smart, programmable Ethernet switch that connects devices globally as if they were in the same physical data center. It combines a secure peer-to-peer network layer (VL1) with an Ethernet emulation layer (VL2), similar to VXLAN, offering features like micro-segmentation and security monitoring. All traffic over ZeroTier is encrypted with keys controlled by the user.

## Prerequisites

Visit [ZeroTier's website](https://www.zerotier.com/) to familiarize yourself with its functionalities and features.

## Setup Instructions

1. **Create a ZeroTier Account and Network:**
  - Sign up at ZeroTier and create a new network. This network will serve as your virtual space for connecting devices.

2. **Install ZeroTier on Two Computers:**
  - Download and install the ZeroTier application on two separate computers that you intend to connect.

3. **Join the Network:**
  - Using the network ID you created, join both computers to your ZeroTier network.

## Verification

4. **Verify Network Connection:**
  - Ensure both computers are visible to each other on the ZeroTier interface. This confirms they are part of your switched network.

5. **Check IP Configuration:**
  - On both computers, open your terminal (Command Prompt in Windows, Terminal in macOS) and run `ipconfig` (Windows) or `ifconfig` (macOS) to display the network configuration. Verify that ZeroTier has assigned IP addresses to both devices.

## Submission

6. **Capture and Submit Screenshots:**
  - Take a screenshot of the ZeroTier page showing both computers in the network.
  - Capture the output of `ipconfig` or `ifconfig` from the first computer.
  - Capture the output of `ipconfig` or `ifconfig` from the second computer.
