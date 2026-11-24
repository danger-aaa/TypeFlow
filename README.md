# TypeFlow Android starter

Prototype Android app with a WebView UI and a user-selected Android IME.

## Build
Push this folder to a GitHub repository. The workflow in `.github/workflows/build.yml` builds a debug APK.

## First run
1. Install the APK.
2. Open TypeFlow and enter text.
3. Tap **Gunakan Keyboard TypeFlow** and enable it in Android keyboard settings.
4. Return to a text field in another app, open the keyboard picker, and choose TypeFlow.
5. Tap **Mulai** on the TypeFlow keyboard.

## Notes
- This is a starter prototype, not a production release.
- Input is user-initiated and uses Android's standard InputMethodService / InputConnection APIs.
- No stealth, anti-detection, or monitoring-bypass behavior is included.
- Android and some target apps may restrict input in particular fields.
- Test on the target Xiaomi device; OEM battery and keyboard settings can vary.
