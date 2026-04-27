Day 1: DevOps Fundamentals & Linux Basics
1. What is DevOps?

Definition: DevOps is a culture or practice aimed at improving an organization's ability to deliver applications quickly and with high quality.  

The Goal: To reduce delivery time (e.g., from 2 weeks to 1 week) by ensuring automation, continuous testing, and monitoring are in place.  
Core Components:
CI/CD: Continuous Integration and Continuous Deployment.  
Automation: Improving efficiency by removing manual efforts that slow down the process.  
Monitoring & Testing: Ensuring constant quality checks and system health tracking.  


2. Software Development Life Cycle (SDLC)
SDLC is a set of standards used to design, develop, test, and deploy high-quality software.  

Phases: Requirement Gathering → Planning → Designing (HLD/LLD) → Building (Coding) → Testing → Deployment.  
Devops Role: Primarily focuses on automating the Building, Testing, and Deployment phases to ensure a fast and manual-intervention-free process.


3. Introduction to Linux

Why Linux?: It is the preferred OS for developers (80-90% of the time) because it is open-source, free, fast, and highly secure. 

Core Components:

Kernel: The heart of the OS; it manages communication between hardware and software. Responsibilities include Device, Memory, and Process management.  
System Libraries: Responsible for performing tasks by sending requests to the Kernel.  
Shell: The interface used to talk to the Operating System via commands. 



4. Essential Linux Commands - what i learned today.

ls: List files and folders.  

pwd: Show the present working directory.  

cd <directory>: Change directory; use cd .. to go back one level.  

touch <filename>: Create a new empty file.  

mkdir <name>: Create a new directory.  

cat <filename>: View file content.  

chmod 777 <filename>: Grant full read/write/execute permissions to everyone.  

df -h: Check disk space usage.  

top: View real-time CPU and memory details.  



5. Shell Scripting Basics

Purpose: To automate repetitive daily manual activities on a Linux system.  

Shebang (#!/bin/bash): The first line in a script that tells the Kernel which shell to use to execute the file.  
Good Practices:
Use set -x for debug mode to see which commands are being executed.  
Use set -e to make the script exit immediately if a command fails.  
Use set -o pipefail to ensure the script catches errors within piped commands.  



6. Virtualization

Virtual Machines (VM): Logical partitions of a physical server that function as independent computer systems with their own CPU and memory.  

Hypervisor: Software (like VMware or Xen) installed on a physical server to create and manage multiple virtual machines, leading to better resource efficiency.
