
The Linux server was investigated using the KillerCoda Playground. The following Linux commands were used to identify the operating system, CPU information, memory, and disk space.

Linux Commands Used

cat /etc/os-release
lscpu
free -h
df -h

Operating System

The investigated server is running Ubuntu 24.04.4 LTS (Noble Numbat). The operating system is Ubuntu and is Debian-based.

CPU Information

The Linux environment reports 1 CPU socket and 1 CPU core. The system is running with KVM full virtualization, indicating that the Linux server is running in a virtualized environment.

Memory

The server has approximately 1.9 GiB of total memory. At the time of the investigation, about 416 MiB was used, 867 MiB was free, and approximately 1.5 GiB was available. The system also has 1.0 GiB of swap space.

Disk Space

The main filesystem /dev/vda1 has a total size of approximately 19 GiB. About 5.4 GiB is used, 13 GiB is available, and the filesystem is 30% used.

Cloud Hosting Options

If this Linux server were migrated to the cloud, the following services could be used to host it:

AWS – Amazon EC2

Amazon Elastic Compute Cloud (EC2) can host the Linux server as a virtual machine in AWS. EC2 allows users to choose computing resources according to the requirements of the workload.

Microsoft Azure – Azure Virtual Machines

Azure Virtual Machines can host Linux-based servers in Microsoft Azure. It allows organizations to deploy and manage Linux virtual machines while selecting appropriate computing, storage, and networking resources.

Google Cloud – Compute Engine

Google Compute Engine can host the Linux server as a virtual machine in Google Cloud. It provides scalable virtual machines that can run Linux operating systems and different types of workloads.

Conclusion

Based on the Linux investigation, the server is running Ubuntu 24.04.4 LTS with approximately 1.9 GiB of memory and a 19 GiB main disk. If migrated to the cloud, equivalent virtual machine services such as Amazon EC2, Azure Virtual Machines, and Google Compute Engine could be used to host the Linux server.

Evidence

Screenshots of the Linux terminal investigation are stored in the screenshots folder.

The screenshots provide evidence of the following:

- Operating System
- CPU Information
- Memory
- Disk Space
