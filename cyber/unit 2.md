# Password Hacking

DTAE - Discovery, Targeting, Access, Exploitation

dictionary attack (4) (prep, target, iteration, matching)
brute force (4) (target, generation, testing, success/failure)
hybrid attack (4) (seed list, mutation, testing, expansion)
rainbow table (4) (pre computation, target hash retrieval, lookup, recovery)
credential stuffing (4) (data acquisition, automation, exploitation, unauthorized access)
phishing (5) (target, lure creation, delivery, exploit, data theft)
keyloggers (5) (delivery, install & persist, record, data exfiltration, exploit)
shoulder surfing (4) (position, observe, record, exploit)
social engineering (4) (recon, pretext, exploit, execute)
default credential exploitation (4) DTAE

# Rootkits

![[Pasted image 20260921072620.png]]

initial compromise - A rootkit usually requires an existing security vulnerability to gain a foothold. 

installation & privilege escalation - goal here is to elevate permissions to the highest level (Kernel mode) and install the malicious files in areas where standard security software rarely looks. 

hiding - intercept calls made by the OS to the hardware or file system (Hooking)

backdoor & persistence - the rootkit ensures it survives system restarts and allows the attacker a permanent way back in

payload execution - the attacker uses the machine for their specific goals

![[Pasted image 20260921033214.png]]

# Trojan

RAT, backdoor, infostealer, downloader, DDoS, Ransom, Fake-AV

delivery & disguise
user execution and installation - malware copies files and creates startup tasks

persistence & communication - connects to remote server (C&C)

payload execution - steal data/ backdoor access

covering tracks & exploitation - hide activity from user & security software
The Trojan modifies your local firewall rules to allow its traffic and hooks the Windows API to hide its process from the Task Manager list

![[Pasted image 20260921033510.png]]

# Backdoors

software, hardware, web shell, cryptographic, supply chain

![[Pasted image 20260921033725.png]]

# Malware
## Virus

![[Pasted image 20260921034245.png]]

file infector, boot sector, macro virus, polymorphic virus, resident virus, ransomware virus

![[Pasted image 20260921035733.png]]

![[Pasted image 20260921035932.png]]

## Ransomware

![[Pasted image 20260921040252.png]]

## Worms

![[Pasted image 20260921040848.png]]

network, email, crypto, botnet

![[Pasted image 20260921040929.png]]

## Spyware

Spyware is a type of malicious software designed to secretly monitor and record your digital activity

![[Pasted image 20260921041422.png]]

## Adware

Adware (short for advertising-supported software) is a type of program that automatically displays, plays, or downloads advertisements to a computer or device

![[Pasted image 20260921041432.png]]

## Sniffers

Tools that capture and inspect network traffic as it passes by, letting an attacker (or a defender) see the raw data flowing across a network segment. Types

passive, active, wireless, protocol/credential

preparing & positioning
interception
packet capture
data extraction & decoding
exploitation

![[Pasted image 20260921042707.png]]

![[Pasted image 20260921042854.png]]

## Denial of Service

ping of death, syn flood, udp flood, application layer dos, ddos

![[Pasted image 20260921043559.png]]

![[Pasted image 20260921043609.png]]

![[Pasted image 20260921043624.png]]

## Buffer Overflow

![[Pasted image 20260921043759.png]]

![[Pasted image 20260921043851.png]]

# Session Hijacking

 attacker takes over an already-authenticated session between a user and a system, tricking both legitimate parties into believing the attacker is the other party

![[Pasted image 20260921044033.png]]

![[Pasted image 20260921044131.png]]

# Physical Security

Network protection isn't purely a software problem. No matter how strong your firewall is, you also need to guard against attacks from inside the building — statistically, insider threats are more likely than external one

![[Pasted image 20260921044316.png]]

