# Overview
- Security principle based on checking and verifying everything, without exceptions

# Core Ideas
- Based on never trusting connected devices until verification; even after verification we will run checks to verify further.
- Policy Based Authentication:
	- The user will need to input credentials to verify that they are trying to use a service that they have authorization for using
	- The machine will read the metadata, such as the location, time, habits, scheduling, etc.
- Based on the [[Least Privilege Access|principle of leas privilege]].
- Implemented through the use of [[Security Service Edge (SSE)]].