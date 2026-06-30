# Windows Troubleshooting
## Objective
Learn how to diag and fix errors
## Skills
- Network adapter enabling/ disabling
- Ping basics
- 
## Steps
1. Opened device manager with Win+X and located my network adapters.
2. Checked my Network by running ipconfig to make sure i had an IP, ping 8.8.8.8 to test network connectivity, and ping google.com to check my DNS connectivity
3. Simulated a network outage by right clicking the network adapter to disable it
4. Ran ipconfig, ping 8.8.8.8, and ping google.com again and observed network errors
5. Went back into device manager and enabled device and verified it was working running ipconfig, ping 8.8.8.8, and ping google.com again

When using "ipconfig" it shows the device IP address, verifying that the network, internet and DNS is working. When the netowrk adapter is disabled, the "ping" has no way to send out information to a server or internet thus failing. If "ping 8.8.8.8" is functional but "ping google.com" fails, DNS is broken. If "ping 8.8.8.8" fails then the network is broken. The network connectivity is tested using "Ping 8.8.8.8" but "Ping google.com" tests the network AND the DNS.

6. Ran "ipconfig /all" in cmd prompt. 
