# Release policy

This repository is the planned public source and release destination for the
free Datanamix Fingerprint SDKs. It is **not yet a customer-release source
mirror**. Until a versioned source tree and approved release are present, do
not treat development artifacts or third-party mirrors as supported downloads.

Planned channels are npm for browser capture and optional React UI, and Maven
for Android. Windows setup and .NET packaging have separate deployment gates;
production Windows signing is deferred until Datanamix has its signing
certificate. Linux and Apple are deferred.

A release must bind package bytes to a reviewed source snapshot and include
SHA-256 checksums, corresponding source, component notices, release notes,
upgrade guidance, and tested device/OS/browser limitations. Package-only
onboarding and deployment checks must pass. Historical reader-test evidence
stays attached to the exact build tested; packaging does not imply a reader was
recertified.

Apache-2.0 applies to independent Datanamix-owned code. LGPL-derived U.are.U
4500 modules, NBIS, and other components retain their own terms. A
component-by-component redistribution review is required before any source or
package publication. The capture SDK requires no activation key or capture fee;
use of Datanamix APIs is governed separately by API terms.

No release is approved or published merely by appearing in a local build or
review dossier. The release owner must explicitly approve the exact version,
source commit, package hashes, notices, and distribution channels.
