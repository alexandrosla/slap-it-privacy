# Privacy Policy for Slap It! - Physical Pranks & Slap It! Pro - Physical Pranks

**Last Updated:** April 2026

This Privacy Policy applies to the mobile applications "Slap It! - Physical Pranks" and "Slap It! Pro - Physical Pranks" (hereinafter referred to as "the App"), created by ThinkQuack. "ThinkQuack" represents the independent development team behind the App.

We built the App as a Commercial ad-free app. This SERVICE is provided by the Developer and is intended for use as is.

Our Privacy Policy is simple: **We do not collect, encrypt, transmit, or share any of your personal data.**

---

### 1. Essential Diagnostics (Crashlytics)
For all users, the App utilizes Firebase Crashlytics to collect anonymous technical data when the App crashes. This data includes information such as device model, OS version, and the technical reason for the crash. We use this information solely to maintain the stability and performance of the Service. No personally identifiable information (PII) is collected or shared through this service.

### 2. Optional Product Improvement (Analytics)
In the "Pro" version of the App, users may choose to opt-in to anonymous usage analytics (Firebase Analytics). If you provide consent, we collect high-level data about which features are used most frequently (e.g., favorite categories or sound selections). This helps us prioritize which new sounds and features to build next. You can toggle this setting ON or OFF at any time in the App Settings.

### 2. Device Sensors (Accelerometer)
The core "Slap Engine" functionality of the App requires real-time access to your device's built-in Accelerometer (Motion Sensor).
- **No storage or transmission:** The raw sensor coordinates (X, Y, Z data) are processed instantly in memory during runtime and are **immediately discarded**. 
- **100% Offline Processing:** The core Slap Engine and sound library are designed to work entirely without an internet connection. None of your real-time sensor data or audio events are ever saved or transmitted off your device.

### 3. Foreground Service
To allow the motion sensor to detect impacts while the phone screen is locked or the device is in your pocket, the App utilizes an Android "Foreground Service" (indicated by a persistent notification). This service only runs when you explicitly click "Start" and completely terminates when you click "Stop". It is strictly used to keep the audio-playback engine awake and does not track your background activity.

### 4. Storage & Audio Files (Custom Audio Import)
The App requests local file permission functionality specifically to allow you to import your own custom audio (`.mp3` or `.wav` files) into the soundboard library.
- When you import a file, the App simply clones the audio file into its secure internal app cache so it can be played back efficiently. 
- The App **does not scan, read, or upload** any other files, photos, or documents on your storage drive.

### 5. Camera & Flashlight
The App utilizes the Camera Flash module to create rapid strobe-light effects (if you enable the Flashlight plugin). It does not take photos, record video, or access the camera lens data under any circumstances.

### 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time if Android policy requirements change. Since the app does not collect user data, we cannot notify you individually. You are advised to review this page periodically for any changes.

### 7. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at: **thinkquack.apps@gmail.com**
