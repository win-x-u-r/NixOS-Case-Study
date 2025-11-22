# The Unbreakable System: A NixOS Case Study

A comprehensive academic case study exploring NixOS, a declarative Linux distribution built on the Nix package manager.

## Overview

This paper provides an in-depth analysis of NixOS, examining its purely functional approach to system management and comparing it with traditional Linux methodologies. Written for CSCI 312 at the American University of Ras Al Khaimah.

## Key Topics

### OS Analysis
- **Process and Thread Management**: Linux kernel's unified task abstraction model
- **Process Scheduling**: Completely Fair Scheduler (CFS) and red-black tree implementation
- **Synchronization**: Spinlocks, mutexes, semaphores, and atomic operations
- **Deadlock Handling**: Prevention strategies including resource ordering and timeouts
- **Memory Management**: Virtual memory, paging, swapping, and zramSwap
- **File Management**: Comparison of imperative vs. functional approaches

### NixOS Features
- **Declarative Configuration**: Single `configuration.nix` file for entire system
- **Atomic Upgrades**: System updates are all-or-nothing transactions
- **Rollback Capability**: Easy reversion to previous configurations
- **Nix Store**: Unique cryptographic hash-based package storage at `/nix/store/`
- **Reproducibility**: Build recipes (derivations) ensure consistent environments

### Legal and Ethical Considerations
- Software licensing and FOSS compliance
- Data privacy and telemetry concerns
- Security vulnerability handling
- Governance and community dynamics
- Non-compliance with Filesystem Hierarchy Standard (FHS)

## Implementation

The paper includes practical guidance on:
- Installing NixOS (VM and bare-metal)
- Resource monitoring with KDE tools
- System call tracing using `strace` and `ftrace`

### Performance Metrics
Testing on Intel i5-12450HX with 28GB RAM showed:
- **Idle**: 0.7% CPU, 2.9GB RAM
- **Average Work**: 4% CPU, 6GB RAM
- **Stress Test**: 95.8% CPU, 25.6GB RAM

## Authors

- Hazim Kaloub (2023005883)
- Adnan Shanbour (2022005845)
- Ahmed Gani (2022005563)
- Additional contributors listed in paper

## Course Information

**Course**: CSCI 312  
**Instructor**: Dr. Zubaidah Alhazza  
**Institution**: American University of Ras Al Khaimah  
**Academic Year**: 2024-2025

## Further Reading

The paper includes references to seminal works by Eelco Dolstra and other NixOS/Nix documentation, available in the Further Readings section.

## License

This academic work is subject to university guidelines and copyright policies.
