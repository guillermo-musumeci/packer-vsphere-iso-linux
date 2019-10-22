# Packer templates for Linux using vSphere-ISO provider

This repository contains **HashiCorp Packer** templates to deploy **Linux** distros in **VMware vSphere ESXi**. 

# Content: #

* CentOS7/centos7-base-vsphere.json --> CentOS7 Packer Base JSON file
* CentOS7/ks.cfg --> CentOS7 Kickstart file

Tested with **VMware ESX 6.7** | User: root | Password: server

# Requeriments: #

* JetBrains-infra vSphere-iso (File Name: packer-builder-vsphere-iso.exe) --> https://github.com/jetbrains-infra/packer-builder-vsphere

* Packer --> https://www.packer.io

* CentOS 7.x ISO --> https://wiki.centos.org/Download
