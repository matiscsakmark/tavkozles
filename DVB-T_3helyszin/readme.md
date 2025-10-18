# Antennák mérési jegyzőkönyve, 3 különböző helyszínen az iskolában
### Készítette: Matiscsák Márk



| Vételi helyszín | Antenna | Szint (dBuV) | Moduláció / FEC | Noise margin | MER  | Fotó |
|------------|-------:|--------------:|-----------------:|------:|-----:|---------:|
| Tanári parkoló udvar      | Iskra P20 LOGPER  | 60.1 dBuV    | QPSK, 1/32      | 24.5dB  | 28.3dB | ![its_snapshot_0007.bmp](https://github.com/user-attachments/files/22968002/its_snapshot_0007.bmp)|
| Tanári parkoló udvar      | Iskra P-58 L700 UNI H/V SMA  | 62.5 dBuV    | QPSK, 1/32      | 29.5dB  | 30.3dB | ![its_snapshot_0008.bmp](https://github.com/user-attachments/files/22968022/its_snapshot_0008.bmp)|
| Tanári parkoló udvar      | Smart HD 550  | 54.9 dBuV    | QPSK, 1/32      | 27.8  | 31.6dB | ![its_snapshot_0009.bmp](https://github.com/user-attachments/files/22968040/its_snapshot_0009.bmp)|
| V3 labor        | Iskra P20 LOGPER | 46.4 dBuV    | QPSK, 1/32      | 25.0  | 28.8dB |  ![its_snapshot_0013.bmp](https://github.com/user-attachments/files/22968049/its_snapshot_0013.bmp)|
| V3 labor        | Iskra P-58 L700 UNI H/V SMA  | 50.1 dBuV    | QPSK, 1/32      | 33.1  | 36.9dB | ![its_snapshot_0012.bmp](https://github.com/user-attachments/files/22968057/its_snapshot_0012.bmp)|
| V3 labor        | Smart HD 550  | 44.3 dBuV    | QPSK, 1/32      | 15.9  | 19.6dB | ![its_snapshot_0011.bmp](https://github.com/user-attachments/files/22968062/its_snapshot_0011.bmp)|
| Iskola terasz     | Iskra P20 LOGPER | 74.9 dBuV    | QPSK, 1/32      | 31.6  | 35.3dB | ![its_snapshot_0001.bmp](https://github.com/user-attachments/files/22968072/its_snapshot_0001.bmp)|
| Iskola terasz     | Iskra P-58 L700 UNI H/V SMA  | 77.0 dBuV    | QPSK, 1/32      | 26.7dB  | 30.4dB | ![its_snapshot_0002.bmp](https://github.com/user-attachments/files/22968087/its_snapshot_0002.bmp)|
| Iskola terasz     | Smart HD 550  | 71.4 dBuV    | QPSK, 1/32      | 28.4  | 32.2dB | ![its_snapshot_0003.bmp](https://github.com/user-attachments/files/22968102/its_snapshot_0003.bmp)|

### Észrevételek: 
##### -Tanári parkoló udvar: Mivel elég magas épületek között mérünk, ezért várható volt, hogy nem itt lesz a legjobb jelerősség, de nem is volt annyira rossz mint a V3 tanteremben
#####               -V3 Tanterem: itt volt a legrosszabb jelerősség, de bőven HD minőégű volt, de ez is hiba nélkül jött
#####               -Iskola bejárati teraszán: Itt volt a legjobb jelerősség, szinte alig van 30m-es közelben fa vagy magasabb épület az Avasi kilátó felé nézve, mind a három antennának itt volt a legjobb jelerősség


| # | Antenna típusa                | Megjegyzés | 
|---|-------------------------------|-------------|
| 1 | Iskra P-58 L700 UNI H/V SMA   | Ez rendelkezett a legjobb jelerősséggel |
| 2 | Iskra P20 LOGPER              | Ez volt a második legjobb jelerősségű |
| 3 | Opticum Smart HD 550          | Ez rendelkezett a legrosszab jelerősséggel, de ez is bőven elfogadható |

### Oszlopdiagram a jelerősségekről
!<img width="652" height="417" alt="image" src="https://github.com/user-attachments/assets/727e04ff-2204-4d1f-a082-a70642aea3a7" />




# Antenna összehasonlítás

| Tulajdonság | Iskra P-58 L700 UNI H/V SMA | Iskra P20 LOGPER | Opticum Smart HD 550 |
|--------------|------------------------------|------------------|-----------------------|
| **Alkalmazás / cél** | Szélessávú külső antenna mobil / adat (LTE700-3800 MHz) | UHF TV-antenna, log-periódikus kialakítás (470-862 MHz) | Beltéri/külső TV-antenna DVB-T/T2 + DAB, UHF/VHF (470-862 MHz) |
| **Frekvenciatartomány** | LTE 700 (698-790 MHz), LTE 800 (790-862 MHz), GSM 900, DCS 1800, UMTS, WiFi 2.4 GHz, LTE 2.6 GHz (2.5-2.7 GHz) | UHF 470-862 MHz | VHF 87.5-230 MHz, UHF 470-862 MHz |
| **Nyereség (Gain)** | 9-11 dBi | 7.5 – 22.5 dBi (verziótól függ) | kb. 9 – 14 dBi (max 30 dB aktív verzió) |
| **Polarizáció / Csatlakozás** | H/V polarizáció, SMA csatlakozó | H/V polarizáció, F-csatlakozó | Állítható polarizáció, koaxiális csatlakozó |
| **Felhasználás** | Mobil hálózatok, adatkommunikáció, 4G/5G | Földi digitális TV (DVB-T/T2), kültéri szerelés | Beltéri/külső TV- és rádióvétel (DVB-T/T2, DAB) |
| **Erősségek** | Szélessávú, több hálózatot kezel, masszív kivitel | Stabil UHF vétel, log-periodikus konstrukció | Egyszerű használat, kis méret, beltérre is alkalmas |
| **Gyengeségek** | Nem kifejezetten TV-vételre optimalizált | Kültéri szerelést igényelhet, verziófüggő teljesítmény | Gyenge jelnél kevésbé hatékony, kisebb nyereség |
| **Árkategória (2025)** | ~25 000 Ft | ~4 500 Ft | ~6 000 Ft |
| **Ajánlott felhasználás** | LTE / adat / 5G projektekhez | Kültéri TV vételhez, jó kompromisszum | Beltéri TV vételhez, erős jelű helyen |

---

### Összegzés

- 📡 **Iskra P-58 L700 UNI H/V SMA** – professzionális, szélessávú antenna, főként LTE/5G és adatkommunikációhoz.  
- 🎯 **Iskra P20 LOGPER** – legjobb választás **földi digitális TV vételhez** (különösen kültéren).  
- 🏠 **Opticum Smart HD 550** – kedvező árú, **beltéri/külső** antenna, ha erős a jel.  

---

### Mérési környezet

| Mérési paraméter | Érték |
|-------------------|-------|
| Mérés | Miskolc TV |
| Frekvencia | 634 MHz |
| Csatorna | CH41 |
| Időjárás | 18 °C, felhős idő, jó vételi körülmények |
| Mérési időtartam | 40–50 perc |





Aláírás: Matiscsák Márk    
Dátum: 2025.10.17
