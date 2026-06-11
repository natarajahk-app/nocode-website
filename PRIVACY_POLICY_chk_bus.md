# Privacy Policy

**Effective Date:** June 11, 2026

This Privacy Policy describes how **Challakere Bus Mitra** ("we", "our", or "us") collects, uses, stores, and shares information when you use our mobile application (the "App") and the services we provide.

By using the App, you agree to the collection and use of information in accordance with this policy.

---

## 1. Overview of Our App
Challakere Bus Mitra is a utility application designed to help commuters in and around Challakere find accurate schedules for both **KSRTC (State Transit)** and **Private Bus Operators**. 

We offer two modes of usage:
*   **Passenger Mode (General Users):** Allows you to search routes, view timetables, and call bus operators/agents to verify schedules. No registration is required.
*   **Agent / Operator Mode:** Restricted to authorized bus operators and their representatives who authenticate to manage and update bus schedules.

---

## 2. Information Collection and Use

### A. General Passengers (Commuters)
We prioritize your privacy. If you are a passenger using the App to search for timetables:
*   **No Personal Information Collected:** We do not require you to register, sign up, or provide any personal details (such as name, email, or phone number) to search or view timetables.
*   **Location Preferences:** The App allows you to set location preferences (State, District, Place) to display relevant localized schedules. 
    *   This preference is configured manually by you or via approximate selection.
    *   **Crucial Privacy Note:** This data is saved **locally on your device** using `SharedPreferences`. It is **never** uploaded to our servers, shared with third parties, or used for tracking your physical movements.
*   **Calling Feature:** The App displays phone numbers of bus agents/operators so you can easily contact them. When you tap to call, the App utilizes your device's native dialer (via `url_launcher`). We do not access, collect, or store your call history, contact list, or call duration.

### B. Bus Agents & Operators
For authorized users who log in to update bus timetables:
*   **Authentication Data:** We collect basic profile details when you sign in via **Firebase Authentication** or **Google Sign-In**:
    *   User ID (UID)
    *   Email address
    *   Display Name (or email prefix)
*   **Schedule Contribution Data:** Any schedules, timings, operator names, and route details you submit are uploaded and stored in our Firebase database to display to passengers.
*   **Agent Contact Details:** Your display name and operator phone number may be visible in the App to passengers so they can reach out to you directly for departure inquiries.

---

## 3. Third-Party Services
To provide dynamic schedules and authentication features, we utilize third-party services. These services may collect information used to identify you. 

Below are the links to the privacy policies of the third-party service providers used by the App:
*   **Google Play Services:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
*   **Firebase Authentication & Databases:** [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
*   **Google Sign-In:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 4. Cookies and Device Storage
*   We do not use cookies to track user behavior.
*   We use standard local storage (`SharedPreferences`) on your device to store user preferences such as your default location search settings and UI theme choices (light/dark mode).

---

## 5. Data Security
We value your trust in providing us your information. We use industry-standard Firebase security rules and authentication methods to prevent unauthorized access to schedule databases. However, please remember that no method of transmission over the internet, or method of electronic storage, is 100% secure and reliable, and we cannot guarantee its absolute security.

---

## 6. Children's Privacy
Our App does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact us so that we can perform the necessary actions to remove it.

---

## 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top of this document.

---

## 8. Contact Us
If you have any questions or suggestions regarding our Privacy Policy, do not hesitate to contact us at:

*   **Email:** [natarajahk.app@gmail.com]
*   **Developer Info:** Challakere Bus Mitra Team
