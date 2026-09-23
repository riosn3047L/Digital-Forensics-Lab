# Digital Forensics Lab

![Subject](https://img.shields.io/badge/Subject-Digital_Forensics-blue.svg)
![Status](https://img.shields.io/badge/Status-In_Progress-success.svg)

This repository contains practical laboratory experiments and demonstrations for **Digital Forensics**. It covers forensic imaging, memory acquisition and analysis, data recovery, network traffic analysis, email forensics, digital investigation, Android forensics, steganalysis, system activity analysis, and basic malware analysis.

Each experiment is documented in its respective directory with detailed procedures, screenshots, observations, findings, and a PDF report.

---

## Table of Contents

| Exp No. | Topic / Experiment Name | Documentation | PDF |
| :---: | :--- | :---: | :---: |
| **01** | Create a forensic image using FTK Imager, capture volatile memory using WinPmem, and analyze the memory image using Volatility 3 | [README](./Exp-1/README.md) | [PDF](./Exp-1/Exp-1.pdf) |
| **02** | Recover deleted or damaged files from a storage device using TestDisk | [README](./Exp-2/README.md) | [PDF](./Exp-2/Exp-2.pdf) |
| **03** | Capture and analyze network traffic to identify suspicious activities using Wireshark | [README](./Exp-3/README.md) | [PDF](./Exp-3/Exp-3.pdf) |
| **04** | Analyze email headers and identify phishing or email spoofing attacks using Mail Header Analyzer (MHA) or MXToolbox Email Header Analyzer | [README](./Exp-4/README.md) | [PDF](./Exp-4/Exp-4.pdf) |
| **05** | Create a digital forensic case, import evidence, recover deleted files, and generate investigation reports using Autopsy | [README](./Exp-5/README.md) | [PDF](./Exp-5/Exp-5.pdf) |
| **06** | Examine file systems, metadata, timelines, and deleted files using The Sleuth Kit (TSK) | [README](./Exp-6/README.md) | [PDF](./Exp-6/Exp-6.pdf) |
| **07** | Perform logical data extraction from an Android device using ADB and AFLogical OSE | [README](./Exp-7/README.md) | [PDF](./Exp-7/Exp-7.pdf) |
| **08** | Detect hidden information in image files using StegExpose | [README](./Exp-8/README.md) | [PDF](./Exp-8/Exp-8.pdf) |
| **09** | Monitor and analyze running processes, system calls, and file activities using Sysinternals Process Explorer | [README](./Exp-9/README.md) | [PDF](./Exp-9/Exp-9.pdf) |
| **10** | Perform basic malware analysis using Ghidra by examining file hashes and strings | [README](./Exp-10/README.md) | [PDF](./Exp-10/Exp-10.pdf) |

---

## Experiments Overview

### Exp-1 — Forensic Imaging & Memory Analysis

Create a forensic image of a storage device using **FTK Imager**, capture volatile memory using **WinPmem**, and analyze the memory image using **Volatility 3**.

**Tools:**

- FTK Imager
- WinPmem
- Volatility 3

[View Experiment 1](./Exp-1/README.md) | [View PDF](./Exp-1/Exp-1.pdf)

---

### Exp-2 — Data Recovery using TestDisk

Recover deleted or damaged files from a storage device using **TestDisk**.

**Tool:**

- TestDisk

[View Experiment 2](./Exp-2/README.md) | [View PDF](./Exp-2/Exp-2.pdf)

---

### Exp-3 — Network Traffic Analysis

Capture and analyze network traffic to identify suspicious activities using **Wireshark**.

**Tool:**

- Wireshark

[View Experiment 3](./Exp-3/README.md) | [View PDF](./Exp-3/Exp-3.pdf)

---

### Exp-4 — Email Header Analysis

Analyze email headers and identify phishing or email spoofing attacks using **Mail Header Analyzer (MHA)** or **MXToolbox Email Header Analyzer**.

**Tools:**

- Mail Header Analyzer (MHA)
- MXToolbox Email Header Analyzer

[View Experiment 4](./Exp-4/README.md) | [View PDF](./Exp-4/Exp-4.pdf)

---

### Exp-5 — Digital Forensics using Autopsy

Create a digital forensic case, import evidence, recover deleted files, and generate investigation reports using **Autopsy**.

**Tool:**

- Autopsy

[View Experiment 5](./Exp-5/README.md) | [View PDF](./Exp-5/Exp-5.pdf)

---

### Exp-6 — File System Analysis using The Sleuth Kit

Examine file systems, metadata, timelines, and deleted files using **The Sleuth Kit (TSK)**.

**Tool:**

- The Sleuth Kit (TSK)

[View Experiment 6](./Exp-6/README.md) | [View PDF](./Exp-6/Exp-6.pdf)

---

### Exp-7 — Android Forensics

Perform logical data extraction from an Android device using **ADB** and **AFLogical OSE**.

**Tools:**

- Android Debug Bridge (ADB)
- AFLogical OSE

[View Experiment 7](./Exp-7/README.md) | [View PDF](./Exp-7/Exp-7.pdf)

---

### Exp-8 — Image Steganalysis

Detect hidden information in image files using **StegExpose**.

**Tool:**

- StegExpose

[View Experiment 8](./Exp-8/README.md) | [View PDF](./Exp-8/Exp-8.pdf)

---

### Exp-9 — System Activity Analysis

Monitor and analyze running processes, system calls, and file activities using **Sysinternals Process Explorer** to identify suspicious system behavior.

**Tool:**

- Sysinternals Process Explorer

[View Experiment 9](./Exp-9/README.md) | [View PDF](./Exp-9/Exp-9.pdf)

---

### Exp-10 — Basic Malware Analysis

Perform basic malware analysis using **Ghidra** by examining file hashes and strings.

**Tool:**

- Ghidra

[View Experiment 10](./Exp-10/README.md) | [View PDF](./Exp-10/Exp-10.pdf)

---

## Tools & Software Utilized

The following tools and software are used across the experiments in this repository:

| Tool / Software | Purpose |
| :--- | :--- |
| **FTK Imager** | Creating forensic images and examining digital evidence |
| **WinPmem** | Capturing volatile memory |
| **Volatility 3** | Analyzing memory images |
| **TestDisk** | Recovering deleted or damaged files |
| **Wireshark** | Capturing and analyzing network traffic |
| **Mail Header Analyzer (MHA)** | Analyzing email headers |
| **MXToolbox Email Header Analyzer** | Investigating email header information |
| **Autopsy** | Creating forensic cases, analyzing evidence, recovering files, and generating reports |
| **The Sleuth Kit (TSK)** | Examining file systems, metadata, timelines, and deleted files |
| **ADB** | Logical data extraction from Android devices |
| **AFLogical OSE** | Android logical acquisition |
| **StegExpose** | Detecting hidden information in image files |
| **Sysinternals Process Explorer** | Monitoring processes and system activity |
| **Ghidra** | Basic malware analysis and examination of file hashes and strings |

---

## Lab Experiments

| Experiment | Primary Tools |
| :---: | :--- |
| **Exp-1** | FTK Imager, WinPmem, Volatility 3 |
| **Exp-2** | TestDisk |
| **Exp-3** | Wireshark |
| **Exp-4** | MHA / MXToolbox |
| **Exp-5** | Autopsy |
| **Exp-6** | The Sleuth Kit |
| **Exp-7** | ADB, AFLogical OSE |
| **Exp-8** | StegExpose |
| **Exp-9** | Sysinternals Process Explorer |
| **Exp-10** | Ghidra |

---

## Repository Structure

Each experiment contains its own documentation, PDF report, and supporting screenshots.

```text
Digital-Forensics-Lab/
│
├── README.md
│
├── Exp-1/
│   ├── README.md
│   ├── Exp-1.pdf
│   └── screenshot/
│
├── Exp-2/
│   ├── README.md
│   ├── Exp-2.pdf
│   └── screenshot/
│
├── Exp-3/
│   ├── README.md
│   ├── Exp-3.pdf
│   └── screenshot/
│
├── Exp-4/
│   ├── README.md
│   ├── Exp-4.pdf
│   └── screenshot/
│
├── Exp-5/
│   ├── README.md
│   ├── Exp-5.pdf
│   └── screenshot/
│
├── Exp-6/
│   ├── README.md
│   ├── Exp-6.pdf
│   └── screenshot/
│
├── Exp-7/
│   ├── README.md
│   ├── Exp-7.pdf
│   └── screenshot/
│
├── Exp-8/
│   ├── README.md
│   ├── Exp-8.pdf
│   └── screenshot/
│
├── Exp-9/
│   ├── README.md
│   ├── Exp-9.pdf
│   └── screenshot/
│
└── Exp-10/
    ├── README.md
    ├── Exp-10.pdf
    └── screenshot/
