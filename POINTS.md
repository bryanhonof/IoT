#Exam Project
The exam project needs :
* at least 2 hardware sensors on at least 1 standalone device that collect relatable information and send this information on different intervals per sensor (e.g. temperature once every 5 minutes, light value once every 2 minutes) to the webserver (i.e. collector page). At least one of the sensors collects value information (not just boolean on/off style of information). (You bring the device and demonstrate it for 2/20)
**  Alternatively, you create a software solution that automaticly collects and generates useful information and sends this from a 24/7 running device on specific intervals (to fill the database).
* one collector page on the webserver that will registrate the information of the 2 different sensors in one MySQL table that at minimum registrates timestamp, value and sensorID. The different possible sensors are in another table that contains ID, name, last-known-timestamp and last-known-external-IP. (You show and explain the code for 4/20, the database needs at least more than 1 week of usefull information)
* "easy for the eyes" view page on the webserver that will generate the registrated information in a graph using jQuery. It contains at least the 2 information streams (i.e. lines) which can be dynamicly added or removed (using ajax). The graph is using the correct axis and combines the 2 information streams that is usefull to interprete (e.g. the 2 datalines should cross somewhere). It must be at least possible to filter the graph to only show a specific time periode (e.g. last 24h, last week). (You show and explain the code for 6/20, usefull collected information must be visible)

The additional points can be collected with self providing extra's (e.g. beautifull HTML / CSS, PHP object oriented style, security, more sensors, different hardware collectors, different graph tools, dynamic updatable table view, user registration, a