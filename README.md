# Homelab Projects

A collection of networking, infrastructure, and AI projects running across a Raspberry Pi cluster, virtual labs, and physical switches.

[![Homelab blog](https://img.shields.io/badge/homelab-blog-0A66C2?style=for-the-badge&logo=readthedocs&logoColor=white)](https://blog.homelabtech.dev/content/)


## Systems Foundations

### [OS Boot Process](https://github.com/ManiAm/os-boot-process)

A ground-up walkthrough of the OS boot sequence — CPU reset, BIOS/UEFI, bootloaders, kernel initialization, and hands-on boot-sector disassembly.

### [Linux Kernel](https://github.com/ManiAm/linux-kernel)

A reference covering the Linux kernel — its UNIX origins, system architecture overview, compiling custom kernels for multiple architectures, and the kernel boot process.

### [Storage and File Systems](https://github.com/ManiAm/storage-and-file-systems)

A bottom-up primer covering disk storage from physical hardware and partitioning schemes to filesystem internals and Linux directory organization.

### [Linux Init Systems](https://github.com/ManiAm/linux-init-systems)

Linux init systems — from the kernel-to-userspace handoff and SysV init to systemd service management, unit files, dependencies, and journald.

### [Linux Package Management](https://github.com/ManiAm/linux-package-management)

A beginner-friendly guide to Linux package management covering dpkg, APT, RPM, DNF, and building .deb/.rpm packages from source.


## Tools and Environment

### [Terminal Primer](https://github.com/ManiAm/primer-terminal)

A beginner-friendly guide to how terminals work in Linux — from physical teletypes to modern terminal emulators.

### [Bash Primer](https://github.com/ManiAm/primer-bash)

A hands-on primer on Bash — covering shell fundamentals, scripting patterns, process control, and practical techniques for day-to-day systems work.

### [Build Tools Primer](https://github.com/ManiAm/primer-build-tools)

A comparative guide to build systems — Make, CMake, and Bazel — covering dependency models, build graphs, caching, and when to use each.


## CI/CD and Build Tooling

### [Primes-CPP](https://github.com/ManiAm/primes-cpp)

A small C++ project for prime number utilities, used as a demo for CI pipelines with build, test, static analysis, linting and code coverage.

### [Primes-Python](https://github.com/ManiAm/primes-python)

A small Python project for prime number utilities, used as a demo for CI pipelines with formatting, linting, static analysis, documentation generation, packaging, test and code coverage.

### [Jenkins-Pipeline](https://github.com/ManiAm/Jenkins-pipeline)

This project sets up a Jenkins CI/CD pipeline with one controller and three agents, triggered by GitHub webhooks.

### [Cache-Forge](https://github.com/ManiAm/Cache-Forge)

A self-hosted artifact caching gateway that uses JFrog Artifactory OSS to locally mirror and accelerate access to artifacts across a home lab environment.


## Security and Cryptography

### [HashCraft](https://github.com/ManiAm/HashCraft)

A hands-on lab for learning hash functions and hash tables with multiple hash implementations and a benchmark that measures how they compare.

### [Digital Signature](xxx)

*(Coming soon)*

### [Soft-Seal](https://github.com/ManiAm/Soft-Seal)

A host-bound secret-sealing tool that derives encryption keys from a machine's identity so secrets stay usable only on that specific host while storing only the encrypted data.


## Virtualization

### [Virtualization Primer](https://github.com/ManiAm/primer-virtualization)

A hands-on primer covering virtualization from hardware hypervisors and QEMU to Docker containers and beyond.

### [QEMU-LabNet](https://github.com/ManiAm/qemu-labnet)

A cross-architecture virtualization lab that connects lightweight QEMU VMs across ARM64 and x86_64 platforms with TAP/VXLAN networking, shared host data, and a Flask-based QMP dashboard.

### [Container Orchestration](https://github.com/ManiAm/container-orchestration)

*(Coming soon)*


## Routing and Forwarding

### [FRRouting (FRR)](https://github.com/ManiAm/FRR-LabNet)

Hands-on Docker-based lab to learn FRRouting (FRR) using an automated multi-node OSPF topology.

### [Bidirectional Forwarding Detection (BFD)](https://github.com/ManiAm/BFD-LabNet)

A Docker lab that demonstrates BFD's sub-second failure detection versus OSPF's 40-second dead timer using a three-node FRR topology.

### [Segment Routing (SR)](https://github.com/ManiAm/SR-LabNet)

A hands-on Docker lab that builds a four-node IS-IS network with SRv6, demonstrating SID distribution and source routing with FRRouting.

### [Virtual Routing and Forwarding (VRF)](https://github.com/ManiAm/VRF-LabNet)

A Docker lab that demonstrates VRF routing-table isolation and BGP route leaking on a single FRR router with two VRFs and four hosts.


## Programmable Networking

### [Software-Defined Networking (SDN)](xxx)

*(Coming soon)*

### [P4-Mininet](https://github.com/ManiAm/p4-mininet)

A containerized P4 learning environment using Mininet and BMv2 to simulate programmable IPv4 forwarding.


## Packet Processing

### [DPDK-LabNet](https://github.com/ManiAm/dpdk-labnet)

A minimal virtual lab environment using two VMs to test and validate DPDK-based packet processing and traffic forwarding.

### [VPP-LabNet](https://github.com/ManiAm/vpp-labnet)

A lightweight container-based lab using VPP and FRRouting to simulate high-speed packet forwarding and dynamic routing across multiple virtual nodes.


## Data Center Networking

### [Data Center Fundamentals](https://github.com/ManiAm/DC-Fundamentals)

Physical data center infrastructure — facility design, rack architecture, power/cooling, management, and network topology evolution from three-tier to leaf-spine.

### [VXLAN-EVPN](https://github.com/ManiAm/DC-VXLAN)

Hands-on VXLAN + BGP EVPN leaf-spine fabric lab using SONiC VS, covering VLANs, overlay encapsulation, and EVPN control-plane configuration.

### [QoS](https://github.com/ManiAm/DC-QOS)

A structured guide to data center QoS — from service models and DiffServ pipelines through lossless Ethernet and next-generation congestion control.

### [RDMA-Primer](https://github.com/ManiAm/RDMA-Primer)

Hands-on RDMA application development in C, covering InfiniBand and RoCEv2.

### [Data Center Fabric Load Balancing](https://github.com/ManiAm/DC-Load-Balancing)

A structured guide to hardware-level load balancing in data center switch fabrics — from ECMP hashing and its limitations through Adaptive Routing and congestion-aware traffic steering on ASICs and NPUs.


## AI Infrastructure Networking

### [MPI](https://github.com/ManiAm/GNS-MPI)

MPI collective operations and communication topologies demonstrated across networked compute nodes in GNS3.

### [AI Network Architecture](https://github.com/ManiAm/DC-AI)

*(Coming soon)*

### [Multipath Reliable Connection (MRC)](https://github.com/ManiAm/DC-AI-MRC)

A hands-on emulator for MRC, a multipath RDMA protocol that sprays packets across all fabric paths to scale RoCEv2 for AI training.


## SONiC Internals and Development

### [SONiC Internals Lab](https://github.com/ManiAm/sonic-lab-internals)

A walkthrough of SONiC architecture and internals — containerization model, service infrastructure, and the role of Redis as the central data store.

### [SONiC Build Lab](https://github.com/ManiAm/sonic-lab-build)

A step-by-step guide to building SONiC VS images from source, covering host setup, build configuration, and deployment on Proxmox, bare-metal, or cloud environments.

### [SONiC Daemon Lab](https://github.com/ManiAm/sonic-lab-daemon)

Developing custom SONiC containers and daemons — from Debian packaging and Docker integration to service management with supervisord.


## SONiC Network Operations — GNS

### [GNS-Bench](https://github.com/ManiAm/GNS-Bench)

A setup guide for using GNS3 to simulate network topologies with appliances like Cisco and SONiC NOS.

### [GNS-Sonic-ZTP](https://github.com/ManiAm/GNS-Sonic-ZTP)

A hands-on lab demonstrating SONiC ZTP in GNS3, including building a ZTP-enabled SONiC VS image and automating switch configuration using DHCP and a provisioning server.

### [GNS-Sonic-LLDP-Discover](https://github.com/ManiAm/GNS-Sonic-LLDP-Discover)

A lightweight tool that discovers SONiC network topology using LLDP and renders an interactive, port-level visualization.

### [GNS-Sonic-Telemetry](https://github.com/ManiAm/GNS-Sonic-Telemetry)

Build a GNS3-based SONiC lab to explore modern network telemetry using gNMI, OpenConfig YANG models, and streaming data collection.

### [GNS-Sonic-FlowMon](https://github.com/ManiAm/GNS-Sonic-FlowMon)

A traffic visibility and telemetry toolkit for SONiC devices, featuring real-time packet sniffing, PCAP export, and scalable sFlow monitoring via UDP.

### [GNS-Sonic-Traffic](https://github.com/ManiAm/GNS-Sonic-Traffic)

A GNS3-based testbed for validating SONiC router traffic flows using TRex in a controlled environment.


## Physical Switch Lab

### [Switch SerDes and Signaling](https://github.com/ManiAm/net-lab-switch-serdes)

High-speed serial signaling in data center switches: SerDes architecture, line coding, signal integrity, and link training.

### [Transceiver Fundamentals](https://github.com/ManiAm/net-lab-transceiver)

Pluggable transceiver architecture, management interfaces (CMIS/SFF-8636/SFF-8472), and EEPROM decoding tools.

### [DX010 Lab](https://github.com/ManiAm/net-lab-dx010)

Celestica DX010 hardware deep-dive, cooling, setup guides, and SONiC platform scripts.

### [PRBS](https://github.com/ManiAm/net-lab-prbs)

Physical-layer PRBS testing and signal integrity validation on a Celestica DX010 (Tomahawk) SONiC switch.


## Lab Access and Control

### [Sonic-Proxy](https://github.com/ManiAm/sonic-proxy)

A lightweight HTTP proxy service for SONiC NOS, enabling outbound internet access for internal applications and containers.

### [Terminal Server](https://github.com/ManiAm/terminal-server)

A lightweight Telnet proxy that multiplexes a single remote session across multiple local clients for collaboration, monitoring, and debugging.

### [Lab-CLI](https://github.com/ManiAm/Lab-cli)

A Klish-based, network-style command interface that exposes safe, structured lab operations through a controlled, auditable CLI.


## Distributed Systems and Databases

### [Distributed Systems Primer](xxx)

*(Coming soon)*

### [SQL Databases](xxx)

*(Coming soon)*

### [NoSQL Databases](xxx)

*(Coming soon)*

### [Redis Lab](https://github.com/ManiAm/sonic-lab-redis)

A structured reference for Redis — covering data types, persistence, transactions, Lua scripting, pub/sub, replication, and Python client usage.


## Web and API Infrastructure

### [Network Programming](xxx)

*(Coming soon)*

### [Web Servers](xxx)

*(Coming soon)*

### [Web Frameworks](xxx)

*(Coming soon)*

### [Web APIs](xxx)

*(Coming soon)*


## Messaging and Microservices

### [Message Brokers](xxx)

*(Coming soon)*

### [Apache Kafka](xxx)

*(Coming soon)*

### [Celery](xxx)

*(Coming soon)*

### [Microservices](xxx)

*(Coming soon)*


## Web Services and Backend Engineering

### [Video2Audio](https://github.com/ManiAm/Video2Audio)

A microservice-based web application that enables users to upload video files and automatically extract the corresponding audio track.

### [DataSpider](https://github.com/ManiAm/DataSpider)

A distributed web scraping platform that uses gRPC for task submission, Celery for asynchronous task processing, and Elasticsearch for indexing scraped content. Supports real-time content search.

### [Rate-Limiter](https://github.com/ManiAm/rate-limiter)

A demonstration and comparison of different rate-limiting algorithms (token bucket, leaky bucket, fixed window, sliding window, etc.) with easy-to-use decorators and middleware for applying limits to Flask endpoints.


## Chat and Collaboration Integrations

### [Webex-REST](https://github.com/ManiAm/webex-rest)

A minimalist Python client for automating team, room, membership, and messaging operations using the Webex REST API.

### [Webex-Assistant](https://github.com/ManiAm/webex-assistant)

A programmable bot framework for Webex that enables users to trigger actions, automate workflows, and retrieve contextual information through chat-based commands.


## Infrastructure and Operations

### [Slurm Cluster on Docker](https://github.com/ManiAm/slurm-docker-cluster)

A fully containerized Slurm cluster using Docker Compose complete with controller, compute nodes, accounting (SlurmDBD + MariaDB), and REST API support.

### [Uptime Monitor](https://github.com/ManiAm/grafana-betterstack-proxy)

A lightweight REST API proxy that connects BetterStack monitoring data to Grafana using JSON endpoints compatible with the Infinity plugin.


## Embedded and Sensors

### [NTP Server](https://github.com/ManiAm/raspi-ntp-server)

Configuring a Raspberry Pi as a NTP server using GPS and PPS for accurate time synchronization.

### [SkyWatch](https://github.com/ManiAm/raspi-skywatch)

Real-time aircraft monitoring, enrichment, and alerting system using ADS-B data from dump1090-fa. Logs flights and sends proximity-based alerts via Discord.

### [Enviro-Watch](https://github.com/ManiAm/raspi-enviro-watch)

A lightweight system for collecting temperature, humidity, and battery data from multiple BLE environmental sensors (`LYWSD03MMC`) using a Raspberry Pi. It decodes advertisements, enriches sensor metadata, and forwards the data to a remote InfluxDB database for storage, visualization, and analysis.


## Media Applications

### [MoviePulse](https://github.com/ManiAm/moviepulse)

A lightweight, self-hosted web application designed to help families discover trending movies and TV shows.

### [Media-Stack](https://github.com/ManiAm/media-stack)

A self-hosted automation suite for managing, optimizing, and streaming your media library using Dockerized tools like Sonarr, Radarr, Lidarr, Readarr, Prowlarr, Bazarr, qBittorrent, SABnzbd, Jellyseerr, etc. secured with Gluetun VPN gateway for anonymous and protected downloads.


## Voice and Speech AI

### [Speak-IO](https://github.com/ManiAm/Speak-IO)

A web API for speech-to-text (STT) and text-to-speech (TTS) that integrates with existing engines, supporting real-time audio streaming and modular engine selection.

### [Trigger-Talk](https://github.com/ManiAm/Trigger-Talk)

An offline-capable hotword detection framework that passively listens for custom wake phrases to trigger speech recognition or automation workflows.

### [LLM-Talk](https://github.com/ManiAm/LLM-Talk)

Natural voice conversations with language models using hotword activation.

### [Transcribe-Voicemail](https://github.com/ManiAm/Transcribe-Voicemail)

A self-hosted system that integrates with FreePBX to automatically transcribe voicemail audio into text and deliver it via email using local speech-to-text processing.


## Retrieval and RAG

### [RAG-Search](https://github.com/ManiAm/RAG-Search)

A web-based chat interface that combines LLMs with document-aware retrieval for context-rich, AI-powered conversations.

### [RAG-Mail](https://github.com/ManiAm/RAG-Mail)

A thread-aware email processing system that semantically indexes conversations and attachments for context-rich retrieval using RAG.

### [Job-Genius](https://github.com/ManiAm/Job-Genius)

An AI-powered job discovery platform that helps users find, evaluate, and personalize job opportunities using semantic search, resume matching, and real-time insights.


## LLM Agents and Tooling

### [Home-MCP](https://github.com/ManiAm/home-MCP)

A locally hosted MCP server that exposes tool-based APIs for use by LLM clients in a privacy-preserving and extensible environment.

### [Personal Assistant](https://github.com/ManiAm/personal-assistant)

An extensible AI personal assistant that uses a ReAct agent to call MCP-provided tools for real-time questions.

### [Ollama-remote-models](https://github.com/ManiAm/ollama-remote-models)

A tool that scrapes the Ollama website to extract and list all available remote LLM models in a structured format.

---

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=ManiAm&style=flat-square" alt="Profile Views" />
</p>
