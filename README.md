# Personal Kubernetes Setup

## Hardware and Node Responsibilites

The cluster currently runs off of 3 Raspberry Pi's. 1 Pi currently serves as a Control Panel, while the other two serve as worker nodes.
Having only 1 Control Panel serves as a potential reliability risk but is a tradeoff to allow the other two nodes to be fully devoted to Pods.

## Current Running Software

Currently, only one container is being ran, and it is a minecraft server. Inside the minecraft folder are the files used for generation.
