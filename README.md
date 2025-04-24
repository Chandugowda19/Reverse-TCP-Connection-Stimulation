# Reverse-TCP-Connection-Stimulation
 Metasploit and msfvenom is used to create a malicious payload (reverse_shell.exe) for covert remote access. The payload was hosted on a local HTTP server and executed on a target Windows machine, establishing a reverse TCP connection back to the attacker's system. Using Metasploit's handler, remote command execution was achieved.
### Reverse TCP Connection Simulation
- Simulated a reverse shell attack using Metasploit Framework and msfvenom to demonstrate remote exploitation techniques.
- Generated a malicious payload (reverse_shell.exe) configured to establish a covert reverse TCP connection from the target to the attacker’s machine.
- Hosted the payload on a Python HTTP server for delivery and executed it on the target machine to gain unauthorized access.
- Configured and deployed a Metasploit handler to receive the reverse shell connection, enabling remote command execution.
- Performed post-exploitation activities, including system reconnaissance (sysinfo) and keystroke logging (keyscan).
- Analyzed attack vectors and emphasized defensive measures such as firewall rules, IDS monitoring, and user awareness to mitigate risks.
- Tools Used: Metasploit, msfvenom, Python HTTP Server, Windows OS.
