# AZ-104 Azure IT Administrator Certificate

## Section 1: Introduction

Important Course Introductions

PDF and Diagrams download

## Section 2: Starting with Azure

Azure Free Account

Creating an Azure Free Account

Note on restrictions for the Azure Free Account

Concepts in Azure

Tour of the Portal

Quick note on Security Defaults

## Section 3: Deploy and Manage Azure compute resources

## Section 3.1: We are going to start with the Azure virtual machine service

## Section 3.2: The Virtual Machine Service

## Section 3.3: Lab - Building a Windows virtual machine

## Section 3.4: Connecting to the Virtual Machine

## Section 3.5: Issues connecting to the machine

## Section 3.6: Lab - Installing Internet Information Services

## Section 3.7: Costs Associated with the Virtual Machine

## Section 3.8: Virtual Machine Types

## Section 3.9: Building a Linux Virtual Machine

### Section 3.9.1: Create a Linux Virtual Machine:

In the Azure Portal, navigate to the "Virtual machines" section.

Click on "Add" to create a new VM.

Select the desired Linux distribution (e.g., Ubuntu, CentOS) and configure other settings like VM size, authentication, and networking.

### Section 3.9.2: Connect to the Virtual Machine:

Once the VM is deployed, connect to it using an SSH client (e.g., PuTTY on Windows, Terminal on macOS/Linux).

### Section 3.9.3: Update and Upgrade:

Run the following commands to ensure your system is up to date:

```linux
sudo apt update
sudo apt upgrade
```

### Section 3.9.4: Install a Web Server (e.g., Apache or Nginx):

For Apache, run:

```linux
sudo apt install apache2
```

For Nginx, run:

```
sudo apt install nginx
```

### Section 3.9.5: Start and Enable the Web Server:

For Apache, run:

```
sudo systemctl start apache2
sudo systemctl enable apache2
```

For Nginx, run:

```
sudo systemctl start nginx
sudo systemctl enable nginx
```

### Section 3.9.6: Open Firewall Ports:

If you have a firewall enabled, allow traffic on the web server port (default is 80 for HTTP and 443 for HTTPS).

```
sudo ufw allow 80
```

### Section 3.9.7: Test the Web Server:

Open a web browser and enter the public IP address of your VM. 

You should see the default page of the installed web server.

That's it! You've successfully deployed a web server on a Linux VM in Azure. 

Depending on your application, you may need to configure additional settings or deploy your web application files to the server.

###  Section 3.10: Azure Virtual Machine - Disks

Lab - Adding data disks

What happens when we stop the machine

###  Section 3.11: Azure Disks - Server Side Encryption

Lab - Azure Key Vault Service

Lab - Disk Encrytion Sets

Lab - Azure Disk Encryption

Quick review on the encryption options

Lab - Data Disks Snapshot

Azure Shared Disks

Custom Script Extensions

Lab - Custom Script Extensions

Lab - Custom Script Extensions for Linux Virtual Machines

Lab - Linux Virtual Machines - Cloud init

Virtual Machine - Boot Diagnostics

Lab - Virtual Machine - Run command

Lab - Virtual Machine - Run command - Resources

Confidential Computing and Azure Dedicated Host

Note - Redeploying a virtual machine

Availability Sets

Availability Sets - Review

Lab - Availability Sets

Lab - Availability Sets - Extra bits

Availability Zones

Lab - Availability Zones

Availability Zones Review

Azure virtual machine scale sets

Lab - Azure Virtual Machine Scale Sets

Azure Virtual Machine Scale Set - Scaling conditions

Virtual Machine Scale Sets - More aspects

Azure Virtual Machine Scale Sets - Flexible Orchestration Mode

Lab - Virtual Machine Scale Sets - Custom Script Extensions

Understanding virtual machine images

Lab - Creating a specialized image

Lab - Using the Specialized image

Lab - Generalized VM Image

Lab - Using the Generalized VM Image

Proximity Placement Groups

Note on deployments

Introduction onto Azure Web Apps

Lab - Azure Web Apps

Lab - Making simple changes to the Web App

Lab - Publishing a .NET project

Installing Visual Studio 2022

More on App Service Plans

Lab - Azure Web App logging

Azure Web Apps - Deployment Slots

Lab - Azure Web Apps - Deployment Slots

Lab - Auto scaling a web app

Azure Web Apps Automatic scaling

Azure Web App - Virtual Network Integration

Lab - Azure Web App - Azure Virtual Network Integration - Setup

Lab - Azure Web App - Azure Virtual Network Integration - Configuration

Lab - Azure Web App - Azure Virtual Network Integration - Resources

Azure Web App - Custom Domains

Azure App Service Backup

The need for containers

Lab - Deploying Docker on a virtual machine

Lab - Running the nginx container on the Linux VM

Lab - Deploying Docker on a virtual machine - Practice commands

The need for an image registry

Lab - Azure Container Registry

Containerize an application - Setup

Containerize an application - Setup - Resources

Containerize an application - Implementation

Containerize an application - Implementation - Resources

Publishing to the Azure Container Registry

Publishing to the Azure Container Registry - Resources

Lab - Azure Container Instances

Lab - Azure Container Groups

Lab - Azure Container Groups - Resources

Azure Container Groups - Probes

Azure Container Apps

Primer on Azure Kubernetes

Lab - Deploying an Azure Kubernetes cluster

Lab - Deploying our application

Lab - Deploying our application - Resources

Azure Kubernetes - Configuring networking

Azure Kubernetes Upgrade cluster

Azure Kubernetes Persistent Storage - Application Setup

Azure Kubernetes Persistent Storage - Application Setup - Resources

Azure Kubernetes Persistent Storage - Build Image

Azure Kubernetes Persistent Storage - Build Image - Resources

Azure Kubernetes Persistent Storage - Using Disks

Azure Kubernetes Persistent Storage - Using Disks - Resources

Azure Kubernetes Persistent Storage - File shares

Azure Kubernetes Persistent Storage - File shares - Resources

## Section 4: Configure and manage virtual networking

## Section 5: Implement and manage storage

## Section 6: Manage Azure Identities and Governance

## Section 7: Monitor and back up Azure resources

## Section 8: Azure PowerShell and Azure CLI

## Section 9: Azure Resource Manager Templates

## Section 10: Bicep language for deploying resources

## Section 11: Practice section



