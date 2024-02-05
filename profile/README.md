# Cuckoo Authenticator

<img src="https://github.com/cuckoo-authenticator/.github/assets/8351121/096d909f-2088-4a9c-afbd-b753e237d457" width="200">
<img src="https://github.com/cuckoo-authenticator/.github/assets/8351121/0200090d-ec21-4b3c-b820-4caaebe86921" width="200">
<img src="https://github.com/cuckoo-authenticator/.github/assets/8351121/3fc66203-4fc1-4299-af19-86422fbccd21" width="200">
<img src="https://github.com/cuckoo-authenticator/.github/assets/8351121/b04b543a-5652-4d8a-94a3-1506ac41a2b4" width="200">

## Introduction

Cuckoo Authenticator is an open source and self hosted Time-Based One-Time Password (TOTP) manager.

It consists of a server and clients components. It is designed to maintain end-to-end encryption between its components and follows ”[zero-knowledge](https://en.m.wikipedia.org/wiki/Zero-knowledge_service)” (aka no-knowledge or zero access) principle.

## Server

Server component is written in Go and its source code is available here https://github.com/cuckoo-authenticator/server under AGPL-3.0 license. Docker image is available here https://hub.docker.com/repository/docker/serhiylunak/cuckoo/general.

## Clients

There is a client available for iOS platform and I am currently using it on a daily basis. Its source code is not available yet. I will be registering Apple Developer account and publishing the app on its App Store under [TestFlight](https://developer.apple.com/testflight/) program.

Apps for other platforms are planned with the following priority order: Android, Chrome Browser Extension.

# Contribution

I would love to understand if there is any interest in this self hosted TOTP solution. Please leave your opinion [here](https://github.com/orgs/cuckoo-authenticator/discussions/1).

