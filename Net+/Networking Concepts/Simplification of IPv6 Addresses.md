- Writing the full address can be a cumbersome task, so over time, several rules got standardized to be able to shorten the IPs.
 To give an example, we can use the previous addresses.
*2001:0DB8:0002:008D:0000:0000:00A5:52F5*
### Eliminate the leading 0s
- Erasing the 0s doesn't change the value, since we are aware that there are always 4 nibbles in each value in a IPv6 address.
	- The result would end up being:
		2001:DB8:2:8D:0:0:A5:52F5

### Replace the remaining 0s with "::"
- The double colon usually ends up in the [[IP Host portion|Interface Identifier]] side of the network
	- The result would end up being:
	  2001:DB8:2:8D::A5:52F5
- There can **only be one double colon per address.** More than that creates confusion in the amount of 0s that are found in the address.
	- F.ex. 1:DC::5::D87 can technically either be:
		- 1:DC:5:0:0:5:0:D87 or 1:DC:5:0:5:0:0:D87.

