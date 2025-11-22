<div align="center">

# 🛡️ The Unbreakable System: A NixOS Case Study

[![NixOS](https://img.shields.io/badge/NixOS-5277C3?style=for-the-badge&logo=nixos&logoColor=white)](https://nixos.org/)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![License](https://img.shields.io/badge/License-Academic-blue?style=for-the-badge)](https://github.com/win-x-u-r/NixOS-Analysis-Paper)

*A comprehensive academic case study exploring NixOS, a declarative Linux distribution built on the Nix package manager*

[Overview](#overview) • [Key Topics](#key-topics) • [Performance](#performance-metrics) • [Authors](#authors)

</div>

---

## 📋 Overview

This paper provides an in-depth analysis of **NixOS**, examining its purely functional approach to system management and comparing it with traditional Linux methodologies. 

> **Course**: CSCI 312  
> **Institution**: American University of Ras Al Khaimah  
> **Academic Year**: 2024-2025

---

## 🔍 Key Topics

### 🖥️ OS Analysis

| Topic | Description |
|-------|-------------|
| **Process & Thread Management** | Linux kernel's unified task abstraction model |
| **Process Scheduling** | Completely Fair Scheduler (CFS) and red-black tree implementation |
| **Synchronization** | Spinlocks, mutexes, semaphores, and atomic operations |
| **Deadlock Handling** | Prevention strategies including resource ordering and timeouts |
| **Memory Management** | Virtual memory, paging, swapping, and zramSwap |
| **File Management** | Comparison of imperative vs. functional approaches |

### ⚙️ NixOS Features

```mermaid
graph LR
    A[NixOS] --> B[Declarative Config]
    A --> C[Atomic Upgrades]
    A --> D[Rollback]
    A --> E[Nix Store]
    A --> F[Reproducibility]
```

- **🔧 Declarative Configuration**: Single `configuration.nix` file for entire system
- **⚡ Atomic Upgrades**: System updates are all-or-nothing transactions
- **↩️ Rollback Capability**: Easy reversion to previous configurations
- **📦 Nix Store**: Unique cryptographic hash-based package storage at `/nix/store/`
- **🔄 Reproducibility**: Build recipes (derivations) ensure consistent environments

### ⚖️ Legal and Ethical Considerations

- ✅ Software licensing and FOSS compliance
- 🔒 Data privacy and telemetry concerns
- 🛡️ Security vulnerability handling
- 👥 Governance and community dynamics
- 📁 Non-compliance with Filesystem Hierarchy Standard (FHS)

---

## 🚀 Implementation

The paper includes practical guidance on:

- 💿 Installing NixOS (VM and bare-metal)
- 📊 Resource monitoring with KDE tools
- 🔍 System call tracing using `strace` and `ftrace`

### 📈 Performance Metrics

> Testing on **Intel i5-12450HX** with **28GB RAM**

| Workload | CPU Usage | RAM Usage |
|----------|-----------|-----------|
| 🟢 Idle | 0.7% | 2.9GB |
| 🟡 Average Work | 4% | 6GB |
| 🔴 Stress Test | 95.8% | 25.6GB |

---

## 👥 Authors

<table>
  <tr>
    <td align="center">
      <b>Hazim Kaloub</b><br>
      <sub>2023005883</sub>
    </td>
    <td align="center">
      <b>Adnan Shanbour</b><br>
      <sub>2022005845</sub>
    </td>
    <td align="center">
      <b>Ahmed Gani</b><br>
      <sub>2022005563</sub>
    </td>
  </tr>
</table>

*Additional contributors listed in paper*

---

## 📚 Course Information

| | |
|---|---|
| **Course** | CSCI 312 |
| **Instructor** | Dr. Zubaidah Alhazza |
| **Institution** | American University of Ras Al Khaimh |
| **Academic Year** | 2024-2025 |

---

## 📖 Further Reading

The paper includes references to seminal works by **Eelco Dolstra** and other NixOS/Nix documentation, available in the Further Readings section.

---

## 📄 License

This academic work is subject to university guidelines and copyright policies.

---

<div align="center">

**[⬆ back to top](#-the-unbreakable-system-a-nixos-case-study)**

Made with ❤️ for CSCI 312

</div>
