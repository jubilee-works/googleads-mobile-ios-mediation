# MoPub Ads Mediation Adapter for Google Mobile Ads SDK for iOS

## Version 5.4.0.0
- Verifed compatibility with MoPub SDK 5.4.0.

## Version 5.3.0.2
- Remove the check that prevents ad requests for native content ad.

## Version 5.3.0.1
- Initialize MoPub and reattempt ad requests manually in the adapters for use cases that do not do so in the app.

## Version 5.3.0.0
- Verifed compatibility with MoPub SDK 5.3.0.

## Version 5.2.0.0
- Verifed compatibility with MoPub SDK 5.2.0.

## Version 5.1.0.0
- Verfied compatibility with MoPub SDK 5.1.0.

## Version 5.0.0.0
- Verified compatibility with MoPub SDK 5.0.0.

## Version 4.20.1.0
- Fixed an issue causing duplicate symbol errors when the adapter was used with
  those of other networks.
- Verified compatibility with MoPub SDK 4.20.1.

## Version 4.20.0.0
- The adapter now returns a media view for every native ad.
- Verified compatibility with MoPub SDK 4.20.0.

## Version 4.19.0.0
- Verified compatibility with MoPub SDK 4.19.0.

## Version 4.18.0.0
- Verified compatibility with MoPub SDK 4.18.0.

## Version 4.17.0.0
- Updated the deployment target to iOS 8.
- Updated the adapter to make it compatibe with MoPub SDK 4.17.0.

## Version 4.16.0.0
- The adapter now depends on `mopub-ios-sdk/Core`. MoPub SDK uses Integral Ad
  Science, Inc. (“IAS”) and Moat, Inc for reporting and viewability measurement.
  If you wish to use these libaries, they need to be added to your app
  separately. See [Disabling Viewability Measurement](https://github.com/mopub/mopub-ios-sdk#disabling-viewability-measurement)
  for more details on how to add these libraries separately.
- Verified compatibility with MoPub SDK 4.16.0.

## Version 4.15.0.0
- Verified compatibility with MoPub SDK 4.15.0.

## Version 4.14.0.0
- Verified compatibility with MoPub SDK 4.14.0.
- Removed the support for `armv7s` architecture.
- Fixed a bug where Native Ads failed to load MoPub privacy icon when MoPub SDK
  is linked using CocoaPods and having `use_frameworks!` in the Podfile for
  Swift projects.

## Version 4.13.1.1
- Fixed a bug where native ads failed to detect clicks when loaded from the same
  `GADAdLoader` instance.

## Version 4.13.1.0
- Verified compatibility with MoPub SDK 4.13.1.

## Version 4.13.0.0
- Verified compatibility with MoPub SDK 4.13.0.

## Version 4.12.0.0
- Verified compatibility with MoPub SDK 4.12.0.
- Added support for accessing MoPub native demand on Google Mobile Ads
  mediation.
- Added support to configure the privacy icon size for MoPub's native ads.
- Updated banner and interstitial ad formats per Google Mobile Ads latest
  mediation APIs.
- Adapter is now distributed as a framework.

## Previous Versions
- Support for MoPub banner and interstitial ads.
