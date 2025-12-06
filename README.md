aviator_hack_v81 - GitHub-ready Android project (minimal)

Default configuration:
- App name: aviator hack v81
- Default top number: 01905437211 (editable via Settings)
- Login: number + password (no OTP)
- WhatsApp floating button opens chat to the configured number
- Admin Settings allow changing top-number, admin-password, and selecting grid icon from device

How to use:
1. Unzip this repo and open in Android Studio (File -> Open).
2. If gradle wrapper (gradlew) is missing, run `./gradlew wrapper` or install Gradle and sync.
3. Build -> Build APK(s) or use GitHub Actions workflow (if you add gradle wrapper and secrets).

Default admin login credentials (change after install):
- Number: 01905437211
- Password: admin123

Notes:
- The project contains minimal source code and layouts to make the APK buildable.
- If you want an automated GitHub Actions build, add the gradle wrapper files and the keystore secrets as described in the previous messages.
