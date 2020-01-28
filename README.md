# Torchlight Nativescript

This is a template project for mobile app development using NativeScript.

## Goals

* Well documented
* Effective workflow
* Publish to iOS/Android

### Inspiration

These are some example projects that demonstrate what we are going for in terms of documentation/completeness.

[Crema App - Web](https://github.com/cremalab/crema-app-web)

# Tools Used

* NativeScript
* How will we test?
* ESLint
* Mocha
* Prettier
* TypeScript

# Setup

Install node dependencies:

```
npm i
```

# Run in Dev

```
tns preview
```

[tns preview](https://docs.nativescript.org/tooling/docs-cli/project/testing/preview#tns-preview) will compile the app, upload it to `https://play.nativescript.org/s/{app-id}`, and render a QR code that you can scan with the NativeScript Playground App.  Playground is just a QR code reader, it will open the app in NativeScript Preview.

If the app is unable to hot reload (e.g. your screen went to sleep after inactivity) you can reconnect by closing the Preview app, then returning to the Playground app, finding the link to your app in the history, and clicking on that.  The Preview app will re-open, and the HMR connection should be re-established.

# Structure

# Best Practices
