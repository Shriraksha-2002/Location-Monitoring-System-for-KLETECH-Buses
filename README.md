
# Location-Monitoring-System-for-KLETECH-Buses
ABSTRACT:

The public transportation system requires effective tracking and monitoring of bus
locations for efficient operations and improved passenger experience. Hence, the tracking
and monitoring of bus locations is crucial. In this work, we propose a system that
automates the recording of GPS-based locations for KLETECH buses using IoT devices
and a web/mobile application. Each bus will be equipped with an IoT device, such
as an ESP32 microcontroller with a A7672x evaluation board with GNSS, which will
periodically send the bus’s GPS coordinates to the Cloud platform for storage and analysis.
A web/mobile application is developed to provide a user-friendly interface for accessing
the recorded bus location data, generating reports, and setting up alerts. The proposed
system will leverage the capabilities of firebase, a cloud-based IoT analytics platform, to
store and analyze the GPS data. Firebase APIs and libraries are used to integrate the
IoT devices with the platform, enabling seamless data transmission and storage. The
secure authentication mechanisms are implemented to prevent unauthorized access to
the system. The monitoring mechanisms, such as logging and alerting, will be in place
to ensure system reliability and performance. The proposed system will also provide
real-time visibility of bus locations, enabling KLETECH to make data-driven decisions
for improved operational efficiency and enhanced passenger experience.

INTRODUCTION:

KLETECH, a leading educational institution, provides transportation services to its
students for their daily commute. As the number of students using the transportation
service is increased, the need for an automated system to track the location of KLETECH
buses has become crucial. This system will provide real-time location data for each bus,
enabling students to plan their travel accordingly and improving overall efficiency of the
transportation service.
To address this need, we propose a system that will use IoT devices installed in each
KLETECH bus to collect and transmit GPS-based location data to a centralized web
and/or mobile application. The application will store and analyze the data, providing
reports and alerts to stakeholders. This system will enhance the overall efficiency of the
transportation service, allowing KLETECH to provide better services to the students.
The proposed system will consist of IoT devices equipped with location sensors, installed
in each KLETECH bus. These IoT devices will be connected to the centralized web and/or
mobile application through a wireless network, allowing for real-time data transmission.
The web and/or mobile application will provide a user-friendly interface for data storage,
analysis, and visualization.
Furthermore, the system will be equipped with advanced analytics capabilities to
generate reports and alerts based on predefined rules. Stakeholders, including KLETECH
transportation administrators, and students, will receive alerts via email, SMS, or app
notifications in case of any delays or deviations from planned routes.
Furthermore, the proposed system will enhance the safety and security of KLETECH
students. In the event of an emergency, administrators can quickly identify the location
of each bus and ensure the safety of students on board. The system can also be used to
monitor driving behavior, ensuring that drivers adhere to safety standards and operate
vehicles in a responsible manner.
Overall, the proposed system will provide a comprehensive solution for tracking the
location of KLETECH buses in real-time, enabling better planning and decision-making
for all stakeholders involved in the transportation service.


MOTIVATION: 

One of the primary motivations is to enhance the safety and security of students who
use college buses to commute to and from college. With a tracking system, the college
can monitor the movement of its buses and ensure that students reach their destination
safely. In case of any emergency, the system can also be used to alert authorities and
take necessary actions. With a tracking system, students can know the exact location
and arrival time of their bus, which will help them to plan their schedule better and
avoid waiting for long hours at the bus stop. In case of efficiency,the system can provide
real-time data of location and status of each bus, allowing administrators to optimize their
routes, reduce wait times. By optimizing bus routes and reducing wait times. Overall, a
college bus tracking system can benefit both students and administrators in several ways,
including safety, convenience, efficiency, cost savings, and improved communication.


OBJECTIVES:

1. The main purpose of Real-Time Tracking is that the system should provide real-time
   tracking of college buses, allowing students and administrators to know the exact
   location of each bus at any given time.
2. Develop and implement an IoT device with appropriate sensors for location sensing
   in each bus.
3. Configure the IoT device to periodically send the location coordinates to a database
   for storage.
4. Design and develop a web and/or mobile application to store and manage the location
   data received from the IoT devices.
5. Incorporate alerting mechanisms into the system to notify stakeholders of any issues,
   such as bus delays, route deviations, or accidents.
6. The system should reduce wait times for students at bus stops by providing accurate
   arrival and departure times of buses

PROBLEM STATEMENT:

