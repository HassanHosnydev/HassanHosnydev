# BlueBus / TripTech driver app

A React Native application used by drivers for job-order workflows, distributed directly as an Android APK.

## My contribution

I worked on the Expo application foundation, including navigation, authentication state, and the API layer. The repository contains login and job-order screens, with Expo Router handling navigation.

The documented authentication flow restores a token from Expo Secure Store into Zustand and directs the user to login or the job-order area. The project uses TanStack Query and Axios for API data, NativeWind for styling, and React Hook Form with Zod for forms. Its dependencies also include camera and image-picker support; installed dependencies alone do not establish a completed feature.

## Selected implementation history

| Date | Reference | Contribution recorded under HassanHosnydev |
| --- | --- | --- |
| 9 June 2026 | [03d6ff1](https://github.com/TripTech-com-eg/driver-app/commit/03d6ff17487bb436d0a0da9a2f07c7706fe23d8e) | Expo app foundation, auth flow, API layer, and login/job-order screens. Cursor is recorded as a co-author. The commit summary and implementation documentation were reviewed. |
| 23 June 2026 | [602b2cb](https://github.com/TripTech-com-eg/driver-app/commit/602b2cbca0178a8c745d842437733cd9d4eaa707) | Dependency updates and an asset-generation script, as recorded in the commit history. |

## Release and usage

Drivers use the application in their day-to-day work. Android builds are distributed directly as APK files rather than through an app store. This deployment information is provided by me as the developer; the Git references above document the selected implementation changes, not a usage audit or a store listing.

The code review covered the documented app foundation and selected contribution history. It was not a review of every later release or every driver workflow.

## Source access

The source repository is private. Commit references require authorized access and may return 404 for public visitors. No application source, tokens, or internal API addresses are reproduced here.
