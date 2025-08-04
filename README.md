# AdvancedOSINT

# 🛰️ AdvancedOSINT Pro v3.0

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Type-OSINT-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Version-3.0-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Python-green?style=for-the-badge">
</p>

### 🔐 కోడ్ రచయిత: Sunnam Sriram  
📅 రిలీజ్ తేదీ: ఆగస్ట్ 2025  
📦 టూల్ రకం: **Open Source Full Recon Tool**  
🌐 వేదికలు: **Termux | Kali Linux | Ubuntu | Android | Cloud VM**

---

## 🧠 ఈ టూల్ ఏమిటి?

**AdvancedOSINT Pro v3.0** అనేది ఒక సంపూర్ణ **OSINT (Open Source Intelligence)** టూల్, ఇది క్రింది రీకాన్ అవసరాల కోసం ఉపయోగించబడుతుంది:

- 🔍 యూజర్ నేమ్ ట్రాకింగ్ (Social Finder)
- 🌐 Domain/IP ట్రేసింగ్
- 🔎 Email Lookup
- 🔐 Phone Number Investigation
- 📷 Image Reverse Search
- 🕵️ Dark Web Username Check
- 📡 Live Location Intelligence

---

## 🚀 ఫీచర్లు:

| ఫీచర్ | వివరణ |
|--------|--------|
| 👤 Username Recon | 35+ సోషియల్ మీడియా ప్లాట్‌ఫామ్స్ లో యూజర్ నేమ్ చెక్ చేస్తుంది |
| 🌍 IP/Domain Tracker | Country, ISP, Region, Proxy/VPN డిటెక్షన్ |
| 📧 Email & Phone OSINT | Validate, breach check, spam flags |
| 🖼️ Image Search | Reverse Image Search via Google, Yandex |
| 🧅 TOR/Dark Web Scan | Onion URL lookup (TOR అవసరం) |
| 📜 Custom Reports | JSON, TXT, HTML ఫార్మాట్స్ లో Export చేయవచ్చు |

---

## 🔧 Installation (Termux లో):

```bash
pkg update && pkg upgrade
pkg install git python -y
git clone https://github.com/sunnamsriram1/AdvancedOSINT_Pro
cd AdvancedOSINT_Pro
pip install -r requirements.txt
python3 adv_osint.py
