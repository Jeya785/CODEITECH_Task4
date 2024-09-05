**Name: JEYA PRIYA S**
**Company: CODTECH IT SOLUTIONS**
**ID: CT12DS2256**
**Domain: Internet of Things**
**Duration: August to October 2024**
**Mentor: Neela Santhosh Kumar**

### Overview of the Project

### Project: Health Monitoring Wearable Device using Arduino Uno
This project is a health monitoring wearable device developed using Arduino Uno. The device is designed to track and display vital health parameters such as heart rate, body temperature, and oxygen levels, providing real-time data. It aims to offer a low-cost, customizable solution for basic health monitoring, especially in environments where access to advanced medical devices is limited.

#### Key Components:
1. **Arduino Uno**:
   - Serves as the microcontroller to process and manage sensor data.
   - It’s easy to use, affordable, and widely supported by a large community of developers.
2. **Sensors**:
   - **Heart Rate Sensor (e.g., Pulse Sensor or MAX30100)**:
     Measures the heart rate in beats per minute (BPM).
   - **Temperature Sensor (e.g., LM35 or DS18B20)**:
     Records the body temperature in degrees Celsius or Fahrenheit.
   - **Pulse Oximeter Sensor (e.g., MAX30100 or MAX30102)**:
     Tracks oxygen saturation (SpO2) levels in the blood.
3. **Display (OLED or LCD)**:
   - Displays real-time health data like heart rate, body temperature, and oxygen levels.
4. **Power Supply**:
   - The device can be powered by a rechargeable battery, ensuring portability.
5. **Optional Components**:
   - **Bluetooth Module (e.g., HC-05)**: To transmit data wirelessly to a mobile app.
   - **Buzzer**: To provide alerts when health parameters exceed certain thresholds.

#### Key Features:
- **Heart Rate Monitoring**: The pulse sensor is used to measure the user’s heart rate in real-time, providing alerts when abnormal patterns are detected.
- **Body Temperature Monitoring**: The temperature sensor continuously tracks body temperature and provides feedback when feverish conditions are detected.
- **Oxygen Saturation**: The pulse oximeter measures the SpO2 levels, giving an indication of oxygen levels in the blood, critical for respiratory monitoring.
- **Real-Time Data Display**: The OLED/LCD displays the collected data for immediate viewing by the user.
- **Portable and Wearable**: Compact design with the ability to be worn as a wristband, making it ideal for continuous health monitoring.
- **Customizable Alerts**: Thresholds for the heart rate, temperature, and SpO2 can be customized. If any parameter exceeds the threshold, the device provides alerts through visual or auditory means.

#### Software Implementation:
1. **Arduino IDE**:
   - Programmed using Arduino IDE with libraries for each sensor (e.g., PulseSensorPlayground, Adafruit_MAX30100 for SpO2, and DallasTemperature for body temperature).
2. **Data Collection**:
   - Sensor readings are collected at intervals, processed, and displayed on the screen.
3. **Alert System**:
   - If the readings exceed the predefined safe levels (e.g., heart rate above 100 BPM or SpO2 below 90%), the device triggers an alarm or sends a notification.
4. **Optional Bluetooth Data Transmission**:
   - For remote monitoring, the Bluetooth module transmits the data to a smartphone app or a cloud service.

#### Use Cases:
- **Personal Health Monitoring**: Useful for tracking daily vital signs and identifying early signs of health issues.
- **Telemedicine**: In remote areas, this device can help healthcare providers monitor patients' vital signs remotely.
- **Fitness Tracking**: It can be used as a simple fitness tracker to monitor heart rate and oxygen levels during exercise.

# Future Enhancements:
- **Mobile App Integration**: Developing a mobile app for real-time data synchronization.
- **Cloud Storage**: Storing long-term data on the cloud for trend analysis.
- **Enhanced Power Management**: Optimizing battery life for prolonged use.
  
