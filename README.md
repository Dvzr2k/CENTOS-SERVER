# Centos-server

This repository contains a CentOS server environment with the Apache web server (httpd) configured, created using Vagrant. Additionally, it includes integration with a FrontEndStore project from https://github.com/Dvzr2k/Front-End-VideogameStore.git feel free to use.

This project demonstrates the principles of Infrastructure as Code (IaC)

- **Vagrantfile**: Defines the configuration of the virtual machine and necessary provisions.
- **Provisioning Scripts**: Install and configure necessary packages, including httpd and other dependencies.
- **FrontEndStore Project**: Integrates with a FrontEndStore project to deploy a web application.

## Usage

1. Clone this repository to your local machine.
   git clone https://github.com/Dvzr2k/Centos-server.git
3. Run the following commands to create and configure the virtual machine.
   ```sh
   cd Centos-server-main
   vagrant up
   
5. Access the assigned IP address of the virtual machine to see the FrontEndStore application in action.
   ![image](https://github.com/Dvzr2k/Centos-server/assets/129244345/e0e293dc-5162-475f-bb9e-455b6bd87ac7)

Enjoy developing!
