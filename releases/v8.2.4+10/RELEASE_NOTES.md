# Release v8.2.4+10

- Version name: 8.2.4
- Version code: 10
- Release date: 2026-05-13 (Asia/Ho_Chi_Minh)

## APK Assets

- yacht_cruise-v8.2.4+10-arm64-v8a.apk
- yacht_cruise-v8.2.4+10-armeabi-v7a.apk
- yacht_cruise-v8.2.4+10-universal.apk

## Notes

### Changes since 34aab95c (exclusive) to HEAD

- [End User] Refactor booking payment result logic to rely exclusively on payment status (a416655)
- [End User] Refactor owner information section in booking detail screen (5c15cdf)
- [End User] Refactor yacht booking payment logic to use API-driven deposit values (2fe31e3)
- [End User] Refactor booking activity display and improve payment gateway exit logic (9fa80eb)
- [End User] Implement centralized API DateTime parsing utility and refactor models (e20bff4)
- Update WORKING_AGREEMENT.md to establish standards for API datetime normalization (9df4d29)
- [End User] Implement month scrolling and improve initial month loading in yacht booking calendar (31d0233)
- Refine `PrimaryButton` interaction and disabled state styling (e1a5499)
- [End User] Implement complaint request status and refine booking detail actions (e50484d)
- [End User] Implement pull-to-refresh for booking history and booking detail screens (ee97351)
- [End User] Implement human-readable booking codes in booking management (e3c9fdc)
- [End User] Simplify pending request banners in booking details (968d86b)
- [End User] Implement and integrate `AppLoadingIndicator2` in booking details (04de022)
- [End User] Implement and integrate `AppLoadingIndicator2` in booking details (896644a)
- [End User] Refine yacht booking calendar UI and selection persistence (1d3d020)
- [End User] Refactor yacht booking duration and departure time widgets for consistent disabled states (64d69ec)
- [Tooling] Enhance `release_apk.sh` with automated release notes management and improved branch handling (52619f3)
