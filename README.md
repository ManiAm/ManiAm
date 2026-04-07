# Homelab Projects

A collection of networking, infrastructure, and AI projects running across a Raspberry Pi cluster, virtual labs, and physical switches.

[![Homelab blog](https://img.shields.io/badge/homelab-blog-0A66C2?style=for-the-badge&logo=readthedocs&logoColor=white)](https://blog.homelabtech.dev/content/)

---

## Routing and Forwarding

### FRR-LabNet

- **Description**: Hands-on Docker-based lab to learn FRRouting (FRR) using an automated multi-node OSPF topology.

- **GitHub**: https://github.com/ManiAm/FRR-LabNet

### Bidirectional Forwarding Detection (BFD)

- **Description**: A Docker lab that demonstrates BFD's sub-second failure detection versus OSPF's 40-second dead timer using a three-node FRR topology.

- **GitHub**: https://github.com/ManiAm/BFD-LabNet

### Segment Routing (SR)

- **Description**: A hands-on Docker lab that builds a four-node IS-IS network with SRv6, demonstrating SID distribution and source routing with FRRouting.

- **GitHub**: https://github.com/ManiAm/segment-routing

---

## Programmable Networking

### Software-Defined Networking (SDN)

- **Description**: xxx

- **GitHub**: xxx

### P4-Mininet

- **Description**: A containerized P4 learning environment using Mininet and BMv2 to simulate programmable IPv4 forwarding.

- **GitHub**: https://github.com/ManiAm/p4-mininet

---

## Packet Processing

### DPDK-LabNet

- **Description**: A minimal virtual lab environment using two VMs to test and validate DPDK-based packet processing and traffic forwarding.

- **GitHub**: https://github.com/ManiAm/dpdk-labnet

### VPP-LabNet

- **Description**: A lightweight container-based lab using VPP and FRRouting to simulate high-speed packet forwarding and dynamic routing across multiple virtual nodes.

- **GitHub**: https://github.com/ManiAm/vpp-labnet

---

## Virtualization

### QEMU-LabNet

- **Description**: A cross-architecture virtualization lab that connects lightweight QEMU VMs across ARM64 and x86_64 platforms with TAP/VXLAN networking, shared host data, and a Flask-based QMP dashboard.

- **GitHub**: https://github.com/ManiAm/qemu-labnet

---

## SONiC Internals and Development

### Redis Lab

- **Description**: A structured reference for Redis — covering data types, persistence, transactions, Lua scripting, pub/sub, replication, and Python client usage.

- **GitHub**: https://github.com/ManiAm/sonic-lab-redis

### SONiC Internals Lab

- **Description**: A walkthrough of SONiC architecture and internals — containerization model, service infrastructure, and the role of Redis as the central data store.

- **GitHub**: https://github.com/ManiAm/sonic-lab-internals

### SONiC Build Lab

- **Description**: A step-by-step guide to building SONiC VS images from source, covering host setup, build configuration, and deployment on Proxmox, bare-metal, or cloud environments.

- **GitHub**: https://github.com/ManiAm/sonic-lab-build

### SONiC Daemon Lab

- **Description**: Developing custom SONiC containers and daemons — from Debian packaging and Docker integration to service management with supervisord.

- **GitHub**: https://github.com/ManiAm/sonic-lab-daemon

---

## SONiC Network Operations - GNS

### GNS-Bench

- **Description**: A setup guide for using GNS3 to simulate network topologies with appliances like Cisco and SONiC NOS.

- **GitHub**: https://github.com/ManiAm/GNS-Bench

### GNS-Sonic-ZTP

- **Description**: A hands-on lab demonstrating SONiC ZTP in GNS3, including building a ZTP-enabled SONiC VS image and automating switch configuration using DHCP and a provisioning server.

- **GitHub**: https://github.com/ManiAm/GNS-Sonic-ZTP

### GNS-Sonic-LLDP-Discover

- **Description**: A lightweight tool that discovers SONiC network topology using LLDP and renders an interactive, port-level visualization.

- **GitHub**: https://github.com/ManiAm/GNS-Sonic-LLDP-Discover

### GNS-Sonic-Telemetry

- **Description**: Build a GNS3-based SONiC lab to explore modern network telemetry using gNMI, OpenConfig YANG models, and streaming data collection.

- **GitHub**: https://github.com/ManiAm/GNS-Sonic-Telemetry

### GNS-Sonic-FlowMon

- **Description**: A traffic visibility and telemetry toolkit for SONiC devices, featuring real-time packet sniffing, PCAP export, and scalable sFlow monitoring via UDP.

- **GitHub**: https://github.com/ManiAm/GNS-Sonic-FlowMon

### GNS-Sonic-Traffic

- **Description**: A GNS3-based testbed for validating SONiC router traffic flows using TRex in a controlled environment.

- **GitHub**: https://github.com/ManiAm/GNS-Sonic-Traffic

---

## Data Center Networking

### DC Fundamentals

- **Description**: Physical data center infrastructure — facility design, rack architecture, power/cooling, management, and network topology evolution from three-tier to leaf-spine.

- **GitHub**: https://github.com/ManiAm/DC-Fundamentals

### VXLAN-EVPN

- **Description**: Hands-on VXLAN + BGP EVPN leaf-spine fabric lab using SONiC in GNS3, covering VLANs, overlay encapsulation, and EVPN control-plane configuration.

- **GitHub**: https://github.com/ManiAm/GNS-DC-VXLAN

### QoS

- **Description**: A structured guide to data center QoS — from service models and DiffServ pipelines through lossless Ethernet and next-generation congestion control.

- **GitHub**: https://github.com/ManiAm/GNS-QOS

### RDMA-Primer

- **Description**: Hands-on RDMA application development in C, covering InfiniBand and RoCEv2.

- **GitHub**: https://github.com/ManiAm/RDMA-Primer

### Load-Balancing

- **Description**: A structured guide to data center fabric load balancing — from ECMP hashing and its limitations through Adaptive Routing and congestion-aware traffic steering.

- **GitHub**: https://github.com/ManiAm/GNS-DC-Load-Balancing

### MPI

- **Description**: MPI collective operations and communication topologies demonstrated across networked compute nodes in GNS3.

- **GitHub**: https://github.com/ManiAm/GNS-MPI

### AI-Networks

- **Description**: End-to-end AI network architecture: from the DNN workload through scale-up, scale-out, and open standards.

- **GitHub**: https://github.com/ManiAm/GNS-DC-AI

---

## Physical Switch Lab

### Switch SerDes and Signaling

- **Description**: High-speed serial signaling in data center switches: SerDes architecture, line coding, signal integrity, and link training.

- **GitHub**: https://github.com/ManiAm/net-lab-switch-serdes

### Transceiver Fundamentals

- **Description**: Pluggable transceiver architecture, management interfaces (CMIS/SFF-8636/SFF-8472), and EEPROM decoding tools.

- **GitHub**: https://github.com/ManiAm/net-lab-transceiver

### DX010 Lab

- **Description**: Celestica DX010 hardware deep-dive, cooling, setup guides, and SONiC platform scripts.

- **GitHub**: https://github.com/ManiAm/net-lab-dx010

### PRBS

- **Description**: Physical-layer PRBS testing and signal integrity validation on a Celestica DX010 (Tomahawk) SONiC switch.

- **GitHub**: https://github.com/ManiAm/net-lab-prbs

### Snake

- **Description**: xxx

- **GitHub**: xxx

### Slow Path

- **Description**: xxx

- **GitHub**: xxx

---

## Lab Access and Control

### Sonic-Proxy

- **Description**: A lightweight HTTP proxy service for SONiC NOS, enabling outbound internet access for internal applications and containers.

- **GitHub**: https://github.com/ManiAm/sonic-proxy

### Terminal Server

- **Description**: A lightweight Telnet proxy that multiplexes a single remote session across multiple local clients for collaboration, monitoring, and debugging.

- **GitHub**: https://github.com/ManiAm/terminal-server

### Lab-CLI

- **Description**: A Klish-based, network-style command interface that exposes safe, structured lab operations through a controlled, auditable CLI.

- **GitHub**: https://github.com/ManiAm/Lab-cli

---

## CI/CD and Build Tooling

### Primes-CPP

- **Description**: A small C++ project for prime number utilities, used as a demo for CI pipelines with build, test, static analysis, linting and code coverage.

- **GitHub**: https://github.com/ManiAm/primes-cpp

### Primes-Python

- **Description**: A small Python project for prime number utilities, used as a demo for CI pipelines with formatting, linting, static analysis, documentation generation, packaging, test and code coverage.

- **GitHub**: https://github.com/ManiAm/primes-python

### Jenkins-Pipeline

- **Description**: This project sets up a Jenkins CI/CD pipeline with one controller and three agents, triggered by GitHub webhooks.

- **GitHub**: https://github.com/ManiAm/Jenkins-pipeline

### Cache-Forge

- **Description**: A self-hosted artifact caching gateway that uses JFrog Artifactory OSS to locally mirror and accelerate access to artifacts across a home lab environment.

- **GitHub**: https://github.com/ManiAm/Cache-Forge

---

## Infrastructure and Operations

### Slurm Cluster on Docker

- **Description**: A fully containerized Slurm cluster using Docker Compose complete with controller, compute nodes, accounting (SlurmDBD + MariaDB), and REST API support.

- **GitHub**: https://github.com/ManiAm/slurm-docker-cluster

### Soft-Seal

- **Description**: A host-bound secret-sealing tool that derives encryption keys from a machine's identity so secrets stay usable only on that specific host while storing only the encrypted data.

- **GitHub**: https://github.com/ManiAm/Soft-Seal

### Uptime Monitor

- **Description**: A lightweight REST API proxy that connects BetterStack monitoring data to Grafana using JSON endpoints compatible with the Infinity plugin.

- **Cluster Node**: `hermes`

- **GitHub**: https://github.com/ManiAm/grafana-betterstack-proxy

---

## Embedded and Sensors

### NTP Server

- **Description**: Configuring a Raspberry Pi as a NTP server using GPS and PPS for accurate time synchronization.

- **Cluster Node**: `gps`

- **GitHub**: https://github.com/ManiAm/raspi-ntp-server

### SkyWatch

- **Description**: Real-time aircraft monitoring, enrichment, and alerting system using ADS-B data from dump1090-fa. Logs flights and sends proximity-based alerts via Discord.

- **Cluster Node**: `gps`

- **GitHub**: https://github.com/ManiAm/raspi-skywatch

### Enviro-Watch

- **Description**: A lightweight system for collecting temperature, humidity, and battery data from multiple BLE environmental sensors (`LYWSD03MMC`) using a Raspberry Pi. It decodes advertisements, enriches sensor metadata, and forwards the data to a remote InfluxDB database for storage, visualization, and analysis.

- **Cluster Node**: `ares`

- **GitHub**: https://github.com/ManiAm/raspi-enviro-watch

---

## Web Services and Backend Engineering

### Video2Audio

- **Description**: A microservice-based web application that enables users to upload video files and automatically extract the corresponding audio track.

- **Cluster Node**: `artemis`

- **GitHub**: https://github.com/ManiAm/Video2Audio

### DataSpider

- **Description**: A distributed web scraping platform that uses gRPC for task submission, Celery for asynchronous task processing, and Elasticsearch for indexing scraped content. Supports real-time content search.

- **Cluster Node**: `artemis`

- **GitHub**: https://github.com/ManiAm/DataSpider

### Rate-Limiter

- **Description**: A demonstration and comparison of different rate-limiting algorithms (token bucket, leaky bucket, fixed window, sliding window, etc.) with easy-to-use decorators and middleware for applying limits to Flask endpoints.

- **GitHub**: https://github.com/ManiAm/rate-limiter

---

## Media Applications

### MoviePulse

- **Description**: A lightweight, self-hosted web application designed to help families discover trending movies and TV shows.

- **Cluster Node**: `artemis`

- **GitHub**: https://github.com/ManiAm/moviepulse

### Media-Stack

- **Description**: A self-hosted automation suite for managing, optimizing, and streaming your media library using Dockerized tools like Sonarr, Radarr, Lidarr, Readarr, Prowlarr, Bazarr, qBittorrent, SABnzbd, Jellyseerr, etc. secured with Gluetun VPN gateway for anonymous and protected downloads.

- **Cluster Node**: `WSL`

- **GitHub**: https://github.com/ManiAm/media-stack

---

## Chat and Collaboration Integrations

### Webex-REST

- **Description**: A minimalist Python client for automating team, room, membership, and messaging operations using the Webex REST API.

- **GitHub**: https://github.com/ManiAm/webex-rest

### Webex-Assistant

- **Description**: A programmable bot framework for Webex that enables users to trigger actions, automate workflows, and retrieve contextual information through chat-based commands.

- **GitHub**: https://github.com/ManiAm/webex-assistant

---

## Voice and Speech AI

### Speak-IO

- **Description**: A web API for speech-to-text (STT) and text-to-speech (TTS) that integrates with existing engines, supporting real-time audio streaming and modular engine selection.

- **GitHub**: https://github.com/ManiAm/Speak-IO

### Trigger-Talk

- **Description**: An offline-capable hotword detection framework that passively listens for custom wake phrases to trigger speech recognition or automation workflows.

- **GitHub**: https://github.com/ManiAm/Trigger-Talk

### LLM-Talk

- **Description**: Natural voice conversations with language models using hotword activation.

- **GitHub**: https://github.com/ManiAm/LLM-Talk

### Transcribe-Voicemail

- **Description**: A self-hosted system that integrates with FreePBX to automatically transcribe voicemail audio into text and deliver it via email using local speech-to-text processing.

- **GitHub**: https://github.com/ManiAm/Transcribe-Voicemail

---

## Retrieval and RAG

### RAG-Search

- **Description**: A web-based chat interface that combines LLMs with document-aware retrieval for context-rich, AI-powered conversations.

- **GitHub**: https://github.com/ManiAm/RAG-Search

### RAG-Mail

- **Description**: A thread-aware email processing system that semantically indexes conversations and attachments for context-rich retrieval using RAG.

- **GitHub**: https://github.com/ManiAm/RAG-Mail

### Job-Genius

- **Description**: An AI-powered job discovery platform that helps users find, evaluate, and personalize job opportunities using semantic search, resume matching, and real-time insights.

- **GitHub**: https://github.com/ManiAm/Job-Genius

---

## LLM Agents and Tooling

### Home-MCP

- **Description**: A locally hosted MCP server that exposes tool-based APIs for use by LLM clients in a privacy-preserving and extensible environment.

- **GitHub**: https://github.com/ManiAm/home-MCP

### Personal Assistant

- **Description**: An extensible AI personal assistant that uses a ReAct agent to call MCP-provided tools for real-time questions.

- **GitHub**: https://github.com/ManiAm/personal-assistant

### Ollama-remote-models

- **Description**: A tool that scrapes the Ollama website to extract and list all available remote LLM models in a structured format.

- **GitHub**: https://github.com/ManiAm/ollama-remote-models

---

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=ManiAm&style=flat-square" alt="Profile Views" />
</p>
