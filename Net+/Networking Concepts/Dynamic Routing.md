# Overview
- An explanation of **Dynamic Routing** alongside the methods used for it to fulfill its objective.

# Core Idea
- The routers use integrated protocols to choose the best route based on a [[Metric]].
- Better than [[Static Routing]] in bigger organizations, in which the path may be messy or expected to expand some way.
- Uses one of two main protocols:
	- [[Open Shortest Path First (OSPF)]] in most devices. 
		- Uses Bandwidth as the metric.
	- [[Enhanced Interior Gateway Routing Protocol (EIGRP)]] in Cisco devices.
		- Uses Bandwidth, delay, load and reliability as metric.

 - In this setup, the routers fill in the missing addresses in the routing tables of their connected routers and then use the metric chosen to calculate the best path.
- If a route is broken, the protocol also sends a message to remove it from the routing tables of both directly and interconnected devices.
- To calculate the optimal path we use [[Metric|metric]] as the main value alongside [[Administrative Distance]]