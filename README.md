# Hyper-V Monitoring

This extension leverages the WMI protocol to collect data from the Windows hypervisor to track health, performance and resource utilization of the VMs in the context of their host, so you can see both the big picture of the cluster and details of each VM.  

**This is intended for users, who:**

- Want to get full monitoring for their Hyper-V clusters 
- Want to monitor Hyper-V at the cluster and virtual host level 

**This enables you to:**

- Monitor health and performance of your Hyper-V cluster 
- Make sure resources are split optimally between the virtual machines

**Compatibility Requirements**
*  x64 OS with BIOS-activated virtualization: 
    * Windows 10 Enterprise/Pro/Education
    * Windows Server 2019
* Hyper-V VM Configuration Version 9.0

**Metrics collected:**

- VMs’ health 
- Memory usage 
- CPU utilization 
- Storage operations 
- VMBus  
- Network traffic  

**This extension is built on top of the new Extension 2.0 Framework and contains:**

- WMI DataSource configuration, 
- Dashboard template, 
- Unified Analysis screen template, 
- Topology definition and entity extraction rules. 
