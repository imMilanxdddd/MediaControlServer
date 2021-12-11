# MediaControlServer
because calling WinRT API from win32 app is pain in the ass

## What / Why
This basicly creates a websockets server that sends info when you change song in your favourite player. I really hate this execution, but I couldnt find easier method to call GlobalSystemMediaTransportControlsSessionManager from outside od UWP.
