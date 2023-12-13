# MMNetwork
MMNetwork is designed to control the microcontroller WiFi chip, connecting to our network that will enable further functionality.
We designed this for our physical target/blaster so it can be controlled by our server/target shooting game. It provides a communication link between server and client(the microcontroller).
It includes authentication support and currently using plain simple TCP as it's transport.

> Future Roadmap:
> - Implement a better messaging protocol that doesn't rely on line break
> - Use JSON as message
> - Optimise the library by changing String to char*

> Dependencies:
> - Implement a better messaging protocol that doesn't rely on line break
> - Use JSON as message
> - Optimise the library by changing String to char*

## Note
This is designed for RP2040 using Arduino-Pico and ESP32
