# Android fundamentals

The Android operating system is a multi-user Linux system.

An Android package, which is an archive file with an .apk suffix, contains the contents of an Android app that are required at runtime and it is the file that Android-powered devices use to install the app.

## App components

### Types of Components

* Activities.

It is the point where we can interact with the user. It represents a screen with a user interface.

* Services.

It is an entry point for keeping an app running in the background.

* Broadcast receivers.

It is a component that enables the system to deliver events/requests to the app outside of a regular user flow, allowing the app to respond to system-wide broadcast announcements.

* Content providers.

It manages a shared set of app data that you can store in the file system.

## The manifest file

The primary task of the manifest is to inform the system about the app's components.

### What the manifest file do?

* Identifies user permissions the app requires.

* Declares the minimum API Level required by the app.

* Declares hardware and software features used or required by the app.

* Declares API libraries the app needs to be linked against.

## App resources

One of the most important aspects of providing resources separate from your source code is the ability to provide alternative resources for different device configurations.

The android app requires resources that are separate from the source code, such as images, audio files, and anything relating to the visual presentation of the app.

For every resource that you include in the Android project, the SDK build tools define a unique integer ID, which you can use to reference the resource from your app code or from other resources defined in XML.
