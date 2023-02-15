# DAPNETNotifier
Forward DAPNET messages to notification services

---

This Python script will poll the DAPNET API and forward any new DAPNET Messages you receive to APRS

The original script this was based off of scraped the Pi-Star dashboard and forwarded any messages to APRS for notitfication as a message there. I modified the script to send it to services that could be used on a phone and instead of scraping the dashboard, it utilizes the DAPNET API.

---

## Supported Services

This script will push a notification to the following services:

 -APRS
