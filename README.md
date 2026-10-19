# Adventure Editor — Windows Releases

This public repository is reserved for **compiled, approved Windows releases** of Adventure Editor. The application source code remains private in a separate repository.

**No automatic update feed is active yet.** Do not treat an installer as a verified in-app update unless its cryptographic signature and manifest have been published and tested.

Each approved release will carry:
- Versioned Windows installer (.exe)
- Tauri updater signature (.sig) and required updater bundle
- A `latest.json` manifest specifying version, platform download URL and signature
- Release notes and a previous version for recovery

The editor must verify updates with its embedded Tauri **public signing key**. The private signing key must never be committed to either repository, placed in the application, or shared in a chat. Development builds are not automatically published here.

Once operational, downloads will be available under the GitHub **Releases** section of this repository.
