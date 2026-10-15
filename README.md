# SoundCloud WebApp for Ubuntu Touch

An experimental, unofficial SoundCloud WebApp for Ubuntu Touch, built using Clickable and the Ubuntu Touch WebApp Container.

**Project status:** Experimental – community testing and contributions welcome.

## Tested environment

- Device: Fairphone 4
- Operating system: Ubuntu Touch 24.04-2.0
- Development environment: Linux Mint
- Build tool: Clickable 8.10
- WebApp version: 1.0.0

## Working features

- SoundCloud website loads successfully
- User login and session cookies
- Music playback
- Background playback with an App Suspension exception
- Playback with the screen switched off
- Playback while using other applications
- Lock-screen media controls
- Bluetooth headset media controls

## Known issues and limitations

### Mobile SoundCloud website

SoundCloud frequently prompts users to install the Android application.

Some tracks cannot be played in the mobile web interface and display a message indicating that the track is unavailable on mobile devices.

### Desktop website

Testing with the desktop version enabled in the Morph browser showed a different user interface and allowed playback of tracks that were unavailable in the mobile interface.

Configuring the WebApp to consistently use the desktop website remains an open development task.

### Background playback

Ubuntu Touch may suspend the WebApp when the screen is switched off or the user switches to another application.

During testing on the Fairphone 4, disabling App Suspension for SoundCloud using UT Tweak Tool allowed background playback to continue.

This setting is not automatically configured by the application package.

## Building

Install Clickable and run:

```bash
clickable build
```

The resulting `.click` package can be installed on a compatible Ubuntu Touch device.

## Community contributions

Feedback, bug reports, testing results and pull requests are welcome.

Areas for further investigation include:

- Desktop browser identification
- Improved mobile usability
- Background playback behavior
- Compatibility with other Ubuntu Touch devices
- SoundCloud website restrictions

Please use GitHub Issues to share your experiences.

## Disclaimer

This is an independent, unofficial community project. It is not affiliated with, endorsed by, or maintained by SoundCloud.

SoundCloud is a trademark of its respective owner.








