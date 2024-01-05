# Kubernetes on VirtualBox with Vagrant: Quick Setup
For detailed implementation guidance, troubleshooting tips, and code explanations, check out [article](https://arambarca.com/p/kubernete-vagrant-virtualbox/).
## Quick setup:
```bash
git clone https://github.com/ngrassa/Kubernetes-Vagrant-VirtualBox.git
cd Kubernetes-Vagrant-VirtualBox
vagrant up
sudo kubectl get nodes
```
## Note:
To customize worker nodes, open the Vagrant file andmodify the following settings::
- **workers:**  to change the number of working nodes `Defualt: 3`
- **ram_worker:**   to djust the allocated RAM for each worker node `Default: 2Gb`
- **cpu_worker:**  tdjust the number of CPU cores allocated for each worker node `Default: 2 Cores`
