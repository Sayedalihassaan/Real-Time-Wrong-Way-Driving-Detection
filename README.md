# **RoadGuard: Real-Time Wrong-Way Driving Detection System** 🚗🚨

This project focuses on detecting wrong-way driving in real-time using YOLOv8, OpenCV, and Telegram integration for alert notifications. The system identifies vehicles traveling in the wrong direction by analyzing video feeds and triggers immediate notifications, improving road safety and accident prevention. The system uses object tracking and area-based detection to determine when a car enters a restricted zone without following the correct path.

## **Features**:
- 🚗 Real-time wrong-way driving detection using YOLOv8
- 🚨 Instant alert notifications via Telegram Bot
- 🛑 Customizable detection areas for wrong-way zones
- 🔔 Audio alarms for wrong-way driving alerts
- 📸 Captures and sends images of detected incidents to Telegram

## **Technologies Used**:
- **YOLOv8**: Object detection for vehicle classification and tracking.
- **OpenCV**: Real-time image processing and video analysis.
- **Pygame**: Audio alert system when wrong-way driving is detected.
- **Telegram API**: Sends alerts and captures to Telegram for immediate response.

## **How It Works**:
1. The system processes video feeds to detect vehicles using YOLOv8.
2. It tracks each vehicle and monitors if it enters a restricted area without passing through the designated zones.
3. If a vehicle is detected as driving the wrong way, an alert is triggered, and an image is sent to a Telegram bot.
4. A sound alarm is also triggered for immediate awareness.

## **Setup Instructions**:
### 1. Clone the repository:
```bash
git clone https://github.com/your-username/roadguard-wrong-way-detection.git
cd roadguard-wrong-way-detection
```

### 2. Install required libraries:
```bash
pip install -r requirements.txt
```

### 3. Set up the Telegram bot:
- Replace `your-telegram-bot-token` and `your-chat-id` in the script with your actual Telegram Bot Token and Chat ID.

### 4. Run the detection:
```bash
python main.py
```

## **Contributing**:
- Fork the repository, make your changes, and create a pull request.
- Feel free to submit issues for bugs, improvements, or features!

## **License**:
MIT License.

---

### **GitHub Link**:
[View the full project on GitHub](https://github.com/your-username/roadguard-wrong-way-detection)

---

### LinkedIn Post Template:

---

🚗 **Introducing the RoadGuard Real-Time Wrong-Way Driving Detection System!** 🚨

I am excited to share my latest project, **RoadGuard**, a real-time system designed to detect wrong-way driving and improve road safety. Using cutting-edge **YOLOv8** for object detection and **OpenCV** for real-time video processing, this system identifies vehicles traveling in the wrong direction and triggers immediate alerts. 🚨

🔍 **Key Features:**
- Detects wrong-way driving in real-time
- Sends instant alerts and captures images via **Telegram** bot
- Audio alarms for immediate awareness
- Improves road safety by helping prevent accidents

Check out the full project and its code here:  
[GitHub - RoadGuard](https://github.com/your-username/roadguard-wrong-way-detection)

#AI #ComputerVision #YOLOv8 #OpenCV #TelegramBot #WrongWayDetection #MachineLearning #RoadSafety #TrafficManagement #DeepLearning #TechForGood

---

This version of the **README.md** and LinkedIn post is designed to attract attention while providing all the essential details about your project. You can adjust the links or further personalize the descriptions if needed! Let me know if you'd like any changes.
