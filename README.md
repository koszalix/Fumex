# Fumex
OpenSource fume extractor, designed for electronics laboratories

# Project repositories
[Fumex Driver](https://github.com/koszalix/fumexDriver) - Main fan controller 
[Fumex Mux](https://github.com/koszalix/fumexMux) - Additional mux, for 3 soldering station stands 
[Fumex 858]() - *Comming soon* - Detection for Zhaoxin/WEP 858 rework station 

# Features
- PWM regulation from 5% to 95% 
- Reverse polarity and over voltage protection
- Up to 2A fan can be supported 
- Soldering iron put down detection 
- 12V fans support 

# Using Fumex standalone
To use Fumex standalone, just connect power supply, power switch and fan as presented at following diagram, you can 
also add power indication led if you wish (the 680R resistor is embeded on the Fumex board).

![Fumex standalone connection diagram](standalone_connection.jpg)

Now you can use potentiometer to regulate fan speed. Enjoy! 

# Using Fumex with soldering station 



# Sugested mechanical design
The Fumex board is designed for [Kradex Z5] case, also cable managments cutsouts are avaialable on boards. 
Proposed mechanical design is presented on picture bellow. 
