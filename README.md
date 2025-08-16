<img width="786" height="498" alt="image" src="https://github.com/user-attachments/assets/c145b83e-b2d1-4c4a-af3b-b18f5f1aaa8d" />




# Lettusee User Manual  

## 📌 Introduction  
Welcome to **Lettusee**, an interactive 2D farming application that integrates with real-world IoT hardware to help you manage and monitor your lettuce farm.  

With **Lettusee**, you can:  
- Simulate and visualize farm operations in a fun and interactive way.  
- Control essential farming processes such as irrigation, nutrient mixing, dispensing, and environmental management.  
- Access real-time data from sensors and take informed actions for healthier crops.  
- Manage sales, inventory, and analytics, all from within the app.  

Developed by 4th Year BS Computer Engineering students from **STI College San Pablo**:  
- Mark Joseph T. Esmil  
- James Allen A. Ferrer  
- Gabriel Marcial A. Reyes  

---

## 🎮 Application Manual  

### Pressable Buttons and Their Functions  

- **Drum Manager**  
  - Prepares the irrigation solution.  
  - Mixes Masterblend and Calcium Nitrate in the correct ratio.  

- **Dispense**  
  - Dispenses Masterblend and Calcium Nitrate into the drum.  
  - Must be done **before mixing** begins.  

- **Mixer**  
  - Activates the mixing machine for 2–3 minutes to dissolve the solution.  
  - Requires dispensing to be completed first.  

- **Transfer Solution**  
  - Transfers the mixed solution from the main drum to the sub-drum for irrigation.  

- **Irrigation**  
  - **Automatic Mode**: Waters crops at scheduled intervals.  
  - **Manual Mode**: Direct user control of water flow.  

- **Drain**  
  - Drains water from the farm back to the reservoir to restart the cycle.  

- **Fan**  
  - Turns on cooling fans to regulate farm temperature.  

---

### 🌱 Farm Monitoring Buttons  

- **Add Masterblend & Calcium**  
  - Track refills of Masterblend and Calcium Nitrate.  

- **Sales System**  
  - Log harvested lettuce sales (quantity & price).  
  - Automatically updates records in the cloud database.  

---

### 📡 Farm Monitoring Sensors  

- **Soil Moisture Sensor** → Monitors moisture levels per pipe, displayed in-app.  
- **Humidity Sensor** → Tracks farm humidity (in “Tools” section).  
- **Temperature Sensor** → Displays current and daily maximum temperature.  
- **Weather API** → Provides a 5-day weather forecast.  
- **pH Sensor** → Monitors acidity/alkalinity of the irrigation solution.  
- **TFT Screen** → Displays real-time sensor values: moisture, temperature, humidity, pH.  

---

### 📊 Data & Analytics  

- **Sales Reports** → View logged sales over time.  
- **Predictive Analytics** → Forecast future sales based on history.  
- **Graphs** → Track growth trends, inventory, and profits.  

---

## ⚙️ Hardware Manual  

### Manual Operations (Offline Mode)  
If the internet is unavailable, Lettusee hardware can still operate:  

1. **Unplug IoT Device** from the relay box → connect directly to power.  
2. **Manual Mixer Button** → Run the mixer locally.  
3. **Irrigation Timer Relay** → Waters crops at pre-set intervals.  

✅ Your farm continues running even without internet access.  

---

## 🚀 Getting Started  

1. **Install the Application**  
   - Open Lettusee on your device.  
   - Log in with your account.  

2. **Connect to IoT Device**  
   - Ensure hardware is powered on & connected to Wi-Fi.  
   - Pair via the app’s settings.  

3. **Start Farming**  
   - Use buttons to control **dispensing, mixing, irrigation, and fans**.  
   - Monitor farm data in the **real-time dashboard**.  

---

## 🔒 Safety & Best Practices  

- Always follow correct solution order: **Dispense → Mix → Transfer → Irrigate**.  
- Avoid overfilling drums to prevent overflow.  
- Use **Automatic Irrigation** for consistency.  
- Clean sensors regularly for accurate readings.  
- Backup sales & inventory data often.  

---

## 📢 Credits  

Developed by:  
👨‍💻 Mark Joseph T. Esmil  
👨‍💻 James Allen A. Ferrer  
👨‍💻 Gabriel Marcial A. Reyes  
📍 STI College San Pablo, BS Computer Engineering  

