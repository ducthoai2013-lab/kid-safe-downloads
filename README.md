# kid-safe-downloads

Binary-only distribution mirror for KidGuard release files (no source code).
Used so phone/browser downloads and in-app updates are served via GitHub's CDN instead of the origin VPS.

The website's download page (d100radar.com/kid-safe/tai-ung-dung) is the ONLY place that links to these files; its releases.json decides which version is current.

Current:
- kidguard-parent-1.1.4.apk - parent app (Android)
- kidguard-student-1.1.2.apk - student app (Android), also what the in-app update downloads
- kidguard-windows-1.1.2.zip - Windows installer package (installer GUI + service + helper), unsigned
- kidguard-windows-service-1.1.2.exe - the Windows agent service alone, what the silent auto-update downloads
- kidguard-windows-service-1.1.0.exe - kept until the 1.1.1 update row is registered

Older versions are removed once the website points at the new one (history keeps them).
