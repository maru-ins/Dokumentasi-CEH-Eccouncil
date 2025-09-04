# 📘 02 Footprinting and Reconnaissance

## 🎯 Konsep Utama
- Reconnaissance adalah proses mencari informasi awal tentang target sebelum menyerang. Informasi ini dipakai penyerang untuk memahami sistem, menentukan cara serangan, dan menemukan celah yang bisa dimanfaatkan.

## 🛠️ Tools yang Digunakan

**1. Find Domain's, Subdomains & Host**
- Netcraft (https://www.netcraft.com)
- DNSdumpster (https://dnsdumpster.com)

**2. Gather Personal Information from various social networking**
- Sherlock (Terminal) :
  ```bash
  sudo su
  sherlock "Target Name"
  ```
- [Social Searcher](https://www.social-searcher.com)  
  Gather target company from Social networking.

**3. Lookup Hostname, IP Address, or Domains**
- Whois (This protocol listens to requests on port 43 (TCP))
  - [Whois](http://whois.domaintools.com)
  - SmartWhois ([Tamos](https://www.tamos.com))
  - Batch IP Coverter ([Sabsoft](http://www.sabsoft.com))

**4. Perform DNS Footprinting**
- NS Lookup
  ```bash
  nslookup
  set type=a
  set type=cname
  ```
- [NSlookup](http://www.kloth.net/services/nslookup.php) Online

**5. Perform Network Tracerouting in Windows and Linux Machines**
- Tracert
  ```bash
  tracert target_domain
  tracert /?
  tracert -h 5 target_domain
  ```
- Traceroute (to view the hops that the packets made before reaching the destination)
  ```bash
  traceroute target_domain
  ```
- Other Tools
  - [PingPlotter](https://www.pingplotter.com/)
  - [Traceroute NG](https://www.solarwinds.com)

**6. Perform Email Footprinting**
- Use [eMailTrackerPro](https://emailtrackerpro.en.softonic.com/) (in Windows) 

**7. Footprinting using Various Footprinting Tools**  
- Recon-ng
```
sudo su  
recon-ng  
help
  ---#list query commands
marketplace install all
  ---#install all modules in recon-ng
modules search
  ---#to search modules after installation
workspaces
  ---#command to view the commands related to the workspaces
workspaces create Workscapacesname
  ---#example workspaces create CEH 
workspaces list
db insert domains
---#domain (TEXT) : www.example.com
---#notes (TEXT) : ....
show domains
```
Issue modules load brute command to view all the modules related to brute forcing. In this task, we will be using the recon/domains-hosts/brute_hosts module to harvest hosts.
18
```
modules load brute
modules load recon/domains-hosts/brute_hosts
run
show hosts
```
To view all the modules associated with the reporting keyword. In this lab, we will save the report in HTML format. So, the module used is reporting/html.
```
modules load reporting 
modules load reporting/html 
```



## 💻 Command / Syntax Penting
```bash
# Tulis contoh command
```

## 🧪 Catatan Praktik Lab
- [Tulis pengalaman atau hasil lab]

---
[⬅ Kembali ke Daftar Modul](README.md)
