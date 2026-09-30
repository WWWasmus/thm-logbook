# Room: Nmap: The Basics

- **Path:** Cyber Security 101 / Networking
- **Link:** https://tryhackme.com/room/nmap
- **Date:** _fill in your real completion date_
- **Time spent:** _fill in_

## Summary
Host discovery, port scanning, and service detection.

## What I learned
- SYN scan (-sS) vs TCP connect scan (-sT)
- -sV detects service versions, -p- scans all ports
- -Pn skips host discovery when ping is blocked

## Commands worth remembering
```
nmap -sC -sV -oN scan.txt <target-ip>
nmap -p- <target-ip>
```

## What tripped me up
_Fill in from memory._

## To revisit
- [ ] 
