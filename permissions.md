# Architecture Decision Record: Permissions of User's Location

## Status

Proposed

## Context

The app requires tracking of the user's location to provide a variety of key functions, such as restaurant recommendations, estimated delivery times, and more. These features require access to the user's location-based services.

Many users are reluctant to share this information, therefore it is important to set the precedent that the app understands and respects the user's privacy.

## Decision

The app will give the user the option to opt-in to the location-based service features.

## Rationale

The opt-in feature will promote user privacy. If the user opts-in to these features, GPS-based tracking in the device will be utilized to provide the user's precise location. With the user's location, the app will be able to send notifications such as nearby restaurant recommendations.

## Consequences

The development team will review the Android Developers [Request runtime permissions](https://developer.android.com/training/permissions/requesting) guidelines to ensure the app falls within these recommendations at all times.

By giving the user the option to opt-in to these services, total overall participation may be less. However, having this feature increases the app's credibility and trust.

The user interface will require a feature that prominently displays the opt-in option.
