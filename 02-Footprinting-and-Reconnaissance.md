# 📘 02 Footprinting and Reconnaissance

## 🎯 Konsep Utama
- [Tulis ringkasan konsep di sini]

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
- Use eMailTrackerPro (in Windows) 

## 💻 Command / Syntax Penting
```bash
# Tulis contoh command
```

## 🧪 Catatan Praktik Lab
- [Tulis pengalaman atau hasil lab]

---
[⬅ Kembali ke Daftar Modul](README.md)
