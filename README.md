# 🗂️ S3Deck: Desktop Client for S3 & S3-Compatible Storage

![S3Deck Banner](https://s3deck.app/feature_graphic.png)

<a href="https://github.com/s3deck/s3deck/releases/latest"><img src="https://img.shields.io/badge/macOS-Download-a78bfa?style=for-the-badge&logo=apple&logoColor=white" alt="Download for macOS" height="32"></a>
<a href="https://github.com/s3deck/s3deck/releases/latest"><img src="https://img.shields.io/badge/Windows-Download-a78bfa?style=for-the-badge&logo=windows&logoColor=white" alt="Download for Windows" height="32"></a>
<a href="https://github.com/s3deck/s3deck/releases/latest"><img src="https://img.shields.io/badge/Linux-Download-a78bfa?style=for-the-badge&logo=linux&logoColor=white" alt="Download for Linux" height="32"></a>

Welcome to the official public repository for **S3Deck**!
*Note: This repository does not contain the application source code. It serves as a centralized hub for our users to download the app, report issues, and request new features.*

## 📖 About S3Deck

**S3Deck** is a fast desktop client for AWS S3 and every S3-compatible storage — Cloudflare R2, MinIO, Backblaze B2, DigitalOcean Spaces, Wasabi, Ceph and any custom endpoint. Browse, transfer, sync and migrate your buckets, and manage bucket settings without ever opening a web console.

### ✨ Key Features

* **Two-Pane File Manager**: Local on the left, bucket on the right. Drag files and folders across, or switch to a single pane with an object inspector.
* **Robust Transfer Engine**: Parallel multipart uploads, auto-resume after dropped connections, bandwidth limits, and checksum verification.
* **Visual Bucket Settings**: Bucket policy JSON editor with validation and plain-language explanations, CORS rule builder, lifecycle rules, versioning, ACLs, tags and access logging.
* **Two-Way Folder Sync**: Pair a local folder with a bucket prefix and resolve conflicts file by file — keep local or keep remote.
* **Cross-Provider Migration**: Move a whole bucket between providers (e.g. AWS S3 → Cloudflare R2), with pause, continue and cancel.
* **One-Click Sharing**: Presigned URLs with custom expiry, public/private toggles, version history with restore, and CloudFront invalidations.

### 🔒 Security-First Architecture

* **Zero Middlemen**: S3Deck connects **directly** from your computer to your storage endpoint. Your files and credentials *never* pass through any third-party server.
* **OS Keychain Storage**: Secret access keys are stored in the system credential store (Keychain on macOS, Credential Manager on Windows, Secret Service on Linux) — never in a plain config file.
* **Read-Only Mode**: Mark production connections read-only to block every delete and overwrite.

---

## 🤝 Feedback, Bug Reports & Feature Requests

We want to build the best S3 desktop experience for you. If you encounter any issues or have ideas to improve S3Deck, we want to hear them!

1. **Bug Reports**: Found a glitch or something isn't working right? Please [open a Bug Report](https://github.com/s3deck/s3deck/issues/new?template=bug_report.md).
2. **Feature Requests**: Have an idea that would make S3Deck even better? Please [submit a Feature Request](https://github.com/s3deck/s3deck/issues/new?template=feature_request.md).
3. **General Questions**: Feel free to open an issue or reach out to our support.

*Before opening a new issue, please search the [existing issues](https://github.com/s3deck/s3deck/issues) to see if it has already been reported.*

---

## 📩 Support & Contact

If you need private support or have business inquiries, you can reach out to us at:
📧 **Email**: richardpham201@gmail.com

---

### Links
- [Website](https://s3deck.app/)
- [Help & Support](https://s3deck.app/help)
- [Sponsor](https://s3deck.app/sponsor)
- [Privacy Policy](https://s3deck.app/privacy-policy)
- [Terms of Service](https://s3deck.app/terms-of-service)
