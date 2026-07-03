<!-- # Briefly -->

This repository serves as a practical showcase of core networking concepts, ranging from low-level socket programming to traffic analysis and dynamic routing emulation. Each section represents a standalone module focused on implementing, configuring, and analyzing modern network protocols.

---
💡 *Note: This repository is intended for educational and professional demonstration purposes only.*

---

# Napredne mreže računala - Laboratorijske vježbe

Ovaj repozitorij sadrži laboratorijske vježbe iz kolegija **Napredne mreže računala**. Cilj vježbi je praktična primjena koncepata mrežnog programiranja, analize prometa, usmjeravanja i bežičnih mreža.

---

## 📌 Pregled vježbi

-  **Lab 1:** UDP Socket programiranje
-  **Lab 2:** TCP Socket programiranje
-  **Lab 3:** Wireshark: TLS i DTLS
-  **Lab 4:** Strujanje multimedije *[(Multimedia Streaming)]*
-  **Lab 5:** RIP i osnove OSPF-a (IMUNES)
-  **Lab 6:** Usmjeravanje u većim mrežama
-  **Lab 7:** IEEE 802.11 *[(Wireshark analiza)]*

---

## 📂 Sadržaj vježbi

| Vježba | Naziv | Tehnologije / Alati | Link na kod/izvještaj |
|--------|-------|---------------------|-----------------------|
| **Lab 1** | UDP Socket | Python / C / C++ | [Pogledaj vježbu](./lab1-udp-socket) |
| **Lab 2** | TCP Socket | Python / C / C++ | [Pogledaj vježbu](./lab2-tcp-socket) |
| **Lab 3** | TLS & DTLS | Wireshark | [Izvještaj_3](https://github.com/PetriciaLee/advanced-computer-networks/blob/main/Izvje%C5%A1taj_3.pdf) |
| **Lab 4** | Strujanje multimedije | RTP / RTSP / VLC | [Izvještaj_4](https://github.com/PetriciaLee/advanced-computer-networks/blob/main/Izvje%C5%A1taj_4.pdf) |
| **Lab 5** | RIP & OSPF osnove | IMUNES / Cisco | [Pogledaj vježbu](./lab5-rip-ospf-imunes) |
| **Lab 6** | Usmjeravanje u većim mrežama | OSPF / BGP | [Pogledaj vježbu](./lab6-large-scale-routing) |
| **Lab 7** | IEEE 802.11 analiza | Wireshark / WLAN | [Pogledaj vježbu](./lab7-ieee-802.11-wireshark) |

---

## 📝 Detalji o vježbama (Popunjavati tijekom semestra)

### 🔹 Lab 1: UDP Socket Programiranje
* **Kratki opis:**
   * Izrada klijent-poslužitelj aplikacije koja komunicira preko UDP protokola bez uspostave veze.
* **Stečeno znanje:**
    * Razumijevanje rada UDP protokola na transportnom sloju.
    * Rukovanje nestrukturiranim podacima i "gubitkom" paketa u kodu.
* **Kako pokrenuti:** *[Napiši naredbu, npr. `python3 udp_server.py`]*

### 🔹 Lab 2: TCP Socket Programiranje
* **Kratki opis:**
   * Implementacija pouzdane TCP veze između klijenta i poslužitelja uz upravljanje višenitnošću (multi-threading)
    * Razlika između TCP-a i UDP-a u praksi (three-way handshake).
    * Rad s "stream" podacima.
* **Kako pokrenuti:** *[Napiši kratke upute]*

### 🔹 Lab 3: Wireshark - TLS i DTLS
* **Kratki opis:**
   * Analiza sigurnih protokola na transportnom sloju i usporedba TLS (preko TCP-a) i DTLS (preko UDP-a) kroz Wireshark pakete.
    * Analiza enkripcije i procesa razmjene ključeva (handshake).
    * Filtriranje prometa u Wiresharku (`tls` ili `dtls`).

### 🔹 Lab 4: Strujanje multimedije
* **Kratki opis:**
   * Konfiguracija i analiza prijenosa video/audio sadržaja u stvarnom vremenu.
    * Upoznavanje s RTP i RTSP protokolima.
    * Utjecaj kašnjenja (jitter) i gubitka paketa na kvalitetu strujanja.

### 🔹 Lab 5: RIP i osnove OSPF-a uz korištenje IMUNES-a
* **Kratki opis:**
   * Emulacija mrežne topologije u IMUNES-u i konfiguriranje protokola dinamičkog usmjeravanja RIP i OSPF.
* **Stečeno znanje:**
    * Konfiguracija usmjerivača (routing tablice).
    * Razlika između Distance-Vector (RIP) i Link-State (OSPF) protokola u praksi.

### 🔹 Lab 6: Usmjeravanje u većim mrežama
* **Kratki opis:**
   * Skaliranje mreže, hijerarhijski OSPF ili uvod u BGP za povezivanje autonomnih sustava.
* **Stečeno znanje:**
    * Koncepti dijeljenja mreže na područja (Areas).
    * Rješavanje problema s petljama u usmjeravanju (Routing loops).

### 🔹 Lab 7: IEEE 802.11 uz korištenje Wiresharka
* **Kratki opis:**
   * Hvatanje i analiza okvira (frames) u bežičnim lokalnim mrežama (WLAN).
* **Stečeno znanje:**
    * Razlikovanje Management, Control i Data okvira u 802.11 standardu.
    * Analiza procesa autentifikacije na Wi-Fi mrežu.

---

<!-- ## 🛠️ Korišteni alati
* **Wireshark** - za analizu mrežnih protokola
* **IMUNES** - mrežni emulator
* **Python / C++** - za socket programiranje
-->
---

### 🛠️ Tehnologije i Mrežni Protokoli

<table border="0">
  <tr>
    <td><b>Jezici:</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-B3C5FF?style=flat-square&logo=python&logoColor=2B2B2B" alt="Python">
      <img src="https://img.shields.io/badge/C++-B8E2C8?style=flat-square&logo=cplusplus&logoColor=2B2B2B" alt="C++">
    </td>
  </tr>
  <tr>
    <td><b>Emulacija i Analiza:</b></td>
    <td>
      <img src="https://img.shields.io/badge/IMUNES%20%2F%20Cisco-D6C7FF?style=flat-square&logo=cisco&logoColor=2B2B2B" alt="IMUNES Cisco">
      <img src="https://img.shields.io/badge/Wireshark-A3E5E5?style=flat-square&logo=wireshark&logoColor=2B2B2B" alt="Wireshark">
    </td>
  </tr>
  <tr>
    <td><b>Streaming i Protokoli:</b></td>
    <td>
      <img src="https://img.shields.io/badge/RTP%20%2F%20RTSP%20%2F%20VLC-FFD1BA?style=flat-square&logo=vlc&logoColor=2B2B2B" alt="VLC RTP RTSP">
      <img src="https://img.shields.io/badge/OSPF%20%2F%20BGP-FFBFC3?style=flat-square&logo=google-cloud&logoColor=2B2B2B" alt="Routing">
      <img src="https://img.shields.io/badge/WLAN-FFEAA7?style=flat-square&logo=wi-fi&logoColor=2B2B2B" alt="WLAN">
    </td>
  </tr>
</table>

---
👤 **Autor:** *[Petra Jakopović / PetriciaLee]* 🎓 **Fakultet:** *[FOI - Faculty of Organization and Informatics]*


