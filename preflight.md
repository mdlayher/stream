# preflight

Matt's preflight checklist for streaming.

## Social media

- 2-3 hours before stream, advertise on:
  - Twitter
  - Gophers Slack
    - #networking
    - #performance
  - Optional: Facebook, text, etc.

## Physical setup

- Desk/computer
  - YubiKey ready
  - Receiver on
  - Speakers off
  - Audio interface phantom on
  - Headphone amp on
  - Light on
  - Trackball clean
- Phone charging, vibrate only
- Self
  - Use bathroom!
  - Socks/slippers/hoodie ready
  - Water bottle full

## Computer setup

- Center monitor
  - Disable webcam autofocus:
    - `sudo v4l2-ctl -c focus_auto=0`
  - Disable GNOME notifications
  - Close Thunderbird
  - Primary workspace:
    - VSCode with project, size 22 font
    - Terminal in project directory, Presentation profile
  - Secondary workspace:
    - Chrome with guest profile
      - Zoom 200%
      - Logged in on GitHub
      - Optional: GoDoc, other sites
- Right monitor
  - Chrome with personal profile
    - Twitch Stream Manager: https://dashboard.twitch.tv/u/mdlayher/stream-manager
      - Set stream title/category
      - Stream audio muted
      - Set project:
        - `!commands edit !project https://github.com/mdlayher/modemmanager`
    - Gophers Slack
    - Twitter
- Left monitor
  - OBS, preview enabled
    - Intro scene
    - Mic unmuted, PC output muted
    - Banner text up to date with stream title
  - OBS multiview

## Start of stream

- Start streaming on OBS
  - Intro scene
  - Mic unmuted, PC output muted
- Social media rounds:
  - Twitter
  - Gophers Slack
    - #networking
    - #performance
    - #general
