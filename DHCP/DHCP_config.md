**DHCP Server set up with a single scope of 172.16.0.100-200, DNS: 172.16.0.1 (Domain Controller used as DNS), Default Gateway: 172.16.0.1 which is the DC's Ipv4 (Clients will use the internal NIC of the domain controller as the default gateway/router)**

This will allow the Windows 10 Client to automatically get an IP address, which lets them access the internet, regardless of being on this private internal network- similar to an office setting.

Server Manager > Add Roles and Features Wizard > Install DHCP

<img width="394" height="447" alt="Screenshot 2025-08-10 022552" src="https://github.com/user-attachments/assets/344c473f-3993-431e-9771-29cf9b1644e4" />
<img width="756" height="349" alt="Screenshot 2025-08-10 022401" src="https://github.com/user-attachments/assets/eacb152c-d629-4d9f-86b0-e9ca0d0636e8" />

**Ensuring the Windows 10 client was on there after creation:**
<img width="759" height="351" alt="Screenshot 2025-08-10 022434" src="https://github.com/user-attachments/assets/8d920243-2537-4f3f-b022-d7d86d2d80d1" />
