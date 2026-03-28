# Privacy Policy for UPT (Upaya Peduli Tuberkulosis)

**Last Updated:** March 28, 2026

UPT (Upaya Peduli Tuberkulosis) ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we handle your information and why we require specific device permissions to ensure your medication discipline.

### 1. Information Collection and Use
UPT is designed as a **local-first** tool. We do not have a central server, and we do not collect your personal data remotely. The following information is stored **only on your device**:

*   **Primary Patient Profile:** Name, age, gender, phone number, and home address.
*   **Family Member Profile:** Name, age, gender, and treatment status (stored via `AnggotaKeluargaEntity`).
*   **Medication Category & Treatment Data:** Information regarding the medication schedule for Adult or TPT categories and times for TB treatment.
*   **Medication Schedule:** Dosage times (hour and minute), frequency (daily/weekly), and treatment start dates for family prophylaxis.
*   **Appointment Data:** Dates and times for healthcare facility visits (stored via `APPOINTMENT_DATE_TIME`).
*   **User Preferences:** Technical settings such as alarm ringtones (`ALARM_SOUND_URI`), vibration status (`VIBRATE`), reminder intervals, and theme choices (stored via Android DataStore).
   
### 2. Data Storage (Local Only)
*   **No Cloud Synchronization:** Your data never leaves your device. We use Room Database for medication records and DataStore Preferences for application settings.
*   **No Data Sharing:** Since we do not collect your data on any server, we do not share your information with any third parties.
*   **Data Deletion:** Uninstalling the app will permanently delete all stored records and settings from your device.

### 3. Device Permissions and Usage
To provide a reliable life-saving reminder service, UPT requires the following permissions as declared in our system manifest:

*   **SCHEDULE_EXACT_ALARM:** Vital for TB treatment. This ensures the alarm triggers at the **exact second** scheduled to prevent missed doses.
*   **FOREGROUND_SERVICE & SPECIAL_USE (FGS_SUBTYPE_ALARM):** Used by our `AlarmService`. This ensures the reminder system remains active and reliable even when the app is in the background.
*   **POST_NOTIFICATIONS:** To display medication alerts and reminders on your screen.
*   **USE_FULL_SCREEN_INTENT:** Allows the medication alarm to appear over the lock screen so you can see it immediately.
*   **RECEIVE_BOOT_COMPLETED:** Allows the app to automatically reschedule your medicine alarms after you restart your device.
*   **SYSTEM_ALERT_WINDOW:** Enables the reminder to appear on top of other running applications.
*   **WAKE_LOCK & turnScreenOn:** Allows the app to wake the device screen to ensure the notification is noticed.
*   **ACCESS_NOTIFICATION_POLICY:** Allows the app to override "Do Not Disturb" settings for critical medical alerts.
*   **VIBRATE:** Provides haptic feedback for reminders.

### 4. Children's Privacy
Our application is intended for individuals requiring TB medication management.
*   **No Personal Data Collection:** UPT does not knowingly collect or request any Personally Identifiable Information (PII) from children under the age of 13.
*   **Parental Guidance:** If a minor is using this app for TB treatment, we strongly encourage parents or guardians to manage the entries, as all data is stored strictly on the local device.

### 5. Security
We utilize standard Android security protocols to protect your local data from unauthorized access by other apps on your device.

### 6. Contact Us
If you have any questions about this Privacy Policy or the permissions used in UPT, please contact us at:

*   **Email:** adhisyahbana09@gmail.com
*   **Application Name:** UPT (Upaya Peduli Tuberkulosis)
*   **Institution:** Puskesmas Tanah Habang
*   ** Adreess:** Jalan Raya Lampihong KM. 20, Desa Tanah Habang Kanan, Kecamatan Lampihong, Kabupaten Balangan, Kalimantan Selatan. 

