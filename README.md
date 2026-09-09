# Privacy Policy

**App Name:** Currency Converter Trip  
**Package Name:** `com.mike.currencyconvertertrip`  
**Developer:** mug  
**Contact:** miike47508@gmail.com  
**Effective Date:** September 10, 2026

Currency Converter Trip (“the App”, “we”, “us”, or “our”) respects your privacy. This Privacy Policy explains what information is processed when you use the App, why it is processed, and your choices.

This policy is written to match the App’s current Android permissions, in-app features, and Google Play Data safety disclosures.

---

## 1. Permissions the App uses

The App’s own Android manifest declares:

- `ACCESS_COARSE_LOCATION` — approximate location only (not precise / GPS-fine location)
- `CAMERA` — price-tag scanning
- `INTERNET` and `ACCESS_NETWORK_STATE` — exchange rates, ads, billing, geocoding
- `com.android.vending.BILLING` — in-app purchases
- `SYSTEM_ALERT_WINDOW`, `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE`, `WAKE_LOCK`, `RECEIVE_BOOT_COMPLETED` — optional lock-screen calculator launch that you turn on in settings

The App does **not** declare or use:

- `ACCESS_FINE_LOCATION` (precise location)
- `READ_MEDIA_IMAGES` / `READ_MEDIA_VIDEO` (broad photo or video library access)
- user accounts or login

Third-party libraries merged into the Android app may also add:

- Advertising ID permissions (`AD_ID`) used by Google Mobile Ads (AdMob)
- `RECORD_AUDIO` pulled in by the camera library. The App initializes the camera with audio disabled (`enableAudio: false`) and does **not** record sound. We do not use the microphone.

---

## 2. Information we process

### A. Approximate location

**App feature (optional)**  
- Permission: `ACCESS_COARSE_LOCATION` only.  
- Purpose: On first setup, if you tap “use current location,” the App reads an approximate position, converts it to a country via on-device/platform geocoding, and suggests a home currency.  
- You can skip this and pick a currency from the list. Denying location permission does not block the rest of the App.  
- We do **not** store latitude/longitude. Only the chosen currency code and your other app settings stay on the device.  
- We do **not** use precise location.

**Advertising (AdMob)**  
- The Google Mobile Ads SDK may estimate approximate location from IP address, and may use location-related signals when ads are shown.  
- This can be collected and shared by AdMob for advertising, analytics, and fraud prevention, as described in Google’s policies.

### B. Camera (`CAMERA`)

- Purpose: Price scanning. The camera captures a still image so on-device OCR (ML Kit) can read a price.  
- Images are processed on the device for that feature. We do **not** upload camera images or videos to our own servers.  
- Audio is not recorded.

### C. Advertising (AdMob)

When ads are shown (banner, interstitial, rewarded, and native ads in the free experience), the Google Mobile Ads SDK may automatically collect and share:

- approximate location (including from IP)
- app interactions (for example app launch, taps, ad/video views)
- diagnostics (for example launch time, hang rate, energy use)
- crash-related / stability diagnostics
- device or other IDs (Android advertising ID, app set ID)

AdMob uses this for advertising, analytics, and fraud prevention. Details: [Google Mobile Ads data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure) and [Google Privacy Policy](https://policies.google.com/privacy).

You can buy in-app products that remove banner and interstitial ads. Rewarded ads for extra price-scanner uses may still be available unless your purchase unlocks unlimited scanning.

### D. In-app purchases (`BILLING`)

- Google Play processes payment. We do not collect or store full payment card numbers.  
- The App asks Play whether a purchase is valid and stores entitlement flags locally (for example ad removal, unlimited scanner, lock-screen launch) so features stay unlocked.

### E. Lock-screen launch (optional)

- Used only if you enable lock-screen calculator launch (premium).  
- May use overlay permission, a special-use foreground service, boot completed, and wake lock so the calculator can open when the screen turns on while locked.  
- These capabilities are off unless you turn the feature on.

### F. Network and exchange rates

- The App uses HTTPS to fetch exchange rates (including our rate endpoint) and to talk to Google Play, AdMob, and platform geocoding as needed.

### G. Data stored on your device

Stored locally (for example SharedPreferences), not uploaded to our own servers as an account profile:

- selected currencies, language, theme, calculator settings
- travel expense records you enter
- purchase / premium flags
- lock-screen settings

### H. User-initiated sharing

If you use share/export (for example a travel expense summary), the content you choose is sent only to the app you pick. We do not share that content automatically.

### I. What we do not process as a developer account

- No user accounts, no developer-operated login  
- No precise location  
- We do not sell your personal data  
- We do not collect photos or videos as a stored media library

---

## 3. How this maps to Google Play Data safety

The Play Store Data safety section for this App currently discloses:

**Collected and shared (mainly via AdMob, except as noted):**

| Data type | Collection purposes | Sharing purposes |
|-----------|---------------------|------------------|
| Approximate location | App functionality (optional GPS currency suggestion), analytics, advertising, fraud prevention | Analytics, advertising, fraud prevention |
| Crash logs | Analytics, fraud prevention | Analytics, fraud prevention |
| Diagnostics | Analytics, fraud prevention | Analytics, fraud prevention |
| App interactions | Analytics, advertising, fraud prevention | Analytics, advertising, fraud prevention |
| Device or other IDs | Analytics, advertising, fraud prevention | Analytics, advertising, fraud prevention |

Approximate location used to suggest currency is an App feature. Approximate location used for ads is processed by AdMob, not stored by us as a location history.

---

## 4. Third-party services

- **Google Mobile Ads (AdMob)** — ads  
- **Google Play Billing** — purchases  
- **Platform location / geocoding** — country from approximate location when you request it  
- **Exchange-rate API** — conversion rates over HTTPS  

Those parties process data under their own policies, including [Google’s Privacy Policy](https://policies.google.com/privacy).

---

## 5. Data sharing

We do not sell your personal data.

Data may leave the device when:

- AdMob serves ads (see section 2.C)
- Google Play handles billing
- you use location-based currency suggestion (geocoding)
- the App fetches exchange rates
- you explicitly share content to another app
- the law requires it

---

## 6. Data retention and deletion

- **On-device App data** stays until you clear App storage or uninstall the App.  
- **Purchases** are kept by Google Play under Google’s policies.  
- **Ads / advertising ID data** is processed by Google; you can reset or delete your advertising ID in Android settings.  
- The App does **not** create a developer-side user account, so we do not operate a separate “delete my account” portal. To remove local App data, clear storage or uninstall. For questions, email miike47508@gmail.com.

---

## 7. Your choices

- Grant or revoke camera, approximate location, and overlay permissions in Android settings.  
- Skip location and pick a currency manually.  
- Limit ads via Android advertising ID controls.  
- Purchase ad removal / premium if you want fewer ads and extra features.  
- Turn lock-screen launch off in the App.

---

## 8. Children

The App is not directed at children and is not intended to knowingly collect personal data from children. If you believe a child has provided personal data through the App, contact us.

---

## 9. Security

Network requests use HTTPS/TLS where the App talks to our rate endpoint and to Google services. No method of transmission or storage is completely secure.

---

## 10. International use

The App may be used worldwide. Third parties (including Google) may process data in other countries under their policies and applicable law.

---

## 11. Changes

If we make material changes, we will update the Effective Date and publish the revised policy at this URL.

---

## 12. Contact

**mug**  
**Email:** miike47508@gmail.com
