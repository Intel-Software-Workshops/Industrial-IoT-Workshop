﻿# Intel Industrial IoT Workshop

Welcome to the Intel Industrial IoT Workshop. In this workshop, we will explore Industry 4.0 technologies through lectures and hands on labs. By the end of the workshop, you should have a solid understanding of different Industry 4.0 technologies and have some working ideas of how to implement them in your place of business.

## Quick Start EIS 2.3

```bash
xhost +
sudo su
tar zxvf IEdgeInsights-2.3.tar.gz
cd IEdgeInsights/docker_setup/provision
docker rm -f $(docker ps -a -q)
./provision_eis.sh ../docker-compose.yml
cd ..
docker-compose up --build

```

## How Do I Use the Lab Material

The links below will guide the workshop attendee through the slides, videos and labs in the Intel Industrial IoT Workshop.

## Schedule - Day 1

| Jan 23rd           |                                                                      |
|-----| ------------------------------------------------------------------------------- | 
| Doors Open for Badge Pickup                                                     |                                                                                                 |
| Presentation: Intel for Industry 4.0                 | [Slides](./presentations/2.1/Intel-for-Industrial-IoT.pdf)            |
| Presentation: Introduction to Intel Edge Insights Software                 | [Slides](./presentations/2.1/EIS-Intro.pdf)            |
| Demo: Worker Safety Detection Demo | [Demo](https://software.intel.com/en-us/iot/reference-implementations/safety-gear-detector) |                  |
| Demo: PCB Anomaly Detection on EIS                                              |                                                                                                 |
| Break                                                    |                                                                             |
| Presentation: EIS Architecture                    | [Slides](./presentations/EIS_Architecture.pdf)  |
| Lab: Overview of the Intel Edge Insights Software| [Lab](https://github.com/SSG-DRD-IOT/EIS-documentation/blob/master/README.md)|
| Lab: EIS Build Environment and Configuration                                          | [Lab](https://github.com/SSG-DRD-IOT/lab-restricted-zone-notifier-using-EIS/blob/master/explore_IEdgeInsights.md)  |
| Lab: Video Ingestion, Cameras and Video Streams | [Lab](https://github.com/SSG-DRD-IOT/EIS-documentation/blob/master/ingestion.md)|
| Presentation: Intel Developer Program                 | [Slides](./presentations/2.1/Intel-Developer-Program.pdf)            |
| Lab: User Defined Functions, Filters, Classifiers | [Lab](https://github.com/SSG-DRD-IOT/EIS-documentation/blob/master/udfs.md)|
| Lab: Worker Safety Gear Setup in EIS| [Lab](https://github.com/SSG-DRD-IOT/lab-restricted-zone-notifier-using-EIS/blob/EIS-2.0-Workshop/understanding_ri_to_eis_conversion.md)
| Lunch  
| Presentation & Demo: Hardware Acceleration with HDDL-R                          | [Slides](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/SMG-Techconnect/presentations/VPU_Intro.pdf)                                                                               |
| Lab: Offloading Workloads to Accelerators in DevCloud                           | [Lab](https://colfaxresearch.com/iot-devcloud/)                                                                                 |
| Presentation: Hardware Kits                    | [Slides](./presentations/2.1/Industrial-Hardware.pdf)  |
| Lab: Time Series Data                                                           | [Lab](https://github.com/SSG-DRD-IOT/EIS-documentation/blob/master/time-series.md) |
| Lab: Explore Industrial Reference Implementations and DevCloud                              | [Lab](https://software.intel.com/en-us/iot/reference-implementations)                           |

#### Extra Resources

- Introduction
  - [Intel Industrial Applications Webpage](https://www.intel.com/content/www/us/en/internet-of-things/industrial-iot/overview.html)
- Virtualization
  - Videos
    - [Intel® Virtualization Technology](https://www.youtube.com/watch?v=gqZrarZiHp8&t=22s)
    - [Intel® VMDq(Tm) Demonstration - Live](https://www.youtube.com/watch?v=lOBOEcBSSkQ)
    - [Intel(r) SR-IOV(TM) Explanation](https://www.youtube.com/watch?v=hRHsk8Nycdg)
    - [Intel® Virtualization Technology for Connectivity (VT-c) - KMedia Channel](https://www.youtube.com/watch?v=Y-EaX3BBzSc&t=3s)
  - Whitepapers
    - [Intel® VMDq Technology: An Overview](https://www.intel.com/content/dam/www/public/us/en/documents/white-papers/vmdq-technology-paper.pdf)
- Resources
  - [Virtual Machine Device Queues](https://www.intel.com/content/www/us/en/ethernet-products/converged-network-adapters/io-acceleration-technology-vmdq.html)
  - [Intel(r) Ethernet Controller i210 FAQ](https://www.intel.com/content/dam/www/public/us/en/documents/faqs/ethernet-controller-i210-i211-faq.pdf)
  - [Components of Linux Traffic Control](http://tldp.org/HOWTO/Traffic-Control-HOWTO/components.html)

* **HW Acceleration with Intel® Movidius™ Neural Compute Stick**
  - Lab - [HW Acceleration with Intel® Movidius™ Neural Compute Stick](https://github.com/intel-iot-devkit/smart-video-workshop/HW-Acceleration-with-Movidious-NCS/README.md) -->
