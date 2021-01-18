![Logo](ic_launcher.png)

## Bloodriders Pages: Controller's Guide

The app is designed to make life simpler for bloodrunners without making extra work for controllers. In fact, most of the time, controller's shouldn't be able to tell whether bloodrunners are using the app or not.

### Functionality:

The app:
- reminds bloodrunners to report for duty at the correct time (where appropriate).
- helps bloodrunners conform to correct messaging formats, auto-populating timestamps and mileage, etc.

The app generates messages according to a template but the user is encouraged to edit the messages before sending - to preserve the human touch between bloodrunner and controller.

The app provides traffic information tailored to the bloodrunner (sourced from Highways England) but it does not propose any routes or diversions.

The app allows the user to send their current location to their controller. The controller will receive a message in the following format:

    <Bloodrunner's name> -- LOCATION: <lat>, <long> Accuracy: <acc>m, Time: <time> -- https://www.google.com/maps/search/?api=1&query=<lat>,<long> -- Disclaimer: Location data unverified.
    
    Clickable example:
	Dave Roxburgh -- LOCATION: 52.0568662, 1.1961801 Accuracy: 2m, Time: 20:42 -- [https://www.google.com/maps/search/?api=1&query=52.0568662,1.1961801](https://www.google.com/maps/search/?api=1&query=52.0568662,1.1961801) -- Disclaimer: Location data unverified.

The app includes a feature called the Tracker. It tracks the user and if they stop somewhere unexpected (i.e. not at a hand-over, hospital, etc.) and do not respond to alerts, their location is automatically sent to their controller. Tracker messages are formatted as follows:

    <Bloodrunner's name> -- TRACKER: This device appears to have been stationary for <mins> minutes. Location: <lat>, <long> Accuracy: <acc>m, Time: HH:mm -- https://www.google.com/maps/search/?api=1&query=<lat>,<long> -- Disclaimer: Location data unverified.
	
	Clickable example:
	Dave Roxburgh -- TRACKER: This device appears to have been stationary for 10 minutes. Location: 52.0568662, 1.1961801 Accuracy: 2m, Time: 20:42 -- [https://www.google.com/maps/search/?api=1&query=52.0568662,1.1961801](https://www.google.com/maps/search/?api=1&query=52.0568662,1.1961801) -- Disclaimer: Location data unverified.

It is important to note that none of the functionality requires the Controller to have either the Bloodriders app or an Android phone. The messages are all sent by SMS (text) message and the links in the Location/Tracker messages can be viewed on any machine with an Internet connection and a browser (or in Google Maps, if installed).
(Click on one of the 'clickable examples' above to see exactly what you'll see if you receive a Location/Tracker message)

[Main Page](https://roxburd.github.io/bloodriders/)
