# Security Policy

## Supported versions

Security fixes are released for the latest version of KairoWidget. Please update to the newest release before reporting.

| Version | Supported |
|---|---|
| 1.0.x | ✅ |

## Reporting a vulnerability

**Please don't open a public issue for security problems.**

Report it privately through GitHub instead: go to the repository's **Security** tab and choose **Report a vulnerability**. Include:

- the KairoWidget version (Finder → Applications → KairoWidget → Get Info) and your macOS version;
- what you found and how to reproduce it;
- what an attacker could do with it.

You'll get an acknowledgement within 7 days. Confirmed issues are fixed in a new release, and reporters are credited in the release notes unless they prefer not to be.

## Verifying your download

Every release includes `SHA256SUMS.txt`. Check your download with:

```sh
shasum -a 256 ~/Downloads/KairoWidget-<version>.dmg
```

Only download KairoWidget from <https://github.com/atanu-app/MAC-WIDGET-Public/releases>.
