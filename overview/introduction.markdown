---
layout: default
title: Introduction
published: true
sorting: 1
---

CFEngine is a configuration management system that provides a framework for automated management of IT infrastructure throughout its life cycle.

CFEngine is decentralized and highly scalable. It is powered by autonomous agents that can continuously monitor, self-repair, and update or restore an entire IT system every five minutes, with negligible impact on system resources or performance.

CFEngine:

* Defines the configuration of an entire IT system consisting of interconnected:
	* Devices
	* Users
	* Applications
	* Services 
* Helps maintain that system over time. 
* Checks the system state at any given moment. 
* Ensures compliance with a desired system state. 
* Propagates real-time modifications or updates across the system.

## How CFEngine Works ##

CFEngine ensures that the actual state of a system is in compliance with the predefined model of desired state for the system. If it is not in compliance CFEngine will bring it into compliance.

That model is represented by one or more policies that have been written using the declarative CFEngine policy language. The policy language has been designed with a vocabulary that is intuitive, yet at the same time can still support the design of highly complex IT systems.

Those policies are distributed across all of the system’s policy distribution servers via pull requests, and then further disseminated to each end host within the system. Every host will then interpret and execute each of the instructions it has been given in a predetermined order. 

CFEngine continually monitors all of the hosts in real-time, and should the system’s current state begin to drift away from the intended state then CFEngine will automatically take corrective action to bring everything back into compliance.

See Also: [Guide][Guide],[System Overview][System Overview],[Policy and Promises Overview][Policy and Promises Overview]

















