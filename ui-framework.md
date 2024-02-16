# Architecture Decision Record: UI Framework

## Status

Proposed

## Context

A requirement for the food ordering app is to have a user-friendly interface that is easy to navigate and delivers a seamless ordering experience. For the development team to create such an interface, a decision on which UI framework to use is being proposed.

## Decision

We are proposing the use of React Native.

## Rationale

To provide cross-platform UI consistency and delivery of an app that meets the client's requirements, we have decided to use React Native as the framework. Using React Native will enhance the development of creating a user-friendly interface by:

- **Code Sharing**
  React Native is cross-platform, therefore the development team will only have to write the majority of code once. This provides more time for the developers to focus on creating a seamless ordering experience across both platforms.
- **Popularity**
  As React Native is a commonly used framework, many developers have the skills necessary to utilize the framework for creating this app. This popularity also means React Native is well documented and supported, which allows developers to leverage existing solutions.
- **Performance**
  With the wide-spread use of React Native, the framework is well optimized for delivering the performance many users expect from other apps they may use.

## Consequences

Using React Native will providing a common framework and set of components for the development team to utilize in creation of this app. The team will be able to focus less on the demands of coding for two separate platforms, giving them more time to devote to delivering on the client's requirements.

By using React Native, the team will be limited to built-in and community developed components and libraries. This will require continuous research on any updates or releases to ensure compatibility exists between the app and the updates.
