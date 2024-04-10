# STW API Descriptions

The Single Trade Window (STW) API Descriptions repository
contains [OpenAPI](https://www.openapis.org/) descriptions for the reference data API.

## Setup

Run `git config core.hooksPath hooks` to configure Git hooks. The secret scanner runs on pre-push.

### Secret scanning

[TruffleHog](https://github.com/trufflesecurity/trufflehog) is used for secret scanning. It can be
installed using brew: `brew install trufflehog`.
