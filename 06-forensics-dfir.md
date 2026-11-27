# 06 — Forensics / DFIR

[⬅ README](README.md)

> Raqamli forensika (Digital Forensics) va Incident Response platforma hamda vositalari.

## 🏢 Kommersiya / platformalar

| Vosita | Havola |
|--------|--------|
| Belkasoft | https://belkasoft.com |
| The Sleuth Kit (open-source) | http://sleuthkit.org |
| AccessData (FTK) | https://accessdata.com |
| Magnet Forensics | https://www.magnetforensics.com |
| Cellebrite | https://www.cellebrite.com |
| OSForensics | https://www.osforensics.com |
| ProDiscover Forensics | https://www.prodiscover.com/prodiscover-forensics.php |
| Elcomsoft — bepul forensic toollar | https://www.elcomsoft.com/free_forensic_tools.html |

## 🧠 Xotira / tahlil

| Vosita | Havola |
|--------|--------|
| Volatility Foundation | https://www.volatilityfoundation.org |
| Velociraptor (endpoint DFIR) | https://github.com/Velocidex/velociraptor · [docs](https://docs.velociraptor.app/) · [releases](https://github.com/Velocidex/velociraptor/releases/) |
| CyLR (tez artefakt yig'ish) | https://github.com/orlikoski/CyLR/releases |
| VISION-ProcMon | https://github.com/forensicxlab/VISION-ProcMon/releases |
| evtx-attack-samples (EVTX namunalar) | https://github.com/sbousseaden/evtx-attack-samples |

## 💿 Forensic Linux distributivlari / live

| Distro | Havola |
|--------|--------|
| CAINE | https://www.caine-live.net |
| CSI Linux | https://csilinux.com/#downloads |
| Network Security Toolkit (NST) | https://www.networksecuritytoolkit.org/nst/index.html |
| Hiren's Boot CD PE | https://www.hirensbootcd.org/download/ |

## 🧰 Yordamchi utilitalar

| Vosita | Havola |
|--------|--------|
| NirSoft Launcher | https://launcher.nirsoft.net/ |
| NirSoft Vault Password View | https://www.nirsoft.net/utils/vault_password_view.html |
| forensic7z (7-Zip plugin) | https://www.tc4shell.com/en/7zip/forensic7z/ |
| Loki (IOC scanner) | https://github.com/Neo23x0/Loki |
| Nextron scanner'lar taqqoslash | https://www.nextron-systems.com/compare-our-scanners/ |

## 💾 DFIR toolkit ("." chati — amaliy video kurs + dasturlar)

Bu chatda to'liq DFIR amaliy kursi (`DFIR_3.mkv`, `DFIR-Finish.mkv`, `Victim_1.mkv`) va vositalar bor:

| Vosita | Fayl | Vazifa |
|--------|------|--------|
| FTK Imager | `Exterro_FTK_Imager_4.7.3.exe`, `AccessData_FTK_Imager_4.7.1.exe` | Disk imaging |
| Bulk Extractor | `bulk_extractor_gui.tar.gz` | Ma'lumot ajratish |
| DMDE | `dmde-4-4-0-828-win64-gui.zip` | Disk/fayl tiklash |
| DataDump | `DataDump-x86-EN-*.zip` | Data dump |
| DCode | `DCode-x86-EN-5.6.zip` | Timestamp dekodlash |
| USBDeview | `usbdeview-x64.zip` | USB tarix |
| CrowdInspect | `CrowdInspect.zip` | Process/network tekshirish |
| Process Monitor | `ProcessMonitor.zip` | Process monitoring |
| Process Hacker | `processhacker-2.39-setup.exe` | Process boshqaruv |
| VISION-ProcMon | `VISION-ProcMon_1.5.0.exe` | Forensic procmon |
| Loki (IOC) | `loki_0.51.0.zip` | IOC scanner |
| HitmanPro.Alert | `hmpalert3.exe` | Exploit himoya |
| CS ShellShock/Heartbleed Scanner | `CSShellShockScanner.zip`, `CSHeartbleedScanner.zip` | Zaiflik skaner |
| PE-bear / Detect It Easy | `PE-bear...zip`, `die_win64...zip` | Binary tahlil |

## 📄 O'rganish rejasi (Cyberkent flags kanalidan)

Sizning **Cyberkent flags** kanalingizdagi "Tarmoq trafikini tahlil qilish" darsidan:
1. **1-hafta:** Wireshark o'rnatib, 5 daqiqa trafik yozib, filtrlarni sinash (THM "Wireshark: The Basics")
2. **2-hafta:** Malware-Traffic-Analysis.net dan haqiqiy PCAP tahlil qilish
3. **3-hafta:** Zeek (Ubuntu VM) — conn.log va dns.log tahlili
4. **4-hafta:** Suricata qoidalari + Security Onion
