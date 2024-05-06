These days, cyber-attack is a severe criminal violation, and it is one of the most active fields of research. This project illustrates a detection scheme for ARP spoofing-based MITM(Man-in-the-middle) attack called D-ARP, which is compatible with the original ARP protocol.  A Man-in-the-middle attack (MITM) is a type of cyber-attack in which an unauthorized third party secretly accesses the communication between two hosts in the same network to read/modify the transferred data between them. ARP spoofing-based MITM attack exploits ARP protocol weakness where the attacker associates its MAC address with the IP address of an intended legitimate host. Although there are many defense approaches for ARP spoofing based-MITM attacks, these methods are uncompleted or have a performance overhead since they modify the original ARP protocol. The main idea of D-ARP is to send an ARP packet signed with a key in parallel with the original ARP packets to make a correlation between requests and replies. Each host records all types of signing ARP packets in a log file. Based on this correlation, D-ARP matches the injected key to detect ARP spoofing if there is a duplicate or conflict in the MAC address. Moreover, this also offers a module for admin to create a trusted list of hosts. The experimental results show that D-ARP is highly effective for detecting and preventing ARP spoofing with zero false positives and zero false negative probabilities.
