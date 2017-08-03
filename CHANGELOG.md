# Chirp JavaScript SDK Changelog

Recent changes to the [Chirp JavaScriptSDK](http://developers.chirp.io/).

The Chirp JavaScript SDK follows [Semantic Versioning](http://semver.org/) guidelines.

## v2.0.1 (2017-07-04)
- Fix issue with Chirps that are created with JSON data that cannot be encoded or played straight after created
- Fix issue with wrong error message for `chirp` method with chirps created with JSON data.

## v2.0.0 (2017-02-10)

- Each method and class now returns promises.
- New ChirpSDK class, implements promises on each method.
- ChirpSDK.chirp do not accept string identifiers anymore, instead you have to create a Chirp instance
- ChirpSDK.setProtocolNamed now supports promises.
- New Chirp class, implements promises on each method.

## v1.1.0 (2016-10-27)

- New `setProtocolNamed` method, allowing you to select the new inaudible ultrasonic protocol.
- Deprecated 'shortcode' terminology, in favour of referring to individual chirps by their 'identifier'.
- The `Chirpjs` object has now been renamed to `ChirpSDK`

## v1.0.0 (2016-10-12)

- Initial public release
- Improvements on Chirp SDK interface.
- Removed jQuery dependency
