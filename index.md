---
layout: default
---

# Security in Networked Systems

14-742 is a graduate-level network security course offered by the [Information Networking Institute](https://www.cmu.edu/ini) at [Carnegie Mellon University](https://www.cmu.edu/).


### Course Description

The Internet was built on unsecured foundations and is constantly growing and changing, and enterprise Internet connectivity amplifies the implications of this design. Exploitation of network infrastructure often serves as a stepping stone to a much broader class of cyber attacks. This course guides students through a holistic exploration of threats against network systems and provides opportunities for hands-on experimentation with classical and modern approaches to reconnaissance, attack, detection, and defense techniques. Topics include attacks and defenses at the link, network, and transport layers; design issues and vulnerabilities in the TCP/IP protocol stack; denial-of-service attack, detection, and reaction; securing routing protocols; network intrusion detection and response; traffic analysis; and anonymity.


### Learning Objectives

In taking and completing this course, students will:
* Explore and create customized software implementations of common network security components including firewalls, VPNs, IDS;
* Demonstrate expertise with attack and defense techniques, including network reconnaissance (e.g., traffic analysis), network vulnerabilities and attacks, securing network services and protocols, monitoring, and protocol adaptation;
* Perform hands-on experimentation with and evaluation of attacks such as denial of service, worm/virus propagation, and stepping-stone attacks as well as corresponding detection and defense mechanisms.


### Lab Assignments

Labs are a major component of the 14-742 course and the basis for the majority of the course learning objectives. Labs will be done individually, and deliverables will be managed in a repository within this GitHub organization.  In addition, students in the 14-742 course self-organize into groups to execute a semester-long project on a topic of their choice, subject to approval.

The course includes a total of five lab assignments, using a variety of programming languages, an open-source network emulator, and various open-source tools.  Brief descriptions of these labs are included here, while further information is made available to students enrolled in the course.

<details><summary>Lab 0: Environment and Network Emulator Setup</summary><p>This lab focuses on setting up your development environment, getting familiar with the network emulator, running a few simple socket-based services, and using built-in tools for network performance analysis.  Strong understanding of the emulator, sockets, and the relevant tools serve as the foundation of upcoming labs.  Programming tasks for this lab can be completed in C, Go, Python, or Rust.</p></details>

<details><summary>Lab 1: Custom Network Utilities using Socket Programming</summary><p>This lab builds on basic understanding of networking, raw socket programming, and network vulnerabilities in some of the most popular networking protocols. Students implement and experiment with a variety of attack primitives in the emulated network environment with the goal of gauging the impact of these attack primitives on network availability and utilization. The primitives developed in this lab are used for evaluating attack and defense techniques in upcoming labs.</p></details>

<details><summary>Lab 2: Open-Source Networking Tools</summary><p>This lab serves as a relatively quick exploration of how SSL/TLS, SSH, and VPN software is used in practice.  Students use OpenSSL, OpenSSH, and OpenVPN to create private networks within an emulated network environment and extend tools from the previous lab to include these traffic types.  This lab is intentionally much more lightweight than the others, as it occurs at the same time that students are preparing project proposals.</p></details>

<details><summary>Lab 3: Exploration with Software-Defined Networking</summary><p>This lab gives students hands-on experience with Software-Defined Networking technologies, incorporating OpenVSwitch, OpenFlow, and at least one SDN controller framework into the emulated network environment.  The lab initially focuses on how to integrate the various SDN components into a functional network and how to build interesting control applications on top of them.  The lab then turns its focus on the development of tools and techniques for detection, accounting, and prevention of various attacks in an enterprise networking scenario, leveraging tools created in previous labs.  The target SDN controller framework used in this lab is built in Python, but other options are available if desired, and tool components can be developed in any suitable language.  In the final task of this lab, students have an opportunity to think more holistically about internal and external threats, roles and authorization for different groups of enterprise users, and what protections could be deployed in the system.  Students build out a selected few of the identified attack and defense mechanisms and evaluate their security benefits, deployment/management costs, and performance overhead.</p></details>

<details><summary>Lab 4: Containers and Virtualization</summary><p>This final lab provides an opportunity for students to extend their study of network security to the domain of virtualized networks used in container-based virtualization platforms.  Students will gain hands-on experience with Linux virtual networking, network namespaces, containerized services, and common techniques for managing access controls and other container protection mechanisms.</p></details>
<p></p>

### Code Management & Testing Infrastructure

This course uses GitHub to initialize and maintain students' code repositories for the labs and project.  In addition, there is an external testing service that can be used to deploy student deliverables for testing in a backend server under control of the course staff.  This service is used for grading and debugging student work, along with documentation components that are graded manually by the course staff.

### Questions and Contact

Please direct questions about the 14-742 course to [Patrick Tague](mailto:tague@cmu.edu).

