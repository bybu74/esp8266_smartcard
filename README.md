Use esp8266's GPIO to simulate a smart card, while running an oscam client, connecting to the cccam server via esp8266's wifi.

Pentru a simula un card inteligent, utilizați ESP8266 și conectați-l la un cititor de carduri standard pentru set-top box pentru a realiza partajarea CCCAM. Sunt necesare patru cabluri de date pentru a conecta cititorul de carduri și porturile GPIO ale ESP8266: VCC, GND, 5 și 2. GPIO 2 este portul I/O, conectat la portul I/O al cititorului de carduri; GPIO 5 este portul RST, conectat la portul RST al cititorului de carduri.

În unele cazuri, o rezistență de 470 ohmi trebuie conectată în serie între porturile I/O și RST ale ESP8266 și cititorul de carduri.

Acest proiect este compilat folosind Arduino și necesită instalarea bibliotecii de suport ESP8266 și a bibliotecii ESPAsyncTCP. În prezent, acesta acceptă emularea plăcii Yongxin Tongfang. Poate apărea instabilitate în timpul vizualizării prelungite; cauza este necunoscută. Cei care doresc să experimenteze pot adăuga suport pentru alte plăci.
