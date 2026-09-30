# Nmap cheatsheet

| Goal | Command |
|------|---------|
| Default scripts + versions | `nmap -sC -sV <ip>` |
| All ports | `nmap -p- <ip>` |
| Skip host discovery | `nmap -Pn <ip>` |
| Save output | `nmap -oN scan.txt <ip>` |
| UDP top ports | `sudo nmap -sU --top-ports 20 <ip>` |
| OS detection | `sudo nmap -O <ip>` |

_Add to this as you learn._
