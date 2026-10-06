# UpSnap

A simple **Wake on LAN** web app written with SvelteKit, Go and PocketBase.

## Features
- Add devices by MAC address and power them on with one click
- Network scan (nmap) to discover devices
- Online/offline status via ping
- Scheduled wake-ups (cron)
- Wake over Wake-on-LAN magic packets

## Notes for this install
- Runs with `network_mode: host` so the magic packet reaches your LAN.
- The device you want to wake must have **Wake-on-LAN enabled in its BIOS and network card**.
- Default web port: **8090**.

Source: https://github.com/seriousm4x/UpSnap
