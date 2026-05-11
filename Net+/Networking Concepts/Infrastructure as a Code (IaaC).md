# Overview
- Logical Script or Template of  a system that is going to be set up in an enviroment.

# Core Ideas
- Allows the automatic Provisioning of Equipment of Equipment which:
	- Reduces Errors
	- Reduces Redeployment Time.

- Creates consistency of configuration, since whenever a [[Virtual Private Clouds (VPC)|VPC]] is implemented, the others can be immediately upgraded or updated.
- Creates a [[Dynamic Inventory]].
- To be deployed it uses:
	- **Template**s,  which defines the configuration parameters
	- **Playbooks**, which defines the logic to deploy the template
	- **Reusable Tasks**, which defines tasks/services that can be copied from a template and transferred between them.
- Allows the implementation of [[Source Control]].

# Examples
- If a company provides a [[Virtual Private Clouds (VPC)|Virtual Private Cloud]] to clients that is supposed to be immediately set up based on a pre-made structure.