# DoorButler

Created to automate my intercom doorbell system.

Intent is to have a Pi and relays detect the buzzer and operate the door according to one of two modes.

Mode one: Notification is made (Either Echo, sound played through Sonos or some local hardware buzzer/lights) and response sought to open door or not.

Mode two: No notification takes place (but event is logged) and door is automatically triggered after a short delay.

Expectation is to have an http interface with simple endpoints to control the door, respond to notifications, change mode and display a list of recent events.
