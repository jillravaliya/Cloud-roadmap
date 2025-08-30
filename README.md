# Cloud & DevOps Engineer Learning Path 🌐☁️

---

## 🌐 Layer 0 – Computer & OS Fundamentals

### Theory
*   **What is a computer:** Basic components and functionality.
*   **CPU, RAM, Storage, Network Interface:** Core hardware components and their roles.
*   **Operating systems:** Understanding the kernel, processes, and system calls.
*   **Server vs Desktop:** Key differences in purpose and configuration.
*   **Physical vs Virtual Machines:** Concepts of virtualization.
*   **Software vs Hardware:** The fundamental difference.
*   **File system concepts:** Directories, files, and permissions (read, write, execute).

### Practical (Command Line)
*   `pwd` – shows current directory path
*   `ls -la` – lists all files with details and permissions
*   `cd` – changes directory
*   `tree` – shows directory structure
*   `touch` – creates empty files or updates timestamps
*   `mkdir -p` – creates directories including parent directories
*   `rm -rf` – removes files/folders recursively and forcefully
*   `cp -r` – copies files/directories recursively
*   `mv` – moves or renames files/directories
*   `ln -s` – creates symbolic links
*   `cat` – displays file content
*   `less` – views file content page by page
*   `head -n` – shows first n lines of file
*   `tail -f` – shows last lines and follows file changes
*   `more` – displays file content one screen at a time
*   `file` – determines file type

---

## 🌐 Layer 1 – Networking Theory for Cloud

### Theory
*   **Networking Basics:** What is a network, LAN, WAN, Internet.
*   **IP addresses:** Public vs private, subnetting basics.
*   **Key Concepts:** Router vs Switch, DNS, HTTP/HTTPS, client-server model.
*   **Models & Data:** OSI 7 layers, TCP/IP model, packets/frames, routing vs switching.
*   **Advanced Concepts:** VLAN, Firewall, VPN, Load balancer.

### Practical
*   `ip addr` – shows/configures network interfaces
*   `ip route` – shows/manages routing table
*   `ifconfig` – legacy interface configuration
*   `nmcli` – network manager command line tool
*   `ping` – tests network connectivity
*   `traceroute` – traces network path to destination
*   `mtr` – combines ping & traceroute
*   `nc` (netcat) – port scanning & data transfer
*   `telnet` – test TCP port connectivity
*   `dig` – DNS lookup
*   `nslookup` – query DNS servers
*   `host` – simple DNS lookup
*   `netstat -tuln` – shows listening connections
*   `ss -tuln` – modern netstat replacement
*   `lsof -i` – lists network connections by process

---

## 🌐 Layer 2 – Linux Theory for Cloud

### Theory
*   **Linux Role:** Why Linux is dominant in the cloud.
*   **Linux Architecture:** Kernel, shell, filesystem hierarchy.
*   **Users & Permissions:** Users, groups, and file permissions.
*   **File Types:** Regular, directory, symlink, device.
*   **Processes:** Processes, jobs, systemd, and services.
*   **Package Management:** RPM (YUM/DNF) vs DEB (APT).
*   **Storage:** Disk concepts, LVM (Logical Volume Manager) basics.
*   **Networking:** Basic networking concepts in Linux.

### Practical
*   `ps aux` – shows running processes
*   `pstree` – displays processes in tree format
*   `top` – real-time process info
*   `htop` – interactive process viewer
*   `kill`, `pkill` – terminate processes
*   `jobs` – lists active jobs
*   `bg`, `fg` – background/foreground jobs
*   `nohup`, `disown` – keep jobs running after logout
*   `screen`, `tmux` – persistent terminal sessions
*   `df -h` – disk space usage
*   `du -sh` – directory size summary
*   `lsblk` – lists block devices
*   `fdisk -l` – lists disk partitions
*   `mount`, `umount` – mount/unmount filesystems
*   `pvs`, `vgs`, `lvs` – LVM info
*   `lvcreate`, `lvextend` – LVM volume operations
*   `scp` – secure file copy
*   `rsync -av` – sync files/folders
*   `wget` – download files from web
*   `curl` – transfer data via protocols

---

## 🌐 Layer 3 – Linux Security & Automation

### Theory
*   **Security:** SSH, Firewall basics, Users/Groups, File security.
*   **Hardening:** System hardening, sudoers, fail2ban.
*   **Shell Scripting:** Variables, arrays, functions, loops, conditionals.
*   **Automation:** Cron jobs, environment variables.

