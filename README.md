<div align="center">

# 🔌 Alpha10 UsbView

**Alle USB-Geräte, die je an Computer hingen – auf einen Blick.**
**Every USB device that was ever connected to this PC – at a glance.**

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%20Framework-4.8-512BD4)
![Version](https://img.shields.io/badge/Version-1.3.1-C8F43C)
![Portable](https://img.shields.io/badge/Portable-Single%20EXE-555555)

![Alpha10 UsbView](docs/screenshot-dunkel.png)

**🇩🇪 [Deutsch](#-deutsch) · 🇬🇧 [English](#-english)**

</div>

## 🇩🇪 Deutsch

Alpha10 UsbView zeigt den kompletten USB-Verlauf von Windows: angeschlossene und längst getrennte Geräte, mit Seriennummer, Laufwerksbuchstabe und Zeitpunkten. Alte Einträge lassen sich gezielt aus der Windows-Geräteliste löschen.

### ✨ Funktionen

- 📋 **Kompletter Verlauf** – Sticks, Festplatten, Handys, Tastaturen, Mäuse, Kameras, Drucker, Audio, Netzwerk, Hubs
- 🕒 **Zeitpunkte** – erstmals verbunden, zuletzt verbunden, zuletzt getrennt
- 💾 **Speicher-Details** – Laufwerk, Kapazität, SSD/HDD, UASP/BOT, Volumes, Schreibschutz
- ⚡ **Live-Daten** – USB-Version, Geschwindigkeit, Stromaufnahme, Anschluss
- ⚠️ **Auffälligkeiten** – BadUSB-Muster, unechte/doppelte Seriennummern, Strom am Hub, Windows-Problemcodes
- 🛡️ **USB-Richtlinien** – zeigt aktive Sperren (z. B. Speicher gesperrt)
- 🗑️ **Aus Verlauf löschen** – einzeln oder mehrere, mit Rückfrage
- 🔧 **Trennen · Neu starten · Deaktivieren** – für angeschlossene Geräte
- 🔍 **Suche & Filter** – Name, Seriennummer, VID/PID, Typ, Status
- 📤 **Export** – CSV, HTML, JSON, XML, Text
- 🌓 **Hell & Dunkel** – Deutsch & Englisch

### Start

1. `Alpha10UsbView.exe` herunterladen – keine Installation nötig
2. Starten, Hinweise lesen, Häkchen setzen, **Programm starten**
3. Zum Löschen/Deaktivieren fragt Windows nach Administratorrechten

**Voraussetzungen:** Windows 10 oder 11 · .NET Framework 4.8 (ab Windows 10 1903 vorhanden)

### 🔒 Datenschutz

Alles bleibt auf dem PC: kein Internet, keine Datenübertragung. Gespeichert werden nur Einstellungen unter `%APPDATA%\Alpha10\UsbView`. Exportierte Listen enthalten Seriennummern – bewusst weitergeben.

### ⚖️ Haftungsausschluss

Nutzung auf eigene Verantwortung. Gelöschte Einträge lassen sich nicht wiederherstellen; Trennen und Deaktivieren greifen in laufende Geräte ein. Keine Gewähr für Vollständigkeit und Richtigkeit. Ausführlich: Readme.pdf.

---

## 🇬🇧 English

Alpha10 UsbView shows the complete Windows USB history: connected and long-disconnected devices, with serial number, drive letter and timestamps. Old entries can be removed from the Windows device list on purpose.

### ✨ Features

- 📋 **Complete history** – sticks, drives, phones, keyboards, mice, cameras, printers, audio, network, hubs
- 🕒 **Timestamps** – first connected, last connected, last removed
- 💾 **Storage details** – drive, capacity, SSD/HDD, UASP/BOT, volumes, write protection
- ⚡ **Live data** – USB version, speed, power draw, port
- ⚠️ **Alerts** – BadUSB patterns, fake/duplicate serial numbers, hub power, Windows problem codes
- 🛡️ **USB policies** – shows active restrictions (e.g. storage blocked)
- 🗑️ **Delete from history** – single or multiple, with confirmation
- 🔧 **Disconnect · Restart · Disable** – for connected devices
- 🔍 **Search & filters** – name, serial number, VID/PID, type, status
- 📤 **Export** – CSV, HTML, JSON, XML, text
- 🌓 **Light & dark** – German & English

### 🚀 Getting started

1. Download `Alpha10UsbView.exe` – no installation needed
2. Run it, read the notes, tick the box, **Start program**
3. Windows asks for administrator rights to delete/disable

**Requirements:** Windows 10 or 11 · .NET Framework 4.8 (included since Windows 10 1903)

### 🔒 Privacy

Everything stays on this PC: no internet, no data transfer. Only settings are stored under `%APPDATA%\Alpha10\UsbView`. Exported lists contain serial numbers – share them deliberately.

### ⚖️ Disclaimer

Use at your own risk. Deleted entries cannot be restored; disconnecting and disabling affect running devices. No warranty for completeness or correctness. Details: [Readme.pdf](Readme.pdf).

---

<div align="center">

☕ [Spende an Entwickler · Donate to the developer](https://ko-fi.com/alpha10)

Alpha10UsbView · © Alpha10.de · alle Rechte vorbehalten · All rights reserved

</div>
