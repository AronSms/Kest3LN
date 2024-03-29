# KEST2NL05EU LOKAVERKEFNI
**1. Install and configure the server1, client1 and client2 with hostnames and domain as ddp.is**

Ég gerði svo það sama fyrir Client 1 og 2.

<img src="Myndir/Hostname-server1.png">
<img src="Myndir/Domain-server1.png">

**2. configure server1 with static IP Address, from the IP Address block 192.168.100.0/24. The server must be configured with the 10th usable IP Address.**

<img src="Myndir/Network.png">
<img src="Myndir/NetworkConfig.png">
<img src="Myndir/TestPing.png">

**4. Install and configure DNS server on server1, so Hostnames are resolved to IP Addresses.**

Ég installaði DSN pakanum bind9 og seti hann upp.

<img src="Myndir/DNS.png">
<img src="Myndir/DSNConfig.png">

**5. Create the users accounts using a script, see the Users file.**
Ég bjó til .sh scriptu og notaði forloopu til að gera notendur.
<img src="Myndir/CreatUser.png">
<img src="Myndir/UsresCheck.png">

**7. Due to data loss the company policy requires taking backups weekly, as system engineer
you are required to schedule backups of home directories to run weekly at midnight each
Friday**

<img src="Myndir/Backup.png">

**8. Install and configure NTP on the server and clients, server1 must be master server to
synchronize the time of the clients**

Eftir að ég seti NTP up á server tengdi ég cliant 1 og 2  við server.

<img src="Myndir/Ntp.png">

**10. Install and configure Postfix on server1, so users can send and receive emails using Round
Cube open-source software.**

<img src="Myndir/PostfixStatus.png">
<img src="Myndir/SentEmail.png">

**11. Install and configure shared printers for each group, only users that belong to the group
should print only, accept IT and Management groups should print and manage the printers.**

Eftir að hafa breyt aðgegnig fyrir prentar í groupu kékaði ég hvort að hann(prentarinn) veri ekki öruglega til.

<img src="Myndir/CupsPrinter.png">
