<div align="center">
  <h1>🌍 ESP32 GPS Clock & Weather Station</h1>
  <p>
    <img src="https://img.shields.io/badge/license-GPL%20v3-blue.svg" alt="License">
    <img src="https://img.shields.io/badge/platform-ESP32-green.svg" alt="Platform">
    <img src="https://img.shields.io/badge/Arduino-Compatible-yellow.svg" alt="Arduino">
  </p>
  <p><em>A smart clock that syncs with GPS satellites and monitors environmental conditions! 🛰️</em></p>
</div>

---

<h2>✨ Features</h2>
<table>
  <tr>
    <td>🕒 Time</td>
    <td>GPS-synchronized precise timekeeping</td>
  </tr>
  <tr>
    <td>🌡️ Environment</td>
    <td>Temperature & humidity monitoring</td>
  </tr>
  <tr>
    <td>🔆 Display</td>
    <td>Auto-brightness & power saving</td>
  </tr>
  <tr>
    <td>📱 Connectivity</td>
    <td>WiFi with OTA updates</td>
  </tr>
</table>

<h2>🛠️ Hardware Requirements</h2>

<details>
<summary><strong>Core Components 📋</strong></summary>

| Component | Purpose | Notes |
|-----------|---------|--------|
| ESP32 devkit v1 | 🧠 Controller | DOIT version recommended |
| BH1750 | 💡 Light sensor | I²C interface |
| BME280 | 🌡️ Environment | Temperature/Humidity |
| GPS Neo 6m | 📡 GPS receiver | UART interface |
| ST7920 LCD | 🖥️ Display | 128x64 pixels |
| Buzzer | 🔊 Alerts | Active buzzer |

</details>

<details>
<summary><strong>Optional Components 🔧</strong></summary>

- 🔋 LiFePO4 AAA 80mAh (GPS backup)
- ⚡ TP5000 charging circuit
- 🔌 BMS with IN4007 diode
- 🛠️ Prototyping materials

</details>

<h2>⚠️ Important Notice</h2>
<div style="background-color: #fff3cd; padding: 10px; border-radius: 5px; border-left: 5px solid #ffeeba;">
  <strong>❌ DO NOT USE AHT25 SENSOR!</strong><br>
  Due to significant accuracy issues, we recommend using BME280/BMP280/TMP117 instead.
</div>

<h2>📜 License</h2>
<div style="background-color: #e9ecef; padding: 15px; border-radius: 5px;">
<h3>GNU General Public License v3.0</h3>

<h4>✅ Permissions</h4>
<ul>
  <li>Commercial use</li>
  <li>Modification</li>
  <li>Distribution</li>
  <li>Patent use</li>
  <li>Private use</li>
</ul>

<h4>⚠️ Conditions</h4>
<ul>
  <li><strong>License and copyright notice:</strong> Include the original license and copyright</li>
  <li><strong>State changes:</strong> Document all modifications</li>
  <li><strong>Disclose source:</strong> Make source code available</li>
  <li><strong>Same license:</strong> Use the same license for derivatives</li>
</ul>

<h4>❌ Limitations</h4>
<ul>
  <li>No liability</li>
  <li>No warranty</li>
</ul>
</div>

<h2>🤝 Contributing</h2>
<div align="center">
  <table>
    <tr>
      <td>🍴 Fork</td>
      <td>🔧 Code</td>
      <td>📤 Push</td>
      <td>📫 PR</td>
    </tr>
  </table>
</div>

<h2>📞 Support</h2>
<div align="center">
  <p>If this project helps you, please consider:</p>
  <p>
    ⭐ Giving it a star<br>
    🐛 Reporting issues<br>
    💡 Suggesting improvements<br>
    🤝 Contributing code
  </p>
</div>

---

<div align="center">
  <sub>Built with ❤️ by the ESP32 community</sub>
</div>
