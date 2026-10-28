# Task 23: The Smart Home Privacy Problem
  Name: Shubojeet Mondal

## Overview

For this task, I looked into the privacy and security issues of setting up a basic smart home. The scenario involves a family using four common devices: a connected door lock, a smart camera, a voice assistant, and a smart TV. Below is my breakdown of what data these devices collect, the risks involved, and my prioritized plan to lock them down.

## 1. Device-Risk Matrix

| Smart Device | What Data It Collects | Main Privacy & Security Risks | Updates & Settings | 
| ----- | ----- | ----- | ----- | 
| **Connected Door Lock** | Times of entry/exit, PIN codes, user profiles. | **High Risk:** If hacked, someone could literally unlock the front door. Unpatched software leaves the house wide open to attacks. | Needs automatic updates turned on. A physical key backup is necessary if the battery dies. | 
| **Smart Camera** | Live video and audio of the home, timestamps. | **High Risk:** Strangers guessing the password to watch the live feed. Video clips leaking from insecure cloud storage. | Keep firmware updated. Settings usually allow saving video to a local SD card instead of the cloud. | 
| **Voice Assistant** | Voice clips, search queries, daily routines. | **Medium Risk:** The device might mishear the wake word and record private conversations. App companies sometimes let humans review these clips. | Most apps let you opt out of human review and delete history, but you have to go looking for the settings. | 
| **Smart TV** | Viewing habits, app usage, IP address. | **Medium Risk:** The TV tracks what you watch specifically to sell that data to advertisers. | TVs usually stop getting security patches after a few years. Tracking is turned on by default. | 

## 2. Prioritized Mitigation Plan

I organized this plan starting with the most urgent threats (physical break-ins and camera spying) down to the less urgent ones (data tracking).

### Phase 1: High Priority (Physical Safety & Cameras)

* **Split the Wi-Fi:** Put all smart home gadgets on a separate "Guest" Wi-Fi network. If the TV gets hacked, the attacker can't use it to access the family's personal laptops.

* **Secure the Door Lock:** Turn on automatic firmware updates. Give each family member their own unique PIN instead of sharing one, so you can track exactly who is coming and going.

* **Lock Down the Camera:** Change the default password immediately. You must turn on Two-Factor Authentication (2FA) for the camera's mobile app. Turn off cloud storage and use a local SD card to prevent online leaks.

### Phase 2: Medium Priority (Everyday Privacy)

* **Manage the Voice Assistant:** Get in the habit of pressing the physical "mute" button on the device during sensitive conversations. Go into the companion app and turn off the setting that allows human review of audio clips.

* **Restrict the Smart TV:** When setting up the TV, say "No" to any optional privacy tracking agreements. Go into the TV settings and turn off "Automatic Content Recognition" (ACR) so it stops spying on what is playing on the screen.

### Phase 3: Low Priority (Long-Term Maintenance)

* **Manual Checks:** Set a calendar reminder every 6 months to check if the camera or TV needs a manual software update.

* **End of Life:** If a manufacturer stops sending security updates for an older device, disconnect it from the Wi-Fi. The risk of keeping an unpatched device on the network isn't worth it.

## Conclusion

Bringing smart devices into a home definitely makes life easier, but it also means putting microphones and cameras into private spaces. You can't just plug these things in and forget about them. By taking the time to change default passwords, turn off unnecessary tracking, and split the Wi-Fi network, a family can secure their home and protect their data without giving up the convenience.
