# Virtual-Network-VMware
# Virtual Network with VMware

This project demonstrates how to create a virtual network using VMware Workstation, and how to create multiple virtual machines that can communicate with each other over a private network.

## Requirements

- VMware Workstation (tested with version 16)
- Adequate system resources (RAM, disk space, etc.)

## Installation

1. Install VMware Workstation on your computer by following the instructions provided by VMware.
2. Once installed, launch the software and create a new virtual machine by selecting "New Virtual Machine" from the "File" menu.
3. Follow the prompts to create a new virtual machine, including selecting the operating system and allocating appropriate resources such as memory and disk space.
4. Repeat step 2 and 3 to create additional virtual machines that will be part of the virtual network.
5. Configure the network settings for each virtual machine to use the "VMnet2" network adapter, which is a private network adapter created by VMware.
6. Start each virtual machine and configure the network settings for each virtual machine, including assigning a static IP address and setting the default gateway to the IP address of the virtual router.
7. Test the network connectivity between the virtual machines by pinging each other's IP address.

## Usage

- This project can be used as a starting point for creating virtual networks using VMware, and can be customized to suit specific network requirements.
- Additional virtual machines can be added or removed from the network as needed by following the same steps outlined in the installation section.

## Troubleshooting

- If virtual machines are unable to communicate with each other, double-check that the network settings are correctly configured to use the "VMnet2" network adapter and that the virtual machines have unique IP addresses within the same subnet.
- If network connectivity is still an issue, refer to the documentation provided by VMware or seek assistance from online forums or support communities.

