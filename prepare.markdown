---
layout: page
title: Prepare
permalink: /prepare/
---

### Material and software

We expect all attendants to have installed the latest stable release of mc\_rtc available on [GitHub](https://github.com/jrl-umi3218/mc_rtc/releases/latest).

Installation instructions are provided in mc\_rtc website in the [installation guide](https://jrl-umi3218.github.io/mc_rtc/tutorials/introduction/installation-guide.html).

Assuming you have an Ubuntu LTS version installed and a ROS distribution selected, that is:

```bash
# Setup the mirror
curl -1sLf 'https://dl.cloudsmith.io/public/mc-rtc/stable/setup.deb.sh' | sudo -E bash
# Install packages
sudo apt install libmc-rtc-dev mc-rtc-utils
# Assuming you have a ROS distribution mirror setup
sudo apt install ros-${ROS_DISTRO}-mc-rtc-plugin ros-${ROS_DISTRO}-mc-rtc-tools
```

### Pre-installed computers

We will be coming to the conference with a small number of computers with mc\_rtc already installed. Please [contact us]({{site.baseurl}}/contact/) us in advance to use such a machine.

### Virtual machine

You can also download a virtual machine with all software already installed. This image can be loaded in most virtualization softwares.

If you want to use this option but cannot download this image before the tutorial day, we will give you a copy on the day.

Link: TBA

### Troubleshooting

For any trouble with the preparations, please contact [Pierre Gergondet](mailto:pierre.gergondet+tutorial-humanoids2022@gmail.com).
