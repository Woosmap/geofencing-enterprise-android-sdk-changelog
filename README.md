# Woosmap Geofencing SDK Change Log

All changes to Woosmap Geofencing Enterprise Android SDK are documented here.


## `v4.3.1` - May 16, 2024 
![version](https://img.shields.io/badge/version-latest-brightgreen)

### Fixed
- 🐛 Newly added `refreshPOIs` method does not work as expected when no listener is passed in the parameters.


## `v4.3.0` - May 14, 2024
### Added
- ✨ Exposed method `refreshPOIs` which takes the last MovingPosition from the database. Fetches POIs for this location and updates the POI table with the latest POI information.


## `v4.2.0` - May 7, 2024
### Added
- 🚀 Upgraded third-party dependencies
- 🚀 Upgraded AGP version

### Removed
- ❌ Removed AltBeacon library dependency


## `v4.1.4` - Mar 13, 2024
### Fixed
- 🐛 Custom Tracking does not work if `profileReadyListener` is not set.


## `v4.1.3` - Mar 6, 2024
### Removed
- 🔒 Remove sensitive permissions from the SDK Manifest file.


## `v4.1.2` - Feb 12, 2024
### Fixed
- 🐛 Add exception handlers and test case to prevent crashes.


## `v4.1.1` - Jan 4, 2024
### Fixed
- 🐛 SDK Crashes when `types` attribute in assets has `string` and not `array`


## `v4.1.0` - Dec 12, 2023
### Added
- ✨ Send broadcast when geofence entry/exit events are triggered.


## `v4.0.7` - Oct 31, 2023
### Fixed
- 🐛 SDK Crashes when `types` attribute in assets has `string` and not `array`.


## `v4.0.6` - Oct 25, 2023
### Fixed
- 🐛 SDK Logger causing crash in React Native Plugin.


## `v4.0.5` - Oct 4, 2023
### Fixed
- 🐛 Modify beacon storage and retrieval policy.


## `v4.0.3` - Sep 21, 2023
### Added
- 🚀 Implement logging in Geofencing Enterprise Android SDK.


## `v4.0.2` - Sep 13, 2023
### Added
- 🚀 Exposed new field `userProperties` in POI table to store asset's custom properties.

### Fixed
- 🐛 SHA1 Fingerprint not being set in the API requests.


## `v4.0.1` - Aug 18, 2023
### Fixed
- 🐛 Enterprise SDK 4.0.0 is using core_beta2.23 version of the core SDK.


## `v4.0.0` - Aug 16, 2023
### Added
- 🎉 Introduced `beaconTracking` profile to track beacons inside Woosmap Indoor venues.


## `v3.0.12` - Aug 3, 2023
### Added
- 🚀 Minifying the Geofencing Android SDK.


## `v3.0.11` - Jun 15, 2023
### Added
- 🚀 Upgrade Google Play Services dependency libraries


## `v3.0.10` - May 19, 2023
### Added
- 🚀 Upgrade AndroidX Work Runtime.


## `v3.0.8` - May 2, 2023
### Added
- 🚀 Replace requests to Traffic by requests to Distance API in the Geofencing Enterprise SDK.


## `v3.0.7` - Apr 25, 2023
### Fixed
- 🐛 Client app crashes due to the `org.json` dependency.


## `v3.0.7` - Apr 25, 2023
### Fixed
- 🐛 Client app crashes due to the `org.json` dependency.


## `v3.0.6` - Apr 6, 2023
### Added
- 🚀 Adding origin/source in the header of Search API and Distance API request.


## `v3.0.3` - Mar 20, 2023
### Fixed
- 🐛 `populateStoreDetail` was returning empty SearchAPIResponseItem object instead of null object.


<!-- 
## [1.0.1] - 2024-05-21 
![version](https://img.shields.io/badge/version-latest-brightgreen)
### Fixed
- 🐛 Fixed a minor display issue on the settings page.
- 🛠️ Corrected typos in the help documentation.

## [1.0.0] - 2024-05-20
### Added
- 🎉 Initial release of the application.
- 👤 User registration and login functionality.
- 📊 Basic dashboard with key metrics.
- 🔧 Profile management features.
 -->

<!-- 

🎉 Major release

🚀 Minor release

🐛 Patch release

✨ Added features

🛠️ Bug fixes

🔒 Security updates

⚠️ Deprecated features

❌ Removed features
 -->
