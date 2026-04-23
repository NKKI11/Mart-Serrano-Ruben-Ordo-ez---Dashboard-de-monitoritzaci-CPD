# Dashboard de monitorització CPD

## 📌 Objectiu
Convertir un ESP32 en un servidor web que monitoritzi la temperatura d'una sala de servidors (CPD) i activi alarmes físiques i visuals.

## 🔧 Components utilitzats
- ESP32
- Sensor de temperatura LM35
- LED vermell
- Resistència 220Ω (per al LED)

## ⚙️ Funcionalitats
- Servidor web amb informació de temperatura
- Actualització automàtica cada 5 segons
- Alarma visual (targeta vermella) quan T > 24°C
- Alarma física (LED encès) quan T > 24°C
- Pàgina secundària de crèdits (/credits)

## 📡 Connexió WiFi
- SSID: ProjectesSMX
- Password: Hola1234

## 📁 Estructura del projecte
