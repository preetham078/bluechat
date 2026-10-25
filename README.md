# BlueChat

A Bluetooth-first Android chat app with a dark cyber/hacker-inspired UI.

## Current build
- Android 12+ Bluetooth permission handling
- Portrait-only professional dark UI
- Host / Wait and Connect flows
- Real Bluetooth RFCOMM socket messaging
- WhatsApp-style message bubbles
- Photo/video picker and document/file picker
- File transfer over the same Bluetooth socket
- Received files saved to `Downloads/BlueChat`
- File names, sizes, timestamps and connection status

## How to test
1. Install the app on two Android phones.
2. Pair the phones in Android Bluetooth settings.
3. Phone A: tap `HOST / WAIT`.
4. Phone B: tap `CONNECT` and select Phone A.
5. Send text messages.
6. Tap `+` to send a photo/video or document/file.

USB is only needed to install/run the APK from Android Studio. The chat data travels phone-to-phone over Bluetooth after connection.

## Limitations of this prototype
- One peer connection at a time.
- No end-to-end encryption beyond the Bluetooth link; do not treat this as a production secure messenger yet.
- Large transfers depend on Bluetooth speed and device limits.
- Background transfers, delivery receipts, voice/video calls, notifications, message persistence and encryption are not yet implemented.
# bluechat
