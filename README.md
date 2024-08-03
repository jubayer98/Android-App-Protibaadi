# Protibaadi Android App

Protibaadi is an innovative Android application designed to enhance women's safety in public places. Unlike traditional safety apps, Protibaadi integrates with a discreet portable device, allowing for emergency alerts without needing to visibly use a smartphone, which can escalate dangerous situations.

## Overview

**Device and Connection:**
- The system includes a portable device hidden inside a pouch that can be worn or attached to a bag.
- It utilizes a **HC-05 Bluetooth module** connected to an Android app to enable remote activation.

**Hardware Components:**
- Small Breadboard
- 555 Timer
- HC-05 Bluetooth Module
- Male to Male Jumper Wires
- 100nF Capacitor
- 10K Trimmer Potentiometer
- A Switch
- 9V Battery

## Application Features

- **Database Integration:** Uses SQLite3 for storing and updating emergency contact numbers effortlessly.
- **Connection Verification:** Confirms the hardware connection and GPS functionality to ensure the system's reliability.
- **Emergency Messaging:** Upon pressing the hardware device switch, it sends an emergency text to a predefined contact with the user’s current location after a 20-second interval.
- **Social Media Integration:** Automatically posts an emergency status on the user's Facebook account with location details. This status is updated at set intervals.
- **User Control:** Allows the user to stop sending messages and posting updates via a stop button in the app.
- **Location Sharing:** Shares the GPS location through a Google Maps URL, making it easy to locate the user.

## Usage Scenario

In a situation where a user feels threatened, they can discreetly press the switch on the Protibaadi device. This action triggers the app to send an emergency SMS and update their Facebook status with their location, helping to alert both personal contacts and broader social networks without escalating the situation by visibly using a phone.

This app provides a practical solution that empowers users to seek help discreetly in emergencies, leveraging modern technology to enhance personal safety. This concept not only adds an essential layer of security but also uses common digital platforms to ensure a rapid response in critical situations.
