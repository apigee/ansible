> These are not officially supported Google products.


# Private Cloud Ansible Repositories


## Installation Quick Launch

Repository: <https://github.com/apigee/ansible-install>

A set of lightweight roles and playbooks to manage the installation of Apigee Edge, create an Apigee mirror, and start and stop Apigee Edge services. These roles and playbooks provide the simplest possible interface to install an Apigee planet using Ansible. They drive the installation using ideal defaults and require just a few simple steps to perform a full installation. They do not cover additional operational tasks you may wish to perform such as infrastructure creation, OS management, Apigee planet expansion, and other tasks.


## Multi-Environment Management

Repository: <https://github.com/apigee/ansible-opdk-accelerator>

This repository contains a set of roles and playbooks to manage the installation, configuration, and maintenance of Private Cloud across multiple environments regardless of the size of those environments. These playbooks will ensure that Apigee requirements are met regarding the configuration of the operating system, the bootstrap configuration and the installation of components. The operating system prerequisites are managed with the option to defer management of specific items. The bootstrap configuration is managed whether you do an online installation or exercise one of the two offline installation options. Component installation is managed so that all configuration files are generated to the topology indicated and role of the individual node. These playbooks create a central location from where to manage Private Cloud installations.


## Monitoring and Troubleshooting

Repository: <https://github.com/maruti123/apigee-pc-auto>

This repository contains Ansible playbooks which can be helpful during the various steps of private cloud topology design and for day to day operations/platform maintenance activities.

This can be used to generate topology for new or existing planet architecture, create port requirements list which would be very handy during firewall and connectivity discussions, scans existing planet setup by analyzing port connectivity between various components, exports component wise log files, retrieves custom properties per component, hardware and memory utilization report for each component, fetches component registration information with reference to each component.
