# SpeedReader Calendar Companion

Static iPhone companion for syncing the next Google Calendar event to the ESP32 SpeedReader.

Configure a Google OAuth **Web application** client ID and add the deployed GitHub Pages URL as an authorized JavaScript origin. The page requests the read-only Calendar events scope and sends only the next event's title and times to the device.
