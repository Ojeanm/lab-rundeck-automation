# lab-rundeck-automation
Deployment and configuration of a Rundeck automation platform in a Hyper-V homelab environment.

⭐ Rundeck Automation Platform (Homelab)







📝 Overview

This repository documents the deployment and configuration of Rundeck, an automation and job orchestration platform, running in a Hyper-V homelab environment.

Rundeck is used to automate operational tasks, manage workflows, and run scheduled jobs across multiple hosts in the lab.

🖥️ Environment

Virtualization Platform: Microsoft Hyper-V
Server OS: Ubuntu Server
Monitored / Managed Infrastructure:

Ubuntu Servers

Windows Server systems

Network infrastructure (VyOS, MikroTik CHR)

Containerized applications

⚙️ Platform Components

Rundeck Server — Central orchestration engine

Rundeck Nodes — Hosts where tasks are executed

Database Backend — Stores job definitions and execution logs

Web Interface — Dashboard for job management and execution

📊 Capabilities

Rundeck is configured to:

✅ Automate routine system administration tasks

✅ Schedule and execute jobs on multiple hosts

✅ Orchestrate workflows across Linux, Windows, and containerized hosts

✅ Provide logging, auditing, and execution history

🏗️ Architecture

Rundeck follows a centralized orchestration architecture:

The Rundeck server manages job execution across multiple nodes

Job results are logged and stored in a database

Workflows can include scripts, commands, or API calls across all managed hosts




💻 Screenshots

Dashboard Overview



Job Execution Example



Workflow View



🎯 Skills Demonstrated

Automation & orchestration of tasks

Multi-node job scheduling

Linux/Windows server administration

Workflow documentation & operational playbooks

Logging and auditing for infrastructure tasks
