# Privacy Policy for Slap It! & Slap It! Pro

**Last Updated:** April 2026

This Privacy Policy applies to the mobile applications "Slap It! - Physical Soundboard" and "Slap It! Pro - Soundboard" (hereinafter referred to as "the App"), created by ThinkQuack Team. "The Developer" (also referred to as "we" or "ThinkQuack Team") represents the independent development team behind the App.

### 1. Essential Diagnostics (Crashlytics)
For all users, the App utilizes Firebase Crashlytics to collect anonymous technical data when the App crashes. This data includes information such as device model, OS version, and the technical reason for the crash. We use this information solely to maintain the stability and performance of the Service. No personally identifiable information (PII) is collected or shared through this service.

### 2. Optional Product Improvement (Analytics)
In the "Pro" version of the App, users may choose to opt-in to anonymous usage analytics (Firebase Analytics). If you provide consent, we collect high-level data about which features are used most frequently (e.g., favorite categories or sound selections). This helps us prioritize which new sounds and features to build next. You can toggle this setting ON or OFF at any time in the App Settings.

### 3. Device Sensors (Accelerometer)
The core "Slap Engine" functionality of the App requires real-time access to your device's built-in Accelerometer (Motion Sensor).
- **How it is used:** The App actively calculates the physical acceleration forces applied to the device to detect physical strikes or "slaps".
- **No storage or transmission:** The raw sensor coordinates (X, Y, Z data) are processed instantly in memory during runtime and are **immediately discarded**. They are never saved, tracked, or transmitted off your device.

### 4. Background Service
To allow the motion sensor to detect impacts while the phone screen is locked or the device is in your pocket, the App utilizes an Android "Foreground Service" (indicated by a persistent notification). This service only runs when you explicitly click "Start" and completely terminates when you click "Stop". It is strictly used to keep the audio-playback engine awake and does not track your background activity.

### 5. Storage & Audio Files (Custom Audio Import)
The App requests local file permission functionality specifically to allow you to import your own custom audio (`.mp3` or `.wav` files) into the soundboard library.
- When you import a file, the App simply clones the audio file into its secure internal app cache so it can be played back efficiently. 
- The App **does not scan, read, or upload** any other files, photos, or documents on your storage drive.

### 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time if Android policy requirements change. Since the app does not collect user data, we cannot notify you individually. You are advised to review this page periodically for any changes.

### 7. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at: **[Insert Your Developer Email Here]**