### Practical
*   `ssh-keygen` – generate SSH keys
*   `ssh-copy-id` – copy public key to remote server
*   `ssh -L` – local port forwarding
*   `iptables`, `ufw`, `firewall-cmd` – firewall management
*   `useradd`, `usermod`, `passwd`, `sudo` – user management
*   `chmod +x`, setuid, setgid, sticky bit – file permissions
*   Shell scripting exercises & cron automation

---

## ☁️ Layer 4 – Cloud Fundamentals

### Theory
*   **Cloud Computing:** What it is, traditional IT vs cloud.
*   **Cost Models:** On-prem vs cloud, CapEx vs OpEx.
*   **Core Attributes:** Scalability, elasticity, pay-as-you-go.
*   **Service Models:** IaaS, PaaS, SaaS, FaaS.
*   **Deployment Models:** Public, Private, Hybrid, Multi-cloud.
*   **Business Benefits:** Advantages of cloud for businesses.

### Practical (Hands-on with major providers)
*   **AWS:** Launch EC2, create S3 bucket, IAM user/role.
*   **Azure:** Create VM, storage account, resource group.
*   **GCP:** Create VM, Cloud Storage bucket.
*   **Cloud Networking:** VPC, subnets, route tables, security groups/NACLs.
*   **Serverless:** Deploy a simple Lambda/Azure Function/Cloud Function.
*   **Scaling:** Auto-scaling group + Load balancer setup.

---

## ☁️ Layer 5 – Modern App Architecture & Containers

### Theory
*   **Architecture:** Monolithic vs Microservices, SOA.
*   **APIs:** API basics: REST, HTTP methods.
*   **Containers:** Containers vs VMs, orchestration (Kubernetes), persistent storage.

### Practical
*   **Docker:** `pull`, `run`, `ps`, `logs`, `exec`, `inspect` – container commands.
*   **Dockerfile:** Build an image from a Dockerfile and understand the container lifecycle.
*   **Kubernetes:** `kubectl` basics, pod, deployment, service creation.
*   **Storage:** Persistent volumes & ConfigMaps.

---

## 🔐 Layer 6 – Cloud Security

### Theory
*   **IAM:** Shared responsibility model, IAM, MFA, RBAC, least privilege.
*   **Network Security:** SSL/TLS certificates, firewall/WAF, DDoS protection.
*   **Compliance:** Cloud compliance standards: GDPR, HIPAA, SOX.

### Practical
*   IAM policy creation & testing.
*   MFA setup on a cloud account.
*   Configure security groups/NACLs to restrict traffic.
*   Deploy SSL/TLS certificates (e.g., using AWS ACM or Let's Encrypt).
*   Run a vulnerability scan using `lynis` or cloud-native tools.

---

## 📊 Layer 7 – Cloud Operations & Monitoring

### Theory
*   **Reliability:** High Availability, fault tolerance, disaster recovery.
*   **Management:** Backup strategies, scaling, load balancing.
*   **Optimization:** Performance monitoring, cost optimization, cloud pricing models.
*   **Real-world:** Analyzing real-world cloud issues: outages, bottlenecks, cost overruns, security incidents.

### Practical
*   Create CloudWatch/Cloud Monitoring dashboards & alarms.
*   Test scaling policies by generating load.
*   Snapshot a volume/VM and restore it.
*   Set up and review a cost monitoring dashboard.
*   Simulate downtime (terminate an instance) and test recovery procedures.

---

## 🎯 Layer 8 – Mini Projects (Combine Everything)

### Practical Projects
1.  **Web Server on Cloud VM:** Deploy a website on EC2/Nginx or Azure VM/IIS.
2.  **Cloud Storage Integration:** Connect the website to S3/Blob Storage/Cloud Storage for assets.
3.  **Scalable Infrastructure:** Setup auto-scaling + load balancer for the website.
4.  **Secure Access:** Implement IAM roles + least privilege access for the EC2 instance.
5.  **Automated Backups:** Write a cron job backup script for the website files and database.
6.  **Containerize the App:** Deploy the application as a container using Docker & Kubernetes.
7.  **Monitor the Application:** Set up monitoring and alerting for the app's performance.
8.  **Disaster Recovery Drill:** Simulate a failure (e.g., zone outage) and test recovery.

