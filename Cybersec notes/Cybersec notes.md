# 🛡️ Cybersecurity Learning Notes

## 📅 Postępy
- [x] Introduction to Cybersecurity – Module 1
- [x] Introduction to Cybersecurity – Module 2
- [x] Introduction to Cybersecurity – Module 3
- [ ] Introduction to Cybersecurity – Module 4
- [ ] Cybersecurity Essentials
- [ ] CompTIA Security+ (planowane)

---

# 🐧 Linux Basics

## 📂 Nawigacja po systemie
- `pwd` → pokaż bieżący katalog
- `ls` → lista plików
- `cd` → zmiana katalogu
- `tree` → struktura katalogów

## 📂 Operacje na plikach
- `touch plik.txt` → utwórz plik
- `cp plik.txt kopia.txt` → kopiowanie
- `mv plik.txt nowa.txt` → przenoszenie/zmiana nazwy
- `rm plik.txt` → usuń plik

## 📂 Uprawnienia
- `ls -l` → sprawdź uprawnienia
- `chmod 755 plik.sh` → zmiana uprawnień
- `chown user plik.txt` → zmiana właściciela

---

# 🌐 Cisco Cybersecurity Notes

## 🔒 Basics
- Cybersecurity = ochrona **CIA triad** (Confidentiality, Integrity, Availability)
- Ataki: malware, phishing, ransomware, DDoS
- Threats: insider threats, human error

## 🔐 Security Appliances
- Firewalls - look deeper in network connection and can identify malicious behaviour
 - Network based firewalls filter communications based on source and destination IP addresses
 - Transport layer firewalls filter communication based on source and destination data ports as well as connection states
 - Application layer firewalls filter communication based on an application, program or service
 - Context aware layer firewalls filter communication based on the user, device, role, application type and threat profil
 - Proxy server filters web content requests like URLs, domain names and media types.
 - Reverse proxy servers placed in front of web servers, reverse proxy servers protect, hide, offload and distribute access to web servers.
 - Network address translation (NAT) firewall - This firewall hides or masquerades the private addresses of network hosts.
 <!-- - Host based firewalls - Filters ports and system service calls on a single computer operating system. -->
- Routers - they can provide basic traffic filtering capabilities
- IPS use a set of traffic signatures to match and block malicious traffic and attacks
- VPNs - let you use a secure encrypted tunnel from your mobile computer and securely connect back to the organization's network
- Antimalware or Antivirus - These systems use signatures or behavioural analysis of applications to identify and block malicious code from being executed
- Other security devices such as: web and email security appliances, decryption devices, client access control, servers and security management systems.

## Penetration test
- How to run a pen test in 5 steps: 
    - Footprinting through the network to find ways to intrude gives you a chance to gather the information you need to plan a simulated attack.
    - Scanning a target allows you to identify potential exploitable weaknesses.
    - You will need to gain access to a network to exploit any vulnerabilities and simulate an attack.
    - Maintaining access, without being detected, means that you can gather further information on a target’s vulnerabilities.
    - Your findings will be reported to the organization so that security improvements can be made.

# 💻 Git & GitHub Notes

## 🔹 Podstawowe komendy
- `git init` → zainicjuj repozytorium
- `git status` → sprawdź zmiany
- `git add .` → dodaj wszystkie zmiany
- `git commit -m "opis"` → zatwierdź zmiany
- `git push origin main` → wypchnij na GitHub

## 🔹 Workflow
1. Zrób zmiany lokalnie
2. Commit
3. Push na GitHub
4. Utrzymuj README.md jako dokumentację

---

# ✅ Zadania / Checklisty
- [✅] Dokończyć Introduction to Cybersecurity (moduł 4 + egzamin)
- [ ] Ćwiczyć 10 komend Linuxa dziennie
- [ ] Uzupełnić notatki w GitHub README.md
- [ ] Nauczyć się podstaw Gita (init, add, commit, push)
- [ ] Stworzyć pierwsze repozytorium z notatkami