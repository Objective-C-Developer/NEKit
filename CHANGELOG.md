# Change Log
All notable changes to this project will be documented in this file.
I will do my best to guarantee that this project adheres to [Semantic Versioning](http://semver.org/) after 1.0.0, but please do read change log before updating.

## [Unreleased]
### Changed
- The `ProxyServer.mainProxy` is removed and instead you should set the `proxyServer` in the implemention of `IPStackProtocol` (`TCPStack` as of now) which requires a proxy server to function.