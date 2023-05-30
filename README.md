# 📕 Cloud-Init Automation Script for CentOS Stream 8 on Proxmox

This repository contains an automation script and templates for deploying CentOS Stream 8 instances on Proxmox using Cloud-Init. By utilising Cloud-Init in Proxmox, you can automate and customize the initial configuration of your virtual machines, making it easier to deploy and manage them at scale.

## 🚀 Deployment Steps

1. First login to your Proxmox VE host terminal:
2. `wget` this repository.
3. Go to the cloned folder.

### Preparingn Cloud Init Template

1. Go to preparing-cloud-init-template folder.
2. Modify the `preparing-cloud-init-template` environment variables in the .env file according to your requirements.

```console
./create-template.sh
```

### Deploy with Cloud Init

1. Go to deploy-with-cloud-init folder.
2. Modify the `deploy-with-cloud-init` environment variables in the .env file according to your requirements.
3. Modify the `vm-cloud-init.yaml` file according to your requirements.

```console
./deploy-vm.sh
```

## 🔨🔧 Customization
Feel free to modify the deployment script and Cloud-Init template to suit your specific requirements. You can add additional configurations, modify network settings, or adjust any other parameters as needed.

## 🔎 Troubleshooting
If you encounter any issues during the deployment process or while configuring the Cloud-Init template, refer to the Proxmox and Cloud-Init documentation for troubleshooting guidance. You can also check the Proxmox host's log files for any relevant error messages.

## ❗ Disclaimer
This automation script and template are provided as-is and without warranty. Use them at your own risk. Make sure to thoroughly test the deployment in a non-production environment before deploying to production.

## 📄 License

MIT / BSD

## 🇬🇧🇭🇰 Author Information

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Website: https://www.jodywan.com

😊 Enjoy automating your CentOS Stream 8 deployments with Cloud-Init on Proxmox!

