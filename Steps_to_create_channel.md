IoT-Based Monitoring using ThingSpeak 
To enable remote monitoring, the system is integrated with ThingSpeak to transmit real
time moisture, humidity, and temperature data to the cloud. 
Steps to Create a Channel on ThingSpeak and Send Data from MATLAB 
1. Create a ThingSpeak Account 
• Sign up at ThingSpeak and log in. 
2. Create a New Channel 
• Go to "Channels" → "New Channel." 
• Name your channel (e.g., "Smart Irrigation Data"). 
• Add three fields: 
o Field 1: Moisture Level 
o Field 2: Humidity 
o Field 3: Temperature 
• Click "Save Channel." 
3.Get API Keys 
• Navigate to the "API Keys" tab in your channel settings. 
• Note down the Write API Key (to send data) and Read API Key (to retrieve data). 
4 Send Data from MATLAB to ThingSpeak 
5.Read Data from ThingSpeak in MATLAB 
