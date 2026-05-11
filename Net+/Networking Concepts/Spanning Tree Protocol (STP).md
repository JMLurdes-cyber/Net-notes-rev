# Overview
- Allows switches to connect several simultaneous links to other switches without causing issues, such as [[ROUTING LOOPS|loops]].

# Core Ideas
- **Spanning Tree Protocol** a.k.a. **STP** allows for the *safe* connection of several links to other bridges
- The switches are nicknamed "bridges" when we are talking about STP
- Works to up to 15 switch loops
- Doesn't add up the speed of the bridges, we use [[Link Aggregation]] for that.

# Functions
- Automatically calculates which link to break to avoid issues
- In case of the failure of a link, it makes the switch between the broken link and the deactivated link automatically.
	- The switch takes up to 30 seconds with normal STP
	- The switch is immediate with Rapid STP (RSTP)

# Port States
- Blocking: No traffic is allowed to pass
- Listening
- Learning
- Forwarding: Traffic passes through
- Disabled

# Port Roles
- Root Port
- Designated Port
- Non-designated Port ( or Alternate Port)
- Disabled


