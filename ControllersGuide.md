![Logo](ic_launcher.png)

## Bloodriders Pages: Controller's Guide

The app is designed to make life simpler for bloodrunners without making extra work for controllers. In fact, most of the time, controller's shouldn't be able to tell whether bloodrunners are using the app or not.

### General Functionality

The app:
- reminds bloodrunners to report for duty at the correct time (where appropriate).
- helps bloodrunners conform to correct messaging formats, auto-populating timestamps and mileage, etc.

The app generates messages according to a template but the user is encouraged to edit the messages before sending - to preserve the human touch between bloodrunner and controller.

### Traffic Info

The app provides traffic information tailored to the bloodrunner (sourced from Highways England) but it does not propose any routes or diversions.

### Location Send

The app allows the user to send their current location to their controller. If Alex sends their location (unedited) the controller will receive a message like this by SMS (text):

Alex -- LOCATION: 54.7198, -2.3478 Accuracy: 2m, Time: 20:42 -- [https://www.google.com/maps/search/?api=1&query=54.7198,-2.3478](https://www.google.com/maps/search/?api=1&query=54.7198,-2.3478) -- Disclaimer: Location data unverified.

### Tracker

The app includes a feature called the Tracker. It tracks the user and if they stop somewhere unexpected (i.e. not at a hand-over, hospital, etc.) and do not respond to alerts, their location is automatically sent to their controller. If Alex stops and is unresponsive, the Tracker will send a message like this by SMS (text):

Alex -- TRACKER: This device appears to have been stationary for 10 minutes. Location: 54.7198, -2.3478 Accuracy: 2m, Time: 20:42 -- [https://www.google.com/maps/search/?api=1&query=54.7198,-2.3478](https://www.google.com/maps/search/?api=1&query=54.7198,-2.3478) -- Disclaimer: Location data unverified.

### Controller Requirements

Crucially, none of the functionality requires the controller to have either the Bloodriders app or an Android phone... or even a smartphone. The messages are all sent by SMS (text) message and the links in the Location/Tracker messages can be viewed on any machine (smartphone/laptop/desktop) with an Internet connection and a browser.<BR>
(Click on the links in the examples above to see exactly what you'll see if you receive a Location Send/Tracker message)

### Privacy

Privacy is covered in the [Privacy Policy](https://roxburd.github.io/bloodriders/privacy). The app employs best practice to keep all data-at-rest and data-in-transit safe and secure, and compliant with all applicable rules, regulations and laws, including GDPR.

[Main Page](https://roxburd.github.io/bloodriders/)
