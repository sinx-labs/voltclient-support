# Volt Client Privacy Policy

Effective date: July 10, 2026

Volt Client is designed as a local-first Visual Studio Code extension.

## Data collection

Volt Client does not include telemetry or analytics and does not require a Volt Client account. SINX Labs does not operate a service that receives request collections, environment variables, request contents, authentication values, or response contents from the extension.

## Request traffic

When a user sends a request, Volt Client sends it directly from the Visual Studio Code extension host to the destination selected by the user. The destination service, network provider, proxy, operating system, Visual Studio Code, or other software involved in that connection may process data under its own terms and privacy policy.

## Local storage

Volt Client stores collections, requests, environments, and related settings locally using the storage mode selected by the user:

- **Global State** stores extension data in Visual Studio Code's extension storage.
- **File** stores data in the configured workspace JSON file, such as `.volt/collections.json`.

Request data may include URLs, parameters, headers, cookies, bodies, API keys, bearer tokens, usernames, and passwords. These values are stored with the request data and are not moved into an operating-system keychain. In file storage mode, they may be written to the configured JSON file.

Users are responsible for protecting, reviewing, backing up, redacting, and deleting their local data. Files containing secrets should not be committed to source control or shared without review.

## Support information

Information submitted through this repository's Issues or Discussions is processed by GitHub under GitHub's applicable terms and privacy statement. Do not include secrets or confidential request data in public reports.

## Changes

Material changes to this policy will be documented in this repository. The effective date above will be updated when appropriate.

## Contact

For privacy questions that do not contain sensitive information, open an issue in this repository. Do not report credentials or confidential data in a public issue.
