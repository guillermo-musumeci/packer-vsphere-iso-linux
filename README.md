# Packer templates for Linux using vSphere-ISO provider

Deploy a **Linux** template using Hashicorp Packer in VMware vSphere ESXi

This repository contains a Packer template for **Linux** distros

# Content: #

* CentOS7/centos7-vsphere.json --> CentOS7 Packet JSON file
* CentOS7/ks.cfg --> CentOS7 Kickstart file

Tested with **VMware ESX 6.7**

User: root
Password: server

# Requeriments: #

* JetBrains-infra vSphere-iso (File Name: packer-builder-vsphere-iso.exe) --> https://github.com/jetbrains-infra/packer-builder-vsphere

* Packer --> https://www.packer.io

* CentOS 7.x ISO --> https://wiki.centos.org/Download