Design a system to automatically record the GPS based location for KLETECH buses.
Each bus will be associated with an IoT device connected to an appropriate sensor
for location sensing. The IoT device in each bus will send the location coordinates to
ThingSpeak/database periodically. System should be able to provide the location of a
bus at any given time. A web and/or mobile application must be developed for data
storage, data analytics, creation of reports and alerts (alert through email /sms/ app
notification)

COMPONENTS USED:

1. A7672S Evaluation Board
The Valetron system A7672S Evaluation board is an electronic development board designed
to evaluate and test the performance of the A7672S power management IC (Integrated
Circuit) produced by Valetron Systems.
The A7672S is a highly efficient power management IC that integrates a DC-DC
converter, a low-dropout regulator (LDO), and a battery management unit (BMU) into
a single package. It is primarily used for powering portable devices such as smartphones,
tablets, and laptops. The A7672S is capable of delivering up to 4.5A of current with a
conversion efficiency of up to 95 percentage.
The A7672S Evaluation board is designed to help developers and engineers test the
capabilities of the A7672S and explore its potential applications. The board includes
various connectors, switches, and test points that allow users to connect external devices
and measure the performance of the A7672S in real-world scenarios. The board also
includes an onboard USB port for programming and debugging. 
Specifications
• Operating voltage : +3.3V to +5V
• Current : 400mA.
• Temperature : 0ºC to +80ºC.
• Frequency : 100 kHz to 3 MHz
• Communicating parameters : 115200
• Integrated Antenna.
• PCB Dimensions - Length: 75mm * Width: 50mm * Thickness: 10 mm


![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/ba075516-e1d3-4149-9abb-f2913dd8cbcb)



3. ESP32-WROOM-32 Development Board

ESP32-WROOM-32 firmware is a powerful platform for IoT applications. It contains
all the functionality of the ESP32, allowing the user to connect to her Wi-Fi network,
interact with the Internet, create and store data, and build powerful applications. Based
on a lightweight version of the Lua scripting language, it is designed for developers familiar
with the Arduino platform. The firmware has an integrated function library that allows
users to quickly and easily create applications for their projects.The ESP32 Development
Board is a great way to start programming the ESP32. It’s cheap and feature-packed,
making it perfect for anyone looking to develop an IoT product. The ESP32 firmware is
open source and can be easily modified to suit the needs of any project. It’s also compatible
with the Arduino IDE and other popular development platforms, making it an ideal
choice for developers of all skill levels.The pinout configuration of ESP32-WROOM-32
 Specifications
• Memory: 520 KB SRAM , 448 KB ROM , 4 MB Flash memory
• Wi-Fi: 802.11 b/g/n/e/i wireless protocol ,
• Bluetooth: Bluetooth v4.2 BR/EDR and BLE specification
• Interfaces: UART, SPI, I2C, I2S, ADC, DAC, PWM, and GPIO interfaces
• Power supply: 2.2V to 3.6V, with support for deep sleep power consumption as low
as 5 μA
• Operating temperatures: -40 to 85 degrees Celsius
• Clock Speed : 240 MHz


![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/0b8ccd46-ec68-4973-8c0a-fcf278111323)



5. Li-on Battery

• Capacity :25±5°C
• Nominal Capacity 2600mAh (0.52A Discharge2.75V)
• Typical Capacity 2550mAh0.52A Discharge2.75V
• Minimum Capacity 2500mAh (0.52A Discharge2.75V)
• Nominal Voltage : 3.7V
• Internal Impedance : 70mΩ
• Discharge Cut-off Voltage : 3.0V
• Max Charge Voltage : 4.20±0.05V
• Rapid Charge Current : 1.3A
• Weight : 46.5±1g
• Maximum Dimension Diameter(Ø) : 18.4mm Height (H): 65.2mm

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/3af9e327-cc79-41d8-8796-8794ab042f9d)

CLOUD PLATFORM: 


Google’s Firebase is a tool that makes it simple for developers to create, maintain, and
expand their apps. It makes it easier for developers to create apps more quickly and
securely. Because there is no programming required on the firebase side, it is simple to
use the features more effectively. It offers services to web, unity, android, and ios. It offers
online storage. The database used for data storage is a NoSQL one.

