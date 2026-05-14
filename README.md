# Climate Monitor Firmware

Firmware repository for the Climate Monitor System IoT platform.

## Devices

### ESP32 + SHT3X

Temperature and humidity monitoring using:

- ESP32-WROOM-32
- SHT3X sensor
- WiFi connectivity
- HTTP requests to Supabase

Folder:

```txt
esp32-sht3x/
```

---

### ESP8266 + BME280

Secondary monitoring node using:

- ESP8266MOD
- BME280 sensor
- WiFi connectivity
- HTTP requests to Supabase

Folder:

```txt
esp8266-bme280/
```

---

## Architecture

```txt
Devices
   ↓
Supabase
   ↓
Next.js Dashboard
```

---

## Features

- Multi-device support
- Real-time sensor monitoring
- Cloud database integration
- Shared backend architecture
- Modular firmware structure

---

## Related Project

Dashboard repository:

```txt
climate-dashboard
```

---

## Author

Developed by Hector Moreira.