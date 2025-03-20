IoT Car Parking System Using RFID
Overview
The IoT Car Parking System Using RFID is a smart parking solution that utilizes RFID technology to automate and manage vehicle entry and exit in a parking lot. This system enhances security, reduces manual effort, and efficiently tracks parking availability in real-time.
Features
•	RFID-Based Authentication: Vehicles are equipped with RFID tags that allow automatic entry and exit.
•	Real-Time Monitoring: IoT-enabled system to track parking occupancy.
•	Automated Barrier Control: Servo motors control barriers to grant or deny access.
•	Data Logging: Stores entry and exit details for security and analysis.
•	LCD Display & Alerts: Displays parking availability and provides notifications.
Components Used
•	RFID Reader & Tags: To identify authorized vehicles.
•	ESP32: For IoT connectivity and system control.
•	Servo Motor: Controls the barrier gate.
•	LCD Display (16x2): Displays parking status.
•	IR Sensors: Detect vehicle presence.
•	Buzzer: Alerts unauthorized access.
•	Cloud Server / Database: Stores vehicle entry-exit records.
Working Principle
1.	Vehicle Authentication: When a vehicle approaches, the RFID reader scans the RFID tag.
2.	Access Decision: If the tag is registered, the barrier opens; otherwise, access is denied.
3.	Parking Status Update: IoT updates real-time parking availability.
4.	Exit Process: When the vehicle exits, the system updates the database.
5.	Data Storage: All transactions are logged for monitoring.
Installation & Setup
1.	Hardware Setup: 
o	Connect RFID reader, LCD, IR sensors, and servo motor to NodeMCU.
o	Configure the buzzer and power supply.
2.	Software Requirements: 
o	Arduino IDE for programming ESP-32.
o	cloud database for data storage.
o	Web/Mobile interface for monitoring.
3.	Code Upload: 
o	Write and upload the firmware to ESP32.
o	Configure the WiFi credentials for cloud integration.
Applications
•	Smart Parking Systems in malls, offices, and residential complexes.
•	Automated toll collection at highways.
•	Secure access control in restricted areas.
Future Enhancements
•	Integration with mobile apps for user reservations.
•	AI-based analytics for parking space prediction.
•	Integration with payment gateways for automated billing.
Contributors
•	Abhijit Maity - Developer
•	Avijit Biswas, Bikram Paul, Archisman Kundu - Team Members
Contact
For queries, reach out at: abhijit334@gmail.com 
