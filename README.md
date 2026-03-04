# Smart Neckband ESP32

# Smart Sleep Therapy Device

A wearable device designed to improve sleep quality for insomnia patients using real-time physiological monitoring, AI-based sleep stage prediction, and adaptive therapy through vibration and thermal stimulation.

---

## Features

- **Real-time Physiological Monitoring**
  - Collects heart rate, temperature, and movement data using onboard sensors.

- **LSTM-Based Sleep Stage Prediction**
  - Predicts sleep stages and detects restlessness for personalized interventions.

- **Adaptive Therapy Control**
  - Adjusts **vibration motor** and **graphene heating element** based on user sleep patterns.

- **Learning Over Time**
  - Device adapts therapy strategies over multiple nights for optimal results.

- **Mobile App Integration**
  - Provides analytics, sleep summaries, and personalized recommendations.
  - Allows users to choose therapy modes ( heating, or vibration intensity).

---

## Workflow

1. Sensors collect real-time physiological data.  
2. LSTM predicts sleep stages and detects restlessness.  
3. Adaptive control module adjusts vibration and thermal therapy.  
4. Device learns and improves therapy over multiple nights.  
5. Mobile app provides analytics and personalized recommendations.

---

## Hardware Components

- Microcontroller: **ESP32 **  
- **Vibration Motor** – for gentle tactile stimulation  
- **Graphene Heating Element** – for controlled thermal therapy  
- Sensors for monitoring heart rate, temperature, and movement

---

## Software Components

- **Arduino / ESP32 Firmware**  
- **Python / TensorFlow / PyTorch** for LSTM sleep stage prediction  
- **Flutter Mobile App** for analytics and user interface

---

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/username/smart-sleep-therapy.git
