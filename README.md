# kid-safe-downloads

Binary-only distribution mirror for KidGuard release files (no source code).
Used so phone/browser downloads and in-app updates are served via GitHub's CDN instead of the origin VPS.

Current (1.1.0):
- kidguard-parent-1.1.0.apk - parent app (Android)
- kidguard-student-1.1.0.apk - student app (Android), also what the in-app update downloads
- kidguard-windows-1.1.0.zip - Windows installer package (installer GUI + service + helper), unsigned
- kidguard-windows-service-1.1.0.exe - the Windows agent service alone, what the silent auto-update downloads

Older versions are removed once the website points at the new one (history keeps them).