# AI Firewall — Trial releases

This repository is **only for downloading trial builds** of AI Firewall, the data-loss-prevention agent for organisations whose staff use AI assistants. It holds no source code — it exists to host the trial installers.

## Download

**[Go to the releases →](https://github.com/ScienceSoft-Endpoint-AI-Firewall/trial-releases/releases)**

Open the newest release at the top to install the latest version, or pick an earlier one if you need a specific version. Every published version stays available.

| Platform | File to download |
|---|---|
| macOS (Apple silicon) | `AI-Firewall-Trial-<version>-arm64.dmg` (drag to Applications) or `.pkg` (installer) |
| Windows (64-bit) | `AI-Firewall-Trial-<version>-x64.exe` |

Versions with a suffix such as `-alpha` are early pre-release builds.

## Check your download

Each release carries a `SHA256SUMS.txt`. Compare the checksum of the file you downloaded with the matching line:

```
shasum -a 256 <file>        # macOS
certutil -hashfile <file> SHA256   # Windows
```

The installers are signed: on macOS with a Developer ID certificate and notarized by Apple, on Windows with an EV code-signing certificate.

## Getting started

On first launch the app asks for your trial **enrolment key**, which you receive in your welcome email. If you have not received one, contact your ScienceSoft representative.
