![Logo](ic_launcher.png)

## Bloodriders Pages: Controller's Guide

The app is designed to make life simpler for bloodrunners without making extra work for controllers. In fact, most of the time, controller's shouldn't be able to tell whether bloodrunners are using the app or not.

### General Functionality

The app:
- reminds bloodrunners to report for duty at the correct time (where appropriate).
- helps bloodrunners conform to correct messaging formats, auto-populating timestamps and mileage, etc.

The app generates messages according to a template but the user is encouraged to edit the messages before sending - to preserve the human touch between bloodrunner and controller.

### Traffic info

The app provides traffic information tailored to the bloodrunner (sourced from Highways England) but it does not propose any routes or diversions.

### Location Send

The app allows the user to send their current location to their controller. The controller will receive a message in the following format:

Dave Roxburgh -- LOCATION: 51.4682, -0.0934 Accuracy: 2m, Time: 20:42 -- [https://www.google.com/maps/search/?api=1&query=51.4682,-0.0934](https://www.google.com/maps/search/?api=1&query=51.4682,-0.0934) -- Disclaimer: Location data unverified.

### Tracker

The app includes a feature called the Tracker. It tracks the user and if they stop somewhere unexpected (i.e. not at a hand-over, hospital, etc.) and do not respond to alerts, their location is automatically sent to their controller. Tracker messages are formatted as follows:

Dave Roxburgh -- TRACKER: This device appears to have been stationary for 10 minutes. Location: 51.4682, -0.0934 Accuracy: 2m, Time: 20:42 -- [https://www.google.com/maps/search/?api=1&query=51.4682,-0.0934](https://www.google.com/maps/search/?api=1&query=51.4682,-0.0934) -- Disclaimer: Location data unverified.

### Controller Requirements

It is important to note that none of the functionality requires the controller to have either the Bloodriders app or an Android phone. The messages are all sent by SMS (text) message and the links in the Location/Tracker messages can be viewed on any machine (smartphone/laptop/desktop) with an Internet connection and a browser (or in Google Maps, if installed).<BR>
(Click on the links in the examples above to see exactly what you'll see if you receive a Location Send/Tracker message)

[Main Page](https://roxburd.github.io/bloodriders/)
