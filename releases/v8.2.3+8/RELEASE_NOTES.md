# Release v8.2.3+8

- Version name: 8.2.3
- Version code: 8
- Release date: 2026-04-26 00:40:25 +0700

## APK Assets
- yacht_cruise-v8.2.3+8-arm64-v8a.apk
- yacht_cruise-v8.2.3+8-armeabi-v7a.apk
- yacht_cruise-v8.2.3+8-universal.apk

## Notes

# Release Notes (v8.2.1+7)

## Features
- Implemented the end-to-end yacht booking payment flow, including payment gateway and payment result screens.
- Added integration and navigation flow between payment steps and result handling.
- Updated authentication screen headers and strengthened verification logic.

## Improvements
- Improved app startup performance by deferring non-critical initialization tasks.
- Enhanced performance and state management for yacht detail comments/reviews screens.
- Refined booking details navigation and related UI structure.
- Optimized notification store behavior and related DB/UI operations.

## Fixes
- Fixed yacht detail text rendering issues (layout + locale), reducing mid-word line breaks.
- Added CMS/API text normalization (hidden chars, special spaces, irregular line breaks) for more stable display.
- Updated Vietnamese mobile phone validation and formatting logic.
- Updated UserDetailCubit to restore previous profile state on API failure.
- Adjusted avatar profile-identifier logic for more consistent user identity display.
- Refined close button styling in the payment result screen.
- Removed notification preloading from Splash to reduce unnecessary startup overhead.
- Excluded Android build ID artifacts from version control.

## Breaking Changes
- No breaking API or migration-required contract changes identified in this range.
