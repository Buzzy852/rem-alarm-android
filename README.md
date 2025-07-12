# rem-alarm-android
app to find out what you were dreaming during your deepest sleep
Wake yourself at the very start of REM sleep by polling a wearable’s sleep-stage API.

## Features

- Polls Fitbit Web API (and optionally Oura) every 60 s  
- Detects sleep stages: AWAKE, LIGHT, DEEP, REM  
- Fires a gentle tone + vibration the instant REM begins  
- Configurable wake-window (5–30 minutes before set alarm)  
- Fallback alarm if no REM detected in window  
- Minimal one-screen UI with on/off toggle  
- Open-source under the MIT License  

## Getting Started

### Prerequisites

- Android Studio Arctic Fox or later  
- Android device running 8.0 (API 26)+ (emulator won’t simulate REM)  
- Fitbit Charge 6 (or compatible tracker) with a registered app in Fitbit Dev Console  
- (Optional) Oura Ring + Oura Cloud API key  

### Clone & Build

```bash

