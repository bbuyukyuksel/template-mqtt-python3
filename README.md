# Python3 - MQTT Publish and Subscribe Template



## MQTT Broker

For linux systems

```bash
sudo apt-get install mosquitto
```

For windows systems

download from: https://mosquitto.org/download/



## mqtt_sub.py

Subscribe a topic to listen message



## mqtt_pub.py

Publish a message with a topic



## Windows CLI Example

### Start Server

```bash
>> cd C:\Program Files\mosquitto
>> mosquitto.exe -p 1883
```

 

### Subscripe

```bash
>> cd C:\Program Files\mosquitto
>> mosquitto_sub -d -L mqtt://peresthayal:123456@127.0.0.1:1883/home/test -v
```



### Publish

```bash
>> cd C:\Program Files\mosquitto
>> mosquitto_pub -d -L mqtt://peresthayal:123456@127.0.0.1:1883/home/test -m "TEST"
```









