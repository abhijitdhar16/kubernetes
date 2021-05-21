# Kubernetes in a box
## About this tutorial 
This guided tour will help you to setup your own Kubernetes cluster using a oracle virtual box, and to deploy your own pod in that system. At the end of this guided tour you should be able to create a cluster of one master node and two worker nodes.

## Hardware requirement
A powerful laptop that should able to host three full-fledged Ubuntu servers deployed on a virtual box along with all your requirements. An example configuration could be as follows
* Processor: i5-6300U CPU @ 2.40GHz 2.50GHz
* Installed memory (RAM): 16.0 GB
* Operating System: 64 Bit operating system (Windows 10)
* Disk space: Around 500GB

## Software Requirement
* Oracle virtual box version 6.1 or more
* Ubuntu server 20.10

The above software will prepare back-bone of the Kubernetes system. Kubernetes will be overlayed on top of that.  
## Execution sequence 
### 1. Downloads
* Download the oracle virtual box version 6.1 or more from [oracle virtual box site](https://www.virtualbox.org/wiki/Downloads/)
* Download the ubuntu server version 20.10 or more (the .iso image) from [ubuntu site](https://ubuntu.com/download/server/)
### 2. Install Virtual Box
After downloading, installation of virtual box should be a very trivial task.
The installation wizard will guide you through the steps of doing the job. A lot of information about the virtual box is available
[here](https://www.virtualbox.org/manual/)
### 3. Creating three new virtual ubuntu servers on the top of virtual box
