# 📘 02 Footprinting and Reconnaissance

## 🎯 Konsep Utama
- [Tulis ringkasan konsep di sini]

## 🛠️ Tools yang Digunakan
*1. Find Domain's, Subdomains & Host.
  - Netcraft (https://www.netcraft.com)
  - DNSdumpster (https://dnsdumpster.com)
2. Gather Personal Information from various social networking.
  - Sherlock (Terminal) : <br />
    | sudo su <br />
    | sherlock *"Target Name"*
  - [Social Searcher](https://www.social-searcher.com) <br />
    Gather target company from Social networking.
3. Lookup Hostname, IP Address, or Domains.
  - Whois (This protocol listens to requests on port 43 (TCP))<br />
    | [Whois](http://whois.domaintools.com)<br />
    or <br />
    | SmartWhois ([Tamos](https://www.tamos.com))<br />
    | Batch IP Coverter ([Sabsoft](http://www.sabsoft.com))
4. Perform DNS Footprinting.
- NS Lookup<br />
    | nslookuop <br />
    | set type=a / type=cname
- [NSlookup](http://www.kloth.net/services/nslookup.php) Online
5. Perform Network Tracerouting in Windows and Linux Machines
- Tracert<br />
    | tracert *target_domain*<br />
    Command View<br />
    | tracert /?<br />
    *Example*<br />
    | tracert -h 5 *target_domain*
- Traceroute ( to view the hops that the packets made before reaching the destination) <br />
    | traceroute *target_domain*
- Other Tools<br />
    |  [PingPlotter](https://www.pingplotter.com/) 
  
  
  

## 💻 Command / Syntax Penting
```bash
# Tulis contoh command
```

## 🧪 Catatan Praktik Lab
- [Tulis pengalaman atau hasil lab]

---
[⬅ Kembali ke Daftar Modul](README.md)
