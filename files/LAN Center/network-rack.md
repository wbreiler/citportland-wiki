# The Network Rack
![the all mighty networking rack](https://media.giphy.com/media/3hRzIz4D8Ikgg/giphy.gif)
## The Hardware
1. 1x Cisco 1921 Router ([Documentation](#Documentation/cisco-1921.pdf))
    * How to access: 
        * Option 1: Open a web browser and go to [`http://10.10.10.1/`](http://10.10.10.1) and log in as `cisco` with a password of `CITPortland` 
        * Option 2: Open Terminal (Linux/MacOS) or Command Prompt (Windows) and type in the following command: `telnet 10.10.10.1` and use the password of `CITPortland`
2. 1x HP 1820-24G Switch ([Documentation](#Documentation/hpe-1820-series.pdf))
    * How to access:
        * Option 1: 
        * Option 2:
3. 1x HP 1820-8G Switch ([Documentation](#Documentation/hpe-1820-series.pdf))
    * How to access:
        * Option 1:
        * Option 2:

## View network stats
If you're a data lover, you can head on over to [`http://10.10.10.x:3000`](http://10.10.10.:3000) and login with a username of `grafana` and a password of `CITPortland`. Once logged in, you'll see a whole host of information from interface throughput to uptime of each switch and the router.