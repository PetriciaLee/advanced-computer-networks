# Hands-On Networking Portfolio

This repository serves as a practical showcase of core networking concepts, ranging from low-level socket programming to traffic analysis and dynamic routing emulation. Each section represents a standalone module focused on implementing, configuring, and analyzing modern network protocols.

---

## 📌 Progress Tracker

- [ ] **Module 1:** UDP Socket Programming
- [ ] **Module 2:** TCP Multithreaded Socket Programming
- [ ] **Module 3:** Transport Layer Security Analysis (TLS & DTLS)
- [ ] **Module 4:** Real-Time Multimedia Streaming
- [ ] **Module 5:** Interior Gateway Routing Emulation (RIP & OSPF)
- [ ] **Module 6:** Advanced Large-Scale Network Routing
- [ ] **Module 7:** Wireless LAN Analysis (IEEE 802.11)

---

## 📂 Repository Structure

| Module | Topic | Core Tech / Tools | Project Link |
|--------|-------|-------------------|--------------|
| **01** | UDP Socket Application | Python / C++ | [Go to Project](./udp-socket-programming) |
| **02** | TCP Multithreaded Server | Python / C++ | [Go to Project](./tcp-multithreaded-server) |
| **03** | TLS & DTLS Traffic Analysis | Wireshark | [Go to Project](./tls-dtls-traffic-analysis) |
| **04** | Multimedia Streaming Engine | RTP / RTSP / VLC | [Go to Project](./multimedia-streaming-protocols) |
| **05** | Emulated RIP & OSPF Systems | IMUNES Topology | [Go to Project](./dynamic-routing-emulation) |
| **06** | Hierarchical Routing & Scaling | OSPF / BGP | [Go to Project](./large-scale-network-routing) |
| **07** | 802.11 WLAN Frame Analysis | Wireshark | [Go to Project](./wireless-ieee80211-analysis) |

---

## 📝 Module Deep Dives (Work in Progress)

### 🔹 Module 01: UDP Socket Application
* **Description:** *[Write 2-3 sentences about the project, e.g., Implementing a lightweight, connectionless client-server application to handle rapid data transfer.]*
* **Key Takeaways & Skills:**
    * Deep understanding of connectionless communication at the Transport Layer.
    * Handling packet loss and unstructured data programmatically.
* **How to Run:** *[Provide short execution commands, e.g., `python3 udp_server.py`]*

### 🔹 Module 02: TCP Multithreaded Server
* **Description:** *[e.g., Developing a reliable, stream-oriented TCP server capable of handling multiple concurrent clients using multithreading.]*
* **Key Takeaways & Skills:**
    * Mastery of the TCP three-way handshake and connection states.
    * Implementing thread-safe stream data parsing.
* **How to Run:** *[Provide short execution commands]*

### 🔹 Module 03: Transport Layer Security Analysis (TLS & DTLS)
* **Description:** *[e.g., Investigating cryptographic handshakes and inspecting secure packet exchanges over both reliable (TCP) and unreliable (UDP) transport protocols.]*
* **Key Takeaways & Skills:**
    * Advanced traffic filtering in Wireshark using customized display filters (`tls` / `dtls`).
    * Analyzing cipher suite negotiations and key exchange mechanisms.

### 🔹 Module 04: Real-Time Multimedia Streaming
* **Description:** *[e.g., Configuring and analyzing live media distribution streams to evaluate quality-of-service metrics over real-time protocols.]*
* **Key Takeaways & Skills:**
    * Practical experience with real-time transport protocols (RTP, RTSP).
    * Assessing the impact of jitter, latency, and packet loss on stream rendering.

### 🔹 Module 05: Emulated RIP & OSPF Systems
* **Description:** *[e.g., Designing virtual network topologies within an emulated environment to observe and compare dynamic routing convergence behavior.]*
* **Key Takeaways & Skills:**
    * Configuring routing tables and interfaces within virtualized router nodes.
    * Comparative analysis of Distance-Vector (RIP) vs. Link-State (OSPF) routing convergence times.

### 🔹 Module 06: Advanced Large-Scale Network Routing
* **Description:** *[e.g., Scaling emulated networks into complex, hierarchical structures to simulate enterprise or service provider environments.]*
* **Key Takeaways & Skills:**
    * Implementing Multi-Area OSPF to reduce routing overhead and optimize link states.
    * Understanding routing loop prevention and scaling constraints.

### 🔹 Module 07: Wireless LAN Analysis (IEEE 802.11)
* **Description:** *[e.g., Capturing and decoding over-the-air wireless frames to understand physical layer interactions and association processes in WLANs.]*
* **Key Takeaways & Skills:**
    * Categorizing Management, Control, and Data frames within 802.11 capture files.
    * Analyzing the 4-way handshake during WPA/WPA2 authentication.

---

## 🛠️ Toolstack & Environment
* **Network Analysis:** Wireshark
* **Network Emulation:** IMUNES / Virtual Environments
* **Programming Languages:** Python / C++ (Socket API)

---
💡 *Note: This repository is intended for educational and professional demonstration purposes only.*

---

# Napredne mreže računala - Laboratorijske vježbe

Ovaj repozitorij sadrži laboratorijske vježbe iz kolegija **Napredne mreže računala**. Cilj vježbi je praktična primjena koncepata mrežnog programiranja, analize prometa, usmjeravanja i bežičnih mreža.

---

