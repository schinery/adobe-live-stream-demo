# Adobe Live Stream Demo

A NodeJS application that demonstrates how to use the [Adobe Live Stream Connector](https://github.com/sleepingstu/adobe-live-stream-connector) NPM module.

<!-- MarkdownTOC -->

- [Prerequisites](#prerequisites)
- [Usage](#usage)

<!-- /MarkdownTOC -->

## Prerequisites

You will need to have the an Adobe ID and have it [linked to your Analytics account](https://marketing.adobe.com/developer/documentation/authentication-1/auth-link-account-1). You'll also have needed to have [created an application](https://marketing.adobe.com/developer/documentation/authentication-1/auth-register-app-1) to use the Live Stream.

Once this is done, copy `config.js.example` to `config.js` and enter the correct information for *clientId*, *clientSecret* and *streamUrl*. The other value should be okay to leave as default values (at the time of writing).

```sh
cp config.js.example config.js
```

## Usage

To start this demo application run:

```sh
npm start
```
Note: This will run `npm install` before starting the application.

If all is set up right you should see data being returned in the terminal window.
