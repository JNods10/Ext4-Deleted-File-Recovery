# Ext4 File Recovery Tool

## Overview

This project comes from the initial work done for my Master's degree thesis.  I have designed a tool to recover deleted files from the Ext4 file system using a Bash script and The Sleuth Kit (tsk). 
The tool automates the recovery process, making it easier for digital forensics professionals to retrieve valuable data from damaged or compromised file systems.  The current version is being adapted to be 
run using python and extended to allow for the recovery of larger and more complicated files.  

## Features

- **Automated Recovery**: Uses a Bash script to streamline the recovery process.
- **Integration with The Sleuth Kit (tsk)**: Leverages powerful TSK utilities for efficient file recovery.
- **User-Friendly**: Simple command-line interface for ease of use.

## Background

The Ext4 file system is widely used in Linux environments. However, deleted files are not immediately erased from the disk, making recovery possible through forensic techniques.  A crucial difference between Ext4 and previous file system versions is the implementation of journaling for file system changes.  The change to journaling creates the imperative to figure out a new technique and method to recover
deleted files.  Some tools exist but lack comprehensiveness and are no longer maintained.  This project was developed to provide the stepping stones toward a reliable solution for recovering deleted files from Ext4 file systems.

## Recognition

I am proud to announce that this work was accepted to the **2024 DFRWS** (Digital Forensics Research Workshop), the premier digital forensics conference in the world, held at Louisiana State University (LSU). Additionally, I was awarded a scholarship from the **National Science Foundation (NSF)** to attend this conference and present my work.
