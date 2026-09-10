# ✨ NetSage AI

[![Version](https://img.shields.io/badge/version-5.5.0-1a1a2e)](https://github.com/roselinereema/NetSage-AI)
![License](https://img.shields.io/badge/license-GPLv3-1a1a2e)
[![Last Commit](https://img.shields.io/github/last-commit/roselinereema/NetSage-AI?color=1a1a2e)](https://github.com/roselinereema/NetSage-AI/commits/main/)

> **NetSage AI** is an AI-assisted network troubleshooting framework designed to investigate network incidents, analyze network evidence, identify likely root causes, recommend troubleshooting actions, and keep a human operator in the approval loop before configuration changes are applied.

| | |
|---|---|
| | **Core Version** |
| **Vendors** | ![Cisco IOS-XE](https://img.shields.io/badge/Cisco_IOS--XE-0d47a1) |
| **Management** | ![RESTCONF](https://img.shields.io/badge/RESTCONF-1565c0) ![CLI](https://img.shields.io/badge/CLI-1565c0) |
| **Integrations** | ![Jira](https://img.shields.io/badge/Jira-1976d2) ![NetBox](https://img.shields.io/badge/NetBox-1976d2) ![Discord](https://img.shields.io/badge/Discord-1976d2) ![HashiCorp Vault](https://img.shields.io/badge/HashiCorp_Vault-1976d2) |
| | **On-Request** |
| **Vendors** | ![Arista EOS](https://img.shields.io/badge/Arista_EOS-1e88e5) ![Juniper JunOS](https://img.shields.io/badge/Juniper_JunOS-1e88e5) ![Aruba AOS-CX](https://img.shields.io/badge/Aruba_AOS--CX-1e88e5) ![SONiC FRR](https://img.shields.io/badge/SONiC_FRR-1e88e5) ![MikroTik RouterOS](https://img.shields.io/badge/MikroTik_RouterOS-1e88e5) ![VyOS](https://img.shields.io/badge/VyOS-1e88e5) |
| **Management** | ![NETCONF](https://img.shields.io/badge/NETCONF-2196f3) ![REST APIs](https://img.shields.io/badge/REST_APIs-2196f3) ![gNMI](https://img.shields.io/badge/gNMI-2196f3) ![eAPI](https://img.shields.io/badge/eAPI-2196f3) |
| **Integrations** | ![Slack](https://img.shields.io/badge/Slack-42a5f5) ![ServiceNow](https://img.shields.io/badge/ServiceNow-42a5f5) |
| | **Monitoring** |
| **Human Review** | Human-in-the-loop approval for configuration changes |
| **Dashboard** | Web dashboard for agent and troubleshooting monitoring |

---

## 📖 Table of Contents

- 📜 **NetSage AI**
  - [🔭 Overview](#-overview)
  - [🍀 Quick Demo](#-quick-demo)
  - [⭐ Key Features](#-key-features)
  - [⚒️ Current Tech Stack](#️-current-tech-stack)
  - [📋 Supported Vendors](#-supported-vendors)
  - [🚛 Supported Transports](#-supported-transports)
  - [🎓 Troubleshooting Scope](#-troubleshooting-scope)
  - [🛠️ Installation & Usage](#️-installation--usage)
  - [🔄 Test Network Topology](#-test-network-topology)
  - [📞 NetSage AI Service Mode](#-netsage-ai-service-mode)
  - [👤 Human-in-the-Loop Review](#-human-in-the-loop-review)
  - [📊 Dashboard](#-dashboard)
  - [📁 Project Structure](#-project-structure)
  - [⬆️ Planned Upgrades](#️-planned-upgrades)
  - [♻️ Repository Lifecycle](#️-repository-lifecycle)
  - [🙏 Attribution](#-attribution)
  - [📄 Disclaimer](#-disclaimer)
  - [📜 License](#-license)

---

## 🔭 Overview

NetSage AI is an AI-assisted **network troubleshooting framework** for investigating network incidents across multi-vendor, multi-protocol and multi-area/multi-AS enterprise environments.

The system is designed to help a network operator move from a network symptom to an evidence-based diagnosis and recommended remediation.

### Key Characteristics

- [x] **AI-assisted network troubleshooting**
- [x] **Multi-vendor support**
- [x] **Multi-protocol, L2/L3**
- [x] **Multi-area/multi-AS**
- [x] **CLI/RESTCONF management**
- [x] **NETCONF/REST/gNMI/eAPI support**
- [x] **MCP tools**
- [x] **Troubleshooting skills**
- [x] **Operational guardrails**
- [x] **Human-in-the-loop approval for configuration changes**
- [x] **Dashboard for agent monitoring**
- [x] **Discord integration**
- [x] **Jira integration**
- [x] **HashiCorp Vault integration**
- [x] **NetBox integration**

### Core Features

- Easy integration with Cisco IOS/IOS-XE environments
- CLI and RESTCONF management
- OSPF and BGP troubleshooting
- Jira integration
- Discord integration
- NetBox integration
- HashiCorp Vault integration

### On-Request Features

- Custom vendor modules
- Custom management integrations
- Custom network architectures
- Environment-specific adaptations

---

## 🍀 Quick Demo

NetSage AI provides an AI-assisted workflow for investigating network incidents.

The general troubleshooting workflow is:

```text
Network Incident
       |
       v
Evidence Collection
       |
       v
AI Investigation
       |
       v
Root Cause Analysis
       |
       v
Recommended Fix
       |
       v
Human Review
     /     \
    /       \
Approve     Reject
   |           |
   v           v
Apply Fix    Keep Case Open
   |
   v
Verification
