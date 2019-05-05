# webbleMQ
## Web Bluetooth relay for devices supporting Nordic UART service, Puck.js in particular

[Application is running here](https://tasm-devil.github.io/webbleMQ/)

Designed primarily for use with Circuitpython. Each device has own publish and subscribe topic. 

Note MQTT uses my private MQTT broker - mqtt.fadenstrahl.de and the data is public. If you fork the repo, please change the broker to one of your choosing and do not use mine.

Authentication is necessary if you run this on a https server like github.io

## Enable web-bluetooth in google chrome

Read [this article](https://github.com/WebBluetoothCG/web-bluetooth/blob/master/implementation-status.md) for getting infos on how to enable web-bluetooth in google chrome or simply open `chrome://flags/#enable-experimental-web-platform-features` and choose *Enabled*.

## Mosquitto setup
This is the perfect [tutorial](https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-the-mosquitto-mqtt-messaging-broker-on-ubuntu-18-04-quickstart) how to setup mosquitto with wss and certbot (*Let's Encrypt*)

## Roadmap
- Write a Circuitpython-module for MQTT over BLE.
- switch to [Eclipse Paho Javascript client](https://www.eclipse.org/paho/clients/js/) because mosquitto.js is [deprecated](https://mosquitto.org/blog/2013/05/mosquitto-javascript-client-deprecated/).

## Contributions
Are welcome!

## License 
MIT

