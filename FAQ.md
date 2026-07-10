# Frequently Asked Questions

## Where does Volt Client store my data?

By default, Volt Client uses Visual Studio Code Global State. File storage mode writes shareable data to the configured workspace file, which defaults to `.volt/collections.json`.

## Does Volt Client upload my collections?

No. Volt Client does not include a Volt Client cloud sync service, telemetry, or analytics. HTTP requests are sent directly to the destination you specify.

## Can I commit `.volt/collections.json` to Git?

Yes, but inspect it first. Requests and environments can contain API keys, tokens, passwords, cookies, private URLs, and request bodies. Remove sensitive values before committing or sharing the file.

## Are secrets stored in an operating-system keychain?

No. Authentication values are currently stored with request data. Treat the selected storage location as sensitive.

## Which VS Code versions are supported?

Volt Client requires Visual Studio Code 1.92.0 or later.

## How do I report a problem?

Use the bug report form in this repository. Include the Volt Client version, VS Code version, operating system, storage mode, reproduction steps, and expected behavior. Redact all sensitive information.

## Where is the source code?

Volt Client is proprietary software. This repository contains public support materials and documentation, not the extension source code.
