Domoticz - The easy way
If you are running Debian-based flavours of Linux on your Pi, like Raspbian and Ubuntu, installing Domoticz is easy. Just open a terminal window and execute this command.


sudo curl -L install.domoticz.com | sudo bash


Just point your browser to the IP address of your Raspberry Pi, and use port 8080. From your Pi's browser you could surf to http://127.0.0.1:8080.

[Note: If you receive certificate error messages, you could also try executing sudo curl -L -k install.domoticz.com | sudo bash. This will download Domoticz through an unsecure (http instead of https) connection.

