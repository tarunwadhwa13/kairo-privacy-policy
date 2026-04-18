# Kairo Privacy Policy

*Last Updated: 18/04/2026*

Welcome to Kairo. We built this app to help you create magical, serendipitous moments with the people you care about. We believe that an invisible connection shouldn't come at the cost of your digital privacy.

Because of how Kairo is built, our privacy policy is very simple: What happens on your phone, stays on your phone.

### 1. The Data We DO NOT Collect
Kairo is a completely offline experience. Because we do not have central servers or cloud databases, we physically cannot collect, sell, or share your data.

No GPS or Location Tracking: Kairo does not know where you are in the world. We do not track your coordinates, and we do not plot you on a map.

No Cloud Storage: We do not store your profile, your connections, or your encounter history on the internet.

No Analytics or Ad Tracking: We do not use third-party trackers to monitor how you use the app, and we never sell your data to advertisers (because we don't have any of your data to begin with).

### 2. The Data Stored on Your Device
To make Kairo work, the app needs to save a small amount of data locally on your own phone.

Your Kairo ID: When you install the app, your phone generates a randomized, unique code (a UUID). This acts as your digital identity. It is stored securely on your device using Android's encrypted storage.

Your "Known Friends" List: When you scan someone else's Kairo QR code, their unique ID is saved to a private database directly on your phone.

Encounter History: To prevent the app from constantly buzzing when you are already hanging out with a friend, Kairo temporarily logs the time of your last connection. This log stays on your device.

You have complete control over this data. If you delete Kairo from your phone, your ID, your connections, and your encounter history are permanently destroyed.

### 3. How We Use Bluetooth
Kairo uses Bluetooth Low Energy (BLE) to detect when your friends are nearby.

Broadcasting: Your app silently broadcasts your unique Kairo ID into the immediate area (~100 meters). This ID does not contain your name, phone number, or any personally identifiable information. To a stranger's phone, it looks like random noise.

Scanning: Your app listens for the unique IDs of the people you have explicitly added to your "Known Friends" list.

### 4. Why We Ask for "Location" Permissions
If we don't track your location, why does Android ask you to grant Kairo "Location" permissions?
It is a quirk of the Android operating system. Historically, Bluetooth could be used by malicious apps to guess your location by scanning for nearby public Wi-Fi routers or beacons. Because of this, Android requires any app that uses Bluetooth scanning to ask for Location permissions.
We promise that Kairo only uses this permission to operate the Bluetooth radio. We do not access your GPS hardware. Furthermore, Kairo explicitly requests zero internet permissions, meaning it is impossible for the app to send data off your device.

### 5. Security
We protect your local data using Android's EncryptedSharedPreferences. This ensures that other apps on your phone cannot read your Kairo ID or see who you are connected to. However, the security of this data also relies on the security of your device. We recommend keeping a lock screen (PIN, fingerprint, or face scan) active on your phone.

### 6. Children's Privacy
Because Kairo does not collect personal information or transmit data over the internet, there is no risk of a child's data being collected by us. However, as an app that facilitates real-world proximity alerts, we recommend that parents guide their children on only exchanging Kairo codes with trusted real-life friends.

### 7. Changes to This Policy
If we ever add new features that change how Kairo handles data, we will update this policy and notify you within the app before those changes take effect.

### 8. Contact Us
If you have any questions about this privacy policy or how Kairo works under the hood, we’d love to hear from you.  
Email: tarunwadhwa.tech@gmail.com
