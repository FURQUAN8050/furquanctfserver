# furquanctfserver
A CTF server using Ubuntu Server is a training machine for cybersecurity practice. It has Port 22 (SSH) for remote access and Port 80 (HTTP) for hosting a website. A hidden resume file is placed as a clue for players to find and continue the challenge.
# CTF Machine Project

## Overview

This project is a custom Capture The Flag (CTF) machine built for cybersecurity practice and learning.
The machine is designed to simulate a vulnerable environment where players can perform enumeration, exploitation, privilege escalation, and flag capturing.

## Objective

The goal of this machine is to:

* Practice penetration testing skills
* Learn Linux privilege escalation
* Improve web enumeration techniques
* Understand hidden file and steganography concepts

## Machine Specifications

* **Operating System:** Ubuntu Server
* **Open Ports:** 22 (SSH), 80 (HTTP)
* **Difficulty Level:** Beginner to Intermediate

## Features

* Hidden resume file inside the web server
* Multiple clues embedded in HTML comments and source code
* SSH login with low-privilege user
* Privilege escalation via misconfigured sudo permissions
* Hidden flags for user and root access

## Tools Recommended

* Nmap
* Gobuster
* Netdiscover
* Hydra
* Steghide
* LinPEAS

## Walkthrough

1. Discover target IP address.
2. Scan open ports using Nmap.
3. Enumerate the web server.
4. Find hidden clues in source code.
5. Gain SSH access.
6. Escalate privileges.
7. Capture all flags.

## Flags

* User Flag: `/home/tim/user.txt`
* Root Flag: `/root/root.txt`

## Disclaimer

This machine is created for educational purposes only. Do not deploy in public environments.

## Author

Created by Mohd Furquan Ullah
