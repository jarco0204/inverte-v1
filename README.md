# InVerte's Main Submodule Repo

## Landing-Page
• Goal is to create a digital image of this startup.
• Has Google analytics embedded to it.

## API-Server
• Express.js-based REST API
• Socket.io for webSocket communication

## Client
• React-based Web App.
• MVP for InVerte

## Analytics
• Machine Learning Models used for analytics service.
• Weight fluctuation data.

## IoT-Scale
• Firmware for ESP32.
• AWS IoT Core Connection

# How to work with Repo?

## Cloning
• Assumes access to all repos: 
 git clone --recursive https://github.com/jarco0204/inverte
 
• If forgetten to add -r flag, then:
 git submodule update --init --recursive
 
## Fetch
 • git submodule update --remote
 • Explanation: Any new commit to a remote individual repo is fetched.
 
## Commit 
 • git status
 • git add . 
 • git commit -m "AreaOfDevelopment: Change"
 • git push
 
 
 
 

