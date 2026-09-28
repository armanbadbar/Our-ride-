# Our Ride — Android APK build from a phone

## Easiest route: Expo EAS

1. Create/sign in to an Expo account.
2. Put this project folder in a GitHub repository, or upload it to a computer/online Git workspace.
3. Install/use EAS CLI where you can run Node commands:
   `npm install -g eas-cli`
4. In the project folder run:
   `npm install`
5. Sign in:
   `eas login`
6. Configure the project:
   `eas build:configure`
7. Create an installable APK:
   `eas build -p android --profile preview`
8. When the build finishes, open the build page and download the APK to the Android phone.

## Important
- This project is a demo/prototype. OTP is demo-only (`123456`).
- Live GPS/maps, real OTP/SMS, driver matching, backend and production payment verification still need server/API setup.
- UPI ID can be entered later in Profile → UPI ID. A UPI ID alone is not a payment gateway.