1.  Realtime Database: The Firebase Realtime Database is a NoSQL database that runs
in the cloud and maintains data at a blistering millisecond pace. It can be compared
to a large JSON file in the simplest terms.
2.  Cloud Firestore: A NoSQL document database, the cloud Firestore offers capabilities
including worldwide syncing, querying, and storage through the application. In the
form of objects, also referred to as Documents, it holds data. It can store any type
of data, including texts, binary data, and even JSON trees, and has a key-value pair.
3.  Authentication: To allow users to access your app, the Firebase Authentication
service offers simple-to-use UI frameworks and SDKs. The amount of labour and
time needed to create and maintain the user authentication service is decreased.
Even complicated manual chores like merging accounts are handled by it.
4.  Remote Config: The service for remote configuration aids in instantly publishing
updates to the user. The modifications could involve anything from changing UI
elements to altering how the applications behave. These are frequently utilised for
posting seasonal offers and contents to applications with short lifespans.

FUNCTIONAL BLOCK DIAGRAM:

Equip each KLETECH bus with an IoT device, such as an ESP32 microcontroller
with an A7672x evaluation board with inbuilt GNSS.Program the IoT device to periodically collect and send the bus’s GPS coordinates
to a cloud-based IoT analytics platform, such as Firebase.
 Use Firebase APIs and libraries to integrate the IoT devices with the platform,
enabling seamless data transmission and storage.
Develop a web/mobile application that provides a user-friendly interface for accessing
the recorded bus location data, generating reports, and setting up alerts.
The application should be integrated with Firebase to enable data retrieval.
Implement secure authentication mechanisms to prevent unauthorized access to the
system.
Put monitoring mechanisms in place, such as logging and alerting, to ensure system
reliability and performance.
Use the real-time visibility of bus locations provided by the system to make data-driven
decisions for improved operational efficiency and enhanced passenger experience

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/9a20c48c-d1f2-4bbf-a937-1aee8d3127d4)


FLOW CHART:

The Figure 3.2 is the process we carried to implement this project. When the power
button is pressed, the system initiates a check for the blinking of a green light. If
the green light is blinking, it indicates that the GSM module with the model number
A7672S is functioning properly and has established a connection. Once the connection is
established, the system gathers longitude and latitude data, which is then sent to Firebase,
a cloud-based platform. In Firebase, the location data is stored and made available for
retrieval by both a mobile app and a web app. Users can access these applications to view
the current location of the buses. The mobile app provides a convenient way for users to
track the buses on their smartphones, while the web app offers a browser-based option
for accessing the same information.


![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/09e90697-c088-4c2a-baa6-adb6353df543)


CIRCUIT CONNECTIONS:

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/c3b7e0c8-3122-4b41-948b-d6676d1973d7)


FIREBASE RESULTS:

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/6069b38c-9b43-40eb-a7ec-998f2b427692)


WEB APPLICATION RESULTS:

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/a458a8f7-41a1-49a6-b914-329646b53262)

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/791dc58b-97de-484c-8d6b-291eb8232048)

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/b90cb642-edba-483b-9512-5a72ec67fc1d)

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/a779bf8e-7193-4185-8dd5-ff6e3017cbc3)

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/1f7573aa-2304-4094-bc88-428a7dd585e2)


MOBILE APPLICATION RESULTS:

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/49c10412-aeed-4dc3-bf60-24cd75cb45b4)

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/de1f3b1e-70ad-4d38-b5b8-3f675cb6228e)

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/eac3b8d0-f5ea-4f92-9456-359a35d2be8d)

![image](https://github.com/sahana14ankad/Location-Monitoring-System-for-KLETECH-Buses/assets/136897959/672456d9-a218-48ed-b1b6-79b8534cd189)


CONCLUSION:

The location monitoring system aims to automate the process of recording GPS-based
locations for KLETECH buses. Each bus will be equipped with an IoT device , which
will periodically send the location coordinates to realtime firebase database. The system
provides real-time access to the location of any bus at any given time. To facilitate data
management and analysis, a web and mobile application is developed which serves as a
platform for storing, analyzing, and reporting the collected data.The proposed system
will contribute to streamlining operations, enhancing accountability, and improving the
overall effectiveness of KLETECH’s bus services through automated GPS-based location
recording and comprehensive data analytics.


FUTURE SCOPE: 

The Internet of Things(IoT) is a growing technology that is being used more and more
around the world. It allows us to have a more in-depth understanding of other cloud-based
applications, as well as to develop enhanced solutions using technologies such as touch
less sensing devices. The system can be improved by adding more features such as
calculating the approximate distance of the bus from bus stop, by adding sensors like
pressure sensor,vibration sensor so that the necessary actions could be taken by admin to
prevent accidents and many more.