## 📌 Pregled napretka

Ovdje možete pratiti status dovršenosti vježbi:

- [ ] **Lab 1:** UDP Socket programiranje
- [ ] **Lab 2:** TCP Socket programiranje
- [ ] **Lab 3:** Wireshark: TLS i DTLS
- [ ] **Lab 4:** Strujanje multimedije (Multimedia Streaming)
- [ ] **Lab 5:** RIP i osnove OSPF-a (IMUNES)
- [ ] **Lab 6:** Usmjeravanje u većim mrežama
- [ ] **Lab 7:** IEEE 802.11 (Wireshark analiza)

---

## 📂 Sadržaj vježbi

| Vježba | Naziv | Tehnologije / Alati | Link na kod/izvještaj |
|--------|-------|---------------------|-----------------------|
| **Lab 1** | UDP Socket | Python / C / C++ | [Pogledaj vježbu](./lab1-udp-socket) |
| **Lab 2** | TCP Socket | Python / C / C++ | [Pogledaj vježbu](./lab2-tcp-socket) |
| **Lab 3** | TLS & DTLS | Wireshark | [Pogledaj vježbu](./lab3-tls-dtls-wireshark) |
| **Lab 4** | Strujanje multimedije | RTP / RTSP / VLC | [Pogledaj vježbu](./lab4-multimedia-streaming) |
| **Lab 5** | RIP & OSPF osnove | IMUNES / Cisco | [Pogledaj vježbu](./lab5-rip-ospf-imunes) |
| **Lab 6** | Usmjeravanje u većim mrežama | OSPF / BGP | [Pogledaj vježbu](./lab6-large-scale-routing) |
| **Lab 7** | IEEE 802.11 analiza | Wireshark / WLAN | [Pogledaj vježbu](./lab7-ieee-802.11-wireshark) |

---

## 📝 Detalji o vježbama (Popunjavati tijekom semestra)

### 🔹 Lab 1: UDP Socket Programiranje
* **Kratki opis:** *[Ovdje napiši 2-3 rečenice o tome što je bio zadatak, npr. Izrada klijent-poslužitelj aplikacije koja komunicira preko UDP protokola bez uspostave veze.]*
* **Stečeno znanje:**
    * Razumijevanje rada UDP protokola na transportnom sloju.
    * Rukovanje nestrukturiranim podacima i "gubitkom" paketa u kodu.
* **Kako pokrenuti:** *[Napiši naredbu, npr. `python3 udp_server.py`]*

### 🔹 Lab 2: TCP Socket Programiranje
* **Kratki opis:** *[Npr. Implementacija pouzdane TCP veze između klijenta i poslužitelja uz upravljanje višenitnošću (multi-threading).]*
* **Stečeno znanje:**
    * Razlika između TCP-a i UDP-a u praksi (three-way handshake).
    * Rad s "stream" podacima.
* **Kako pokrenuti:** *[Napiši kratke upute]*

### 🔹 Lab 3: Wireshark - TLS i DTLS
* **Kratki opis:** *[Npr. Analiza sigurnih protokola na transportnom sloju i usporedba TLS (preko TCP-a) i DTLS (preko UDP-a) kroz Wireshark pakete.]*
* **Stečeno znanje:**
    * Analiza enkripcije i procesa razmjene ključeva (handshake).
    * Filtriranje prometa u Wiresharku (`tls` ili `dtls`).

### 🔹 Lab 4: Strujanje multimedije
* **Kratki opis:** *[Npr. Konfiguracija i analiza prijenosa video/audio sadržaja u stvarnom vremenu.]*
* **Stečeno znanje:**
    * Upoznavanje s RTP i RTSP protokolima.
    * Utjecaj kašnjenja (jitter) i gubitka paketa na kvalitetu strujanja.

### 🔹 Lab 5: RIP i osnove OSPF-a uz korištenje IMUNES-a
* **Kratki opis:** *[Npr. Emulacija mrežne topologije u IMUNES-u i konfiguriranje protokola dinamičkog usmjeravanja RIP i OSPF.]*
* **Stečeno znanje:**
    * Konfiguracija usmjerivača (routing tablice).
    * Razlika između Distance-Vector (RIP) i Link-State (OSPF) protokola u praksi.

### 🔹 Lab 6: Usmjeravanje u većim mrežama
* **Kratki opis:** *[Npr. Skaliranje mreže, hijerarhijski OSPF ili uvod u BGP za povezivanje autonomnih sustava.]*
* **Stečeno znanje:**
    * Koncepti dijeljenja mreže na područja (Areas).
    * Rješavanje problema s petljama u usmjeravanju (Routing loops).

### 🔹 Lab 7: IEEE 802.11 uz korištenje Wiresharka
* **Kratki opis:** *[Npr. Hvatanje i analiza okvira (frames) u bežičnim lokalnim mrežama (WLAN).]*
* **Stečeno znanje:**
    * Razlikovanje Management, Control i Data okvira u 802.11 standardu.
    * Analiza procesa autentifikacije na Wi-Fi mrežu.

---

## 🛠️ Korišteni alati
* **Wireshark** - za analizu mrežnih protokola
* **IMUNES** - mrežni emulator
* **Python / C++** - za socket programiranje

---
👤 **Autor:** *[Petra Jakopović / PetriciaLee]* 🎓 **Fakultet:** *[FOI (Faculty of Organization and Informatics]*


