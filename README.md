// IP Records

A progressive web app (PWA) for storing and looking up IP addresses from your phone. It works offline and installs to your home screen.

Live app: https://TaleOfTwoCities.github.io/IP-records

// Features
- Add, edit and delete records (IP address, name, type, status, notes)
- IPv4 and IPv6 validation, with duplicate detection
- Search and filter by status
- One-tap copy of an address
- CSV export (copied to clipboard)
- Installable and works offline
- Light and dark mode

// Installation
- iPhone (Safari): Share → Add to Home Screen
- Android (Chrome): Browser menu → Add to Home screen

// Built with
Vanilla JavaScript, HTML and CSS, `localStorage`, a web app manifest and a service worker. No frameworks or build step.

// Known limitations
- Records are stored locally in the browser, so they aren't shared across devices
- No import yet, so CSV export can't be restored
- Clearing browser data deletes the records

 // Roadmap
-  JSON export/import for backups
-  Persistent storage request
-  Subnet/CIDR details per record
-  Cloud sync
