# Introduction

**What is IoT?**&#x20;

The Internet of Things (IoT) describes the network of physical objects“things”that are embedded with sensors, software, and other technologies for the purpose of connecting and exchanging data.

* IoT involves extending Internet connectivity beyond standard devices, such as desktops, laptops, smartphones and tablets to any range of traditionally dumb or non-internet-enabled physical devices and everyday objects.
* Embedded with technology, these devices can communicate and interact over the Internet, and they can be remotely monitored and controlled. https://youtu.be/LlhmzVL5bm8

**Main components of IoT :**

1. Sensors/Devices - First, sensors or devices collect data from their environment. This data could be as simple as a temperature reading or as complex as a full video feed.
2. Connectivity/Cloud - That collected data is sent to a cloud infrastructure but it needs a medium for transport. Connecting things to sensors/devices has many options like bluetooth, satellite, cellular, ethernet, etc.
3. Data Processing - Once the data is collected and it gets to the cloud, the software performs processing on the acquired data. This could be very simple, such as checking that the temperature reading is within an acceptable range. Or it could also be very complex, such as using computer vision on video to identify objects.
4. User Interface - The information is made useful to the end-user in some way. This could be via an alert to the user (email, text, notification, etc).&#x20;

`For example, a text alert when the temperature is too high.`

**IoT Architecture :**

Perception Layer - Sensors that gather information about the environment (heat sensor, pressure sensor, Blood Pressure Sensor, etc.) Transport Layer - Transfer the sensor data through network (Wi-Fi, Bluetooth, ...) Processing Layer - Stores, processes, analyses data (cloud computing, big data, ...) Application Layer - Delivering application specific services to the user

**Advantages of IoT :**

1. Minimize human effort
2. Save time
3. Enhanced data collection - Information is easily accessible
4. Improved Securtiy
5. Efficient resource utilization: If we know the functionality and the way that how each device work we definitely increase the efficient resource utilization as well as monitor natural resources.

**Disadvantages of IoT :**

1. Security issues
2. Privacy Concern
3. Increased Unemployment
4. High Dependency on the internet
5. Reduced mental and physical activity

**Some challenges in IoT**

* Lack of security
* Vulnerable interfaces
* Physical security risk
* Lack of vendor support
* Difficult of update firmware and OS

**Shodan :**&#x20;

We will use shodan website to find that device connected to the internet, it can be anything camera, routers, web servers etc. Shodan is same like google the only differnce is google will find websites and shodan will find devices.

**Some Shodan commands :**&#x20;

\#camera has\_screenshot:true - For finding those camera who doesn't have any authentication.

**Default Passwords for routers/devices :**

* A default password is a password supplied by the manufacturer with new equipment (e.g. switches, hubs, routers) that is password protected.
* Attackers use default passwords in the list of words or dictionary that they use to perform password guessing attack.

**Online tools to Search Default Passwords**

* http://cirt.net
* http://default-password.info
* http://www.routerpasswords.com
