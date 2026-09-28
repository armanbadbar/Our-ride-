# Our Ride — Final Demo Package

Cross-platform Expo app for the Our Ride local ride-booking concept.

## Included
- Customer booking flow
- Driver mode and ride lifecycle demo
- Pickup/drop selection for Narnaul, Mahendragarh, Surajgarh, Pacheri, Buhana, Badbar and Singhana
- Bike/Auto/Car fare estimate
- Ride history stored locally
- Demo OTP login (123456)
- UPI ID editable later from Profile
- UPI payment handoff (`upi://pay`) after ride completion
- Production integration placeholders for Maps/GPS, real OTP/SMS, push notifications, secure backend, driver matching and payment verification

## Run
1. Install Node.js LTS.
2. In this folder run `npm install`.
3. Run `npx expo start`.
4. Scan the QR with Expo Go, or use an Android/iOS simulator.

## Build
For installable Android/iOS builds, use Expo/EAS Build with the appropriate signing accounts. This source package does not contain private signing keys or third-party API secrets.

## UPI
Open Profile → UPI ID, enter your UPI ID (for example `name@bank`) and save it. The app creates a standard UPI payment intent for the fare. A production ride service should verify payment server-side before marking a ride paid.
