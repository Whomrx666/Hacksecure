# Hacksecure
![hacksecure preview](hacksecure.jpg)

<p align="center">
  <strong>Cyberpunk Neon Edition – OSINT • Security • Stresser • Digital Forensics • Password Security</strong><br>
  <em>"Unlock the Truth — Intelligence meets Neon." – Mr.X</em>
</p>

## Introduction
Hacksecure is an all-in-one terminal-based toolkit that combines **OSINT**, **ethical hacking**, **stress testing**, **digital forensics**, and **password security** modules into a single powerful cyberpunk-themed CLI. With **10 OSINT modules**, **40 ethical hacking modules**, **6 stresser modules (L4/L7)**, **10 forensic image modules**, and **6 password security modules**, Hacksecure streamlines your reconnaissance, vulnerability assessment, and investigation workflows. Runs smoothly on **Termux (Android)**, Linux, Windows, macOS, and Kali Linux — **no root required** and **no API key needed** for OSINT and Forensic modules.

## Installation
```bash
$ pkg update -y && pkg upgrade -y
$ pkg install git python -y
$ git clone https://github.com/Whomrx666/Hacksecure.git
$ cd Hacksecure
$ python3 install.py
```

## Run manually
```
$ python3 hacksecure.py
```

> **Note:** OSINT and Forensic Image modules work 100% offline-capable without any API key. Some optional features may require additional tools (`whois`, `exiftool`, `tesseract`, `scapy`).

## Features
- **OSINT Suite** – 10 modules covering username, phone, email, social media, IP, domain, GitHub, Gravatar, IP reputation, and website tech detection.
- **40+ Ethical Hacking Modules** – Port scanning, SQLi, XSS, CMS detection, WordPress scanner, and more.
- **Stresser (L4 & L7)** – UDP/TCP/ICMP floods and HTTP GET/POST/Slowloris (educational use only).
- **Forensic Image Suite** – 10 modules including EXIF/GPS extraction, steganography check, ELA, OCR, and color palette analyzer.
- **Password Security Suite** – Strength analyzer, secure generator, common password checker, hash generator, policy validator, and wordlist analyzer.
- **Cyberpunk Neon UI** – Rich terminal interface with animations, panels, and colored output.
- **Cross-Platform** – Works on Termux, Linux, Windows, macOS, and Kali Linux.
- **No API Key Required** – OSINT and Forensic modules use free public resources.


## Modules Overview

### OSINT Suite (10 Modules)
| #  | Module | Description |
|----|--------|-------------|
| 01 | OSINT Username        | Search username across 100 online platforms |
| 02 | OSINT Phone Number    | Extract carrier, location, timezone, type |
| 03 | OSINT Email           | Validate email, MX, Gravatar, breach lookup |
| 04 | OSINT Social Media    | Search social media profiles by name/keyword |
| 05 | OSINT IP Address      | Geolocation, reverse DNS, ASN, ISP info |
| 06 | OSINT Domain          | DNS records, subdomain discovery, whois |
| 07 | OSINT GitHub User     | Public GitHub profile lookup |
| 08 | OSINT Gravatar        | Find Gravatar profile & avatar by email |
| 09 | OSINT IP Reputation   | Check blacklist, Tor exit node, threat intel |
| 10 | OSINT Website Tech    | Detect CMS, headers, SSL certificate |

### Hacksecure Hacking (40 Modules)
| #  | Module | Description |
|----|--------|-------------|
| 01 | Port Scanner              | Scan open ports on a target host |
| 02 | Subdomain Finder          | Discover subdomains of a domain |
| 03 | DNS Lookup                | Resolve DNS records |
| 04 | Whois Lookup              | Retrieve domain registration info |
| 05 | IP Geolocation            | Find geographic location of an IP |
| 06 | HTTP Header Analyzer      | Analyze HTTP response headers |
| 07 | Directory Brute Force     | Find hidden directories |
| 08 | SQL Injection Scanner     | Test for SQL injection |
| 09 | XSS Scanner               | Test for cross-site scripting |
| 10 | CMS Detector              | Identify CMS (WordPress, Joomla, etc.) |
| 11 | WordPress Scanner         | Scan WordPress sites |
| 12 | Banner Grabbing           | Grab service banners |
| 13 | SSL/TLS Analyzer          | Check SSL certificate |
| 14 | Reverse IP Lookup         | Find domains on same IP |
| 15 | Email Harvester           | Collect emails from a domain |
| 16 | Metadata Extractor        | Extract file metadata |
| 17 | Hash Identifier           | Identify hash type |
| 18 | Hash Cracker              | Crack hashes using wordlist |
| 19 | Password Generator        | Generate strong passwords |
| 20 | Wordlist Generator        | Create custom wordlists |
| 21 | Base64 Encoder/Decoder    | Encode or decode base64 |
| 22 | Hex Encoder/Decoder       | Convert text to hex |
| 23 | URL Encoder/Decoder       | Encode/decode URL strings |
| 24 | String Manipulation       | Various string operations |
| 25 | Network Sniffer           | Capture network packets |
| 26 | WiFi Scanner              | Scan nearby WiFi networks |
| 27 | Bluetooth Scanner         | Scan for Bluetooth devices |
| 28 | MAC Address Changer       | Spoof MAC address |
| 29 | ARP Spoof Detector        | Detect ARP spoofing attacks |
| 30 | Packet Crafting           | Create custom network packets |
| 31 | Firewall Tester           | Test firewall rules |
| 32 | Router Default Credentials| Check default router credentials |
| 33 | IoT Device Scanner        | Find insecure IoT devices |
| 34 | Web Crawler               | Crawl website and extract links |
| 35 | Vulnerability DB Lookup   | Search for known CVEs |
| 36 | Exploit Suggester         | Suggest exploits |
| 37 | Payload Generator (Web)   | Generate web payloads (XSS, SQLi) |
| 38 | Payload Encoder           | Encode payloads |
| 39 | Social Engineering Toolkit| Launch SE attacks (educational) |
| 40 | Forensic Toolkit          | Digital forensics tools |

