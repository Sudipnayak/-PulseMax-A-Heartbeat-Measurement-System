# -PulseMax-A-Heartbeat-Measurement-System
Project Title: Heartbeat Measurement using ESP8266 NodeMCU with MAX30102 Pulse Oximeter and RemoteXY Webserver

Description:
As part of a mini project, I undertook the development of a heartbeat measurement system using the ESP8266 NodeMCU microcontroller, MAX30102 pulse oximeter sensor, and the RemoteXY webserver platform. The objective was to create a web-based interface to monitor and display real-time heartbeat data.

For the project, I utilized the ESP8266 NodeMCU as the primary controller. This powerful microcontroller, equipped with Wi-Fi capabilities, enabled seamless communication with the RemoteXY webserver. The MAX30102 pulse oximeter sensor, which integrates red and infrared LEDs with a photodetector to measure heart rate and blood oxygen levels, was connected to the NodeMCU for data acquisition.

To implement the project, I began by programming the NodeMCU to collect and process data from the MAX30102 sensor. I utilized signal processing techniques to extract meaningful heartbeat information from the raw data acquired by the sensor. The processed data was then transmitted to the RemoteXY webserver.

I employed the RemoteXY platform as the webserver for visualizing and displaying the heartbeat data in real-time. RemoteXY provided a user-friendly web interface that could be accessed from any device connected to the internet. Through this interface, users were able to monitor their heart rate variations conveniently.

The web interface created with RemoteXY included interactive elements such as graphs and charts, which depicted the heartbeat data over time. This visualization aided users in understanding their heart rate patterns and detecting any abnormalities. Additionally, the RemoteXY platform allowed for customization, enabling me to tailor the web interface to suit the project requirements.

To ensure the security and privacy of the data transmitted, I implemented user authentication and employed encryption techniques to safeguard the communication between the webserver and connected devices. This ensured that only authorized individuals could access and view the heartbeat data.

Throughout the project, I encountered challenges related to optimizing the NodeMCU's performance for real-time data transmission and integrating the MAX30102 sensor with the RemoteXY webserver. These hurdles were overcome through diligent research, iterative development, and troubleshooting.

Completing this project provided me with valuable experience in working with microcontrollers, sensors, web development, and data visualization. It enhanced my proficiency in programming languages as well as my understanding of signal processing techniques.

The heartbeat measurement system, utilizing the ESP8266 NodeMCU, MAX30102 pulse oximeter sensor, and RemoteXY webserver, demonstrates my capability to design and develop innovative solutions utilizing embedded systems and web technologies. This project showcases my problem-solving skills, technical competence, and enthusiasm for creating practical applications that contribute to healthcare and well-being.

![PROJECT PIC](https://github.com/Sudipnayak/-PulseMax-A-Heartbeat-Measurement-System/assets/81667491/1da0cafe-6d25-435c-81c8-655bdff49352)

OUTPUT

The BPM readings will continuously update to new ones in the Arduino IDE compiler.

![image](https://github.com/Sudipnayak/-PulseMax-A-Heartbeat-Measurement-System/assets/81667491/81e78dec-1a02-42a8-9b86-46bb045c23d6)

I also have used RemoteXY to show the results of BPM ( Beats per minute) whose readings taken within a second and then multiplied with 60 to make it per minute and then the average BPM is found out after few BPM readings.

![image](https://github.com/Sudipnayak/-PulseMax-A-Heartbeat-Measurement-System/assets/81667491/6bc5ec69-1aaa-42dd-a05b-8983d1c62e2e)

