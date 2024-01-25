# Cuckoo Authenticator

Cuckoo Authenticator is an open source and self hosted Time-Based One-Time Password (TOTP) manager.

It consists of a server and clients components. It is designed to maintain end-to-end encryption between its components and follows ”[zero-knowledge](https://en.m.wikipedia.org/wiki/Zero-knowledge_service)” (aka no-knowledge or zero access) principle.

## Server

Server component is written in Go and its source code is available here https://github.com/cuckoo-authenticator/server under AGPL-3.0 license. Docker image is available here https://hub.docker.com/repository/docker/serhiylunak/cuckoo/general.

## Clients

There is a client available for iOS platform and I am currently using it on a daily basis. Its source code is not available yet. I will be registering Apple Developer account and publishing the app on its App Store under [TestFlight](https://developer.apple.com/testflight/) program.

Apps for other platforms are planned with the following priority order: Android, Chrome Browser Extension.

# Contribution

I would love to understand if there is any interest in this self hosted TOTP solution. Please let me know by opening an issue [here](https://github.com/cuckoo-authenticator/.github/issues).