### Stresser (6 Modules – L4 & L7)
| # | Module | Description |
|---|--------|-------------|
| 01 | UDP Flood         | Send high volume UDP packets |
| 02 | TCP SYN Flood     | Initiate many TCP connections |
| 03 | ICMP Flood        | Send ping flood |
| 04 | HTTP GET Flood    | Send many HTTP GET requests |
| 05 | HTTP POST Flood   | Send many HTTP POST requests |
| 06 | Slowloris Attack  | Hold many connections open |

### Forensic Image Suite (10 Modules)
| #  | Module | Description |
|----|--------|-------------|
| 01 | Image Metadata         | EXIF, IPTC, XMP, GPS, camera info |
| 02 | Reverse Image Search   | Google, Yandex, TinEye, Bing, SauceNAO |
| 03 | Image Hashes           | MD5, SHA1, SHA256, SHA512, pHash |
| 04 | GPS Extractor          | Extract GPS coordinates + Google Maps link |
| 05 | Steganography Check    | LSB detection, appended data, trailing bytes |
| 06 | Error Level Analysis   | ELA image forensics for tampering |
| 07 | Color Palette Analyzer | Extract dominant colors & palette |
| 08 | Image Similarity       | Compare two images (histogram + SSIM) |
| 09 | OCR Text Extraction    | Extract text via Tesseract |
| 10 | Compression Analyzer   | Quantization tables & artifacts |

### Password Security Suite (6 Modules)
| # | Module | Description |
|---|--------|-------------|
| 01 | Password Strength Analyzer | Entropy, crack time, and rating |
| 02 | Secure Password Generator  | Generate strong random passwords |
| 03 | Common Password Checker    | Check against 200+ common passwords |
| 04 | Hash Generator             | MD5, SHA1, SHA256, SHA512, BLAKE2, SHA3 |
| 05 | Password Policy Validator  | Validate against security rules |
| 06 | Wordlist Analyzer          | Statistics, duplicates, distribution |

## Instructions
1. **Install** the tool using the commands above.
2. **Run** `python3 hacksecure.py` after installation.
3. **Select a menu** – choose from OSINT, Hacking, Stresser, Forensic Image, Password Security, About, Help, or Exit.
4. **Choose a module** – enter the module number to launch.
5. **Follow on-screen prompts** – provide required input (URL, IP, file path, etc.).
6. **View results** – results are displayed in the terminal; some modules save output files (ELA image, palette image, etc.).

## Observation
This tool is intended for **educational and ethical purposes only**. Unauthorized scanning, stress testing, or investigation of systems you do not own or have explicit written permission to test is **illegal**. The author assumes no responsibility for misuse or damage caused by this tool.

### Original Author
<a href="https://github.com/Whomrx666"><img src="https://img.shields.io/badge/Original-Author-brightgreen.svg" alt=""/></a>

### <<< If you copy, then give me the credits >>>

## CONNECT WITH ME :

[![Website](https://img.shields.io/badge/WEBSITE-VISIT-red?style=for-the-badge&logo=blogger)](https://whomrx.pages.dev)
[![Blog](https://img.shields.io/badge/BLOG-VISIT-red?style=for-the-badge&logo=blogger)](https://whomrxhackers.blogspot.com)
[![Twitter](https://img.shields.io/badge/TWITTER-FOLLOW-red?style=for-the-badge&logo=x)](https://twitter.com/whomrx666)
[![WhatsApp](https://img.shields.io/badge/WHATSAPP-CHATME-red?style=for-the-badge&logo=whatsapp)](https://wa.me/6285926601133?text=Halo%2C%20Mr.X)
[![Facebook](https://img.shields.io/badge/FACEBOOK-LIKE-red?style=for-the-badge&logo=facebook)](https://www.facebook.com/whomrx.666)
[![Telegram](https://img.shields.io/badge/TELEGRAM-CONNECT-red?style=for-the-badge&logo=telegram)](https://t.me/Whomr_X)
[![Gmail](https://img.shields.io/badge/GMAIL-CONTACT-red?style=for-the-badge&logo=gmail)](mailto:whomrx666@gmail.com)
[![TikTok](https://img.shields.io/badge/TIKTOK-FOLLOW-red?style=for-the-badge&logo=tiktok)](https://www.tiktok.com/@whomr.x)

**If you want to donate, click on the button**
<a href="https://saweria.co/whomrx"><img title="Donate" src="https://img.shields.io/badge/Donate-Hacksecure-yellow?style=for-the-badge&logo=github"></a>

---

<p align="left">
  <img src="https://img.shields.io/badge/Thank_you_for_visiting!-808080?style=for-the-badge&logo=github" alt="Thanks badge"/>
</p>