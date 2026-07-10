# Volt Client Support

Volt Client is a lightweight, local-first REST API client for Visual Studio Code.

This public repository is the support and documentation home for Volt Client. The extension source code is maintained separately and is not published in this repository.

## Get Volt Client

Volt Client will be available from the Visual Studio Marketplace as `sinx-labs.volt-api-client`.

## Support

- [Report a bug](https://github.com/sinx-labs/voltclient-support/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/sinx-labs/voltclient-support/issues/new?template=feature_request.yml)
- [Read the FAQ](FAQ.md)
- [View the roadmap](ROADMAP.md)
- [Review the changelog](CHANGELOG.md)

Before opening an issue, remove API keys, tokens, passwords, cookies, private URLs, request bodies, and other sensitive information from screenshots and logs.

## Privacy and local data

Volt Client does not require an account and does not include telemetry or analytics. Requests are sent directly from the VS Code extension host to endpoints selected by the user.

Request data can contain authentication values and other secrets. In file storage mode, these values may be written to `.volt/collections.json`. Review and redact the file before committing or sharing it. See the [Privacy Policy](PRIVACY.md) for details.

## License

Volt Client is proprietary software. Personal use and internal business use are permitted under the [Volt Client End User License Agreement](LICENSE).
