# 📝 Lab 1 – Installing Ubuntu Server and Accessing via SSH

## 🎯 Objective
Install Ubuntu Server on VMware Workstation and access it remotely from the host system using SSH.

## 🛠 Requirements
- VMware Workstation / Player installed on Windows  
- Ubuntu Server ISO file  
- Windows Command Prompt or PowerShell for SSH  
- Stable internet connection

## 🚀 Procedure

### 1. Download VMware and Ubuntu Server ISO
- Download and install VMware Workstation/Player.  
- Download Ubuntu Server ISO from the official Ubuntu website.  

### 2. Create a New Virtual Machine
- Open VMware → Click **Create a New Virtual Machine**.  
- Select **Typical** installation and choose the downloaded Ubuntu Server ISO.

### 3. Configure Virtual Machine Settings
- Choose disk size, memory, and CPU as instructed.  
- Finish the setup.

### 4. Install Ubuntu Server
- Start the VM.  
- Follow the installation prompts to set language, keyboard, and user credentials.

### 5. Get the VM IP Address
- After installation, log in to Ubuntu Server.  
- Run the command:
  ```bash
  ip addr
