# Maagic7 – Industrial Step 7 Programming Library for Simatic S7-300/400

A field-proven, high-performance PLC programming library developed since 2003 and actively deployed across large-scale industrial projects. Highly optimized for Simatic S7-300/400, VIPA, and Yaskawa hardware environments running Classic Step 7 or TIA Portal.

Eine praxiserprobte, hochperformante SPS-Programmierbibliothek, die seit 2003 kontinuierlich weiterentwickelt und in industriellen Großprojekten eingesetzt wird. Optimiert für Simatic S7-300/400, VIPA und Yaskawa Steuerungen unter Classic Step 7 oder im TIA Portal.

---

## 🏭 Proven Industrial Track Record / Einsatzerprobte Industriebereiche

This library is not theoretical code—it is the structural backbone running inside heavily automated plant environments for over two decades:
Diese Bibliothek ist kein theoretischer Code – sie bildet das funktionale Rückgrat realer Industrieanlagen seit über zwei Jahrzehnten:

* **Biogas Power Plants** (Biogasanlagen & BHKWs)
* **Biological Waste Treatment Facilities** (Biologische Abfallbehandlungsanlagen)
* **Glass Production Machinery** (Glasproduktionsmaschinen)
* **Plant Control Systems for the Food Industry** (Prozessleittechnik in der Lebensmittelindustrie)
* **Heavy Hydraulic & Oil Cleaning Systems** (Hydraulik- und Ölreinigungsanlagen)

---

## 🚀 Key Functional Highlights / Technologische Highlights

The library provides modular, highly efficient SCL/AWL blocks engineered to solve complex automation tracking, calculation, and scheduling routines without overhead:
Die Bibliothek liefert modulare, hocheffiziente SCL/AWL-Bausteine für komplexe Automatisierungs-, Berechnungs- und Steuerungsaufgaben:

### 📊 Advanced Data Archiving & Statistics / Datenarchivierung & Statistik
* **`m7_YearArchives.SCL`:** Functions to build automated full Year Archives—perfect for tracking electricity meters, heat meters, or overall process consumption.
  *(Automatisierte Jahresarchive zur lückenlosen Erfassung von Strom-, Wärmezählern oder Produktionsdaten).*
* **`m7_StatisticCounter_DINT.SCL`:** Statistical tracking engines delivering calculated summation values for rolling periods: actual/last **[Hour, Day, Week, Month, Year]**.
  *(Statistikzähler für gleitende Zeiträume: aktuelle/letzte Stunde, Tag, Woche, Monat und Jahr).*

### ⏰ Deterministic Time & Calendar Operations / Kalender- & Zeitfunktionen
* **`m7_DateInfo.SCL`:** Computes extended chronological parameters from a given Date stamp, including native `Week_ISO` (European standard), `Week_NA` (North American standard), and automated `LeapYear` detection.
  *(Erweiterte Datums- und Kalenderinfos wie ISO-Woche, US-Woche und Schaltjahr-Erkennung).*
### 🎛️ Process Controls & Matrix Multiplexing / Prozessleittechnik & Multiplexer
* **`m7_MUX_4x.SCL`:** Signal Multiplexer engine for streamlined sensor routing.
  *(Signal-Multiplexer zur effizienten Sensorwert-Kanalisierung).*
* **`m7_Mapping_4x.SCL` / `m7_Mapping_8x.SCL`:** Advanced mapping tables engineered to generate precise **"criss-cross switches" (Kreuz- und Querschalter)**. Highly recommended for wear-level optimization in **Multi-Pump-Controls (Pumpenfolgesteuerungen)** or balancing thermodynamic loads in **Heater-Controls**.
  *(Erweiterte Mapping-Tabellen für Kreuz- und Querschaltungen zur Laufzeitoptimierung von Mehrpumpen- oder Heizungssteuerungen).*

---

## ⚠️ Safety Disclaimer / Sicherheitshinweis

### 🇬🇧 English
This library contains professional open-source industrial software provided "as is". Machine control applications present inherent operational risks. You are fully responsible for testing and verifying the code under simulated environments. Do not deploy these blocks in live plant environments unless you fully understand their internal mechanics and have rigorously verified their functionality!

### 🇩🇪 Deutsch
Diese Bibliothek enthält professionelle Open-Source-Industriesoftware und wird ohne Mängelgewähr bereitgestellt. Die Steuerung von Maschinen und Industrieanlagen birgt betriebliche Risiken. Sie tragen die volle Verantwortung für das Testen und Verifizieren des Codes in Simulationsumgebungen. Setzen Sie diese Bausteine erst in realen Anlagen ein, wenn Sie deren interne Funktionsweise vollständig verstanden und intensiv geprüft haben!

---

## 🛠️ Integration and Hardware Compatibility

### 🇬🇧 English
* **Supported Frameworks:** Siemens Simatic Step 7 (Classic V5.x) and TIA Portal (all versions).
* **Hardware Platforms:** S7-300, S7-400, VIPA 300S/SL, Yaskawa SLIO, and compatible WinAC software controllers.

### 🇩🇪 Deutsch
* **Unterstützte Software:** Siemens Simatic Step 7 (Classic V5.x) und TIA Portal (alle Versionen).
* **Hardware-Plattformen:** S7-300, S7-400, VIPA 300S/SL, Yaskawa SLIO sowie kompatible WinAC Software-SPS-Systeme.

---

## 📄 License / Lizenz

Licensed under the **MIT License**. Celebrate the 20+ years anniversary of this industrial library by utilizing it in your next automation project!

Veröffentlicht unter der **MIT-Lizenz**. Feiere das über 20-jährige Bestehen dieser Industrie-Bibliothek und nutze sie für dein nächstes Automatisierungsprojekt!
