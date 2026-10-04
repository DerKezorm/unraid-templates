# Unraid Community Applications templates

Docker templates for [Unraid](https://unraid.net) Community Applications, maintained
alongside the apps themselves.

| App | Description | Source |
| --- | --- | --- |
| [Nexview](templates/nexview.xml) | Self-hosted media discovery and request dashboard for Radarr and Sonarr, with accounts, approvals, quotas and an age restriction. | [DerKezorm/nexview](https://github.com/DerKezorm/nexview) |
| [nexmail](templates/nexmail.xml) | Self-hosted email client in the browser: several IMAP mailboxes in one window, calendar over CalDAV, address books over CardDAV, one container and one SQLite file. | [DerKezorm/nexmail](https://github.com/DerKezorm/nexmail) |
| [nexdeck](templates/nexdeck.xml) | Live dashboard for the homelab: cards for Unraid, Docker, Proxmox, the media and download stack and many more services, with actions, kiosk displays and notifications. | [DerKezorm/nexdeck](https://github.com/DerKezorm/nexdeck) |
| [nexpulse](templates/nexpulse.xml) | Speed test tracker for the homelab: live gauge, schedules with random times, history, alerts and an API, measuring with Cloudflare, LibreSpeed and optionally Ookla. | [DerKezorm/nexpulse](https://github.com/DerKezorm/nexpulse) |
| [nexbeat](templates/nexbeat.xml) | Find music and request it from Lidarr: recommendations from your library, genres, MusicBrainz search, accounts with quotas and approvals. | [DerKezorm/nexbeat](https://github.com/DerKezorm/nexbeat) |
| [nextrmnl](templates/nextrmnl.xml) | SSH and SFTP in the browser: terminal with tabs and jump hosts, file transfer, a vault per account for keys and passwords, host key checks, accounts by invitation or OpenID Connect, a second factor. | [DerKezorm/nextrmnl](https://github.com/DerKezorm/nextrmnl) |
| [nexsift](templates/nexsift.xml) | The filter for your homelab's notifications: one inbox for every service, answers like Gotify, ntfy, Discord, SMTP and syslog, bundles the noise and pushes only what matters. | [DerKezorm/nexsift](https://github.com/DerKezorm/nexsift) |
| [nexcanvas](templates/nexcanvas.xml) | A whiteboard for your own server like Apple Freeform: notes, shapes, drawings and photos, edited live together, with frames, a shape library, templates and JSON Canvas. | [DerKezorm/nexcanvas](https://github.com/DerKezorm/nexcanvas) |
| [nexlore](templates/nexlore.xml) | Notes for your own server, in the browser: Markdown files on your disk, a WYSIWYG editor, wiki links and a map of all notes to zoom into, shared spaces with rights. | [DerKezorm/nexlore](https://github.com/DerKezorm/nexlore) |

## Installing from Community Applications

Open the **Apps** tab on your Unraid server, search for the app by name and click
**Install**. Nothing here needs to be downloaded by hand.

## Installing a template directly

If an app is not in Community Applications yet, you can add this repository under
**Apps → Settings → Template Repositories**:

```
https://github.com/DerKezorm/unraid-templates
```

## Reporting a problem

Template problems belong here in the [issue tracker](https://github.com/DerKezorm/unraid-templates/issues).
Problems with an app itself belong in that app's own repository: for Nexview that is
[DerKezorm/nexview/issues](https://github.com/DerKezorm/nexview/issues), for nexmail
[DerKezorm/nexmail/issues](https://github.com/DerKezorm/nexmail/issues), for nexdeck
[DerKezorm/nexdeck/issues](https://github.com/DerKezorm/nexdeck/issues), for nexpulse
[DerKezorm/nexpulse/issues](https://github.com/DerKezorm/nexpulse/issues), for nexbeat
[DerKezorm/nexbeat/issues](https://github.com/DerKezorm/nexbeat/issues), for nextrmnl
[DerKezorm/nextrmnl/issues](https://github.com/DerKezorm/nextrmnl/issues), for nexsift
[DerKezorm/nexsift/issues](https://github.com/DerKezorm/nexsift/issues), for nexcanvas
[DerKezorm/nexcanvas/issues](https://github.com/DerKezorm/nexcanvas/issues), for nexlore
[DerKezorm/nexlore/issues](https://github.com/DerKezorm/nexlore/issues).

## Licence

MIT — see [LICENSE](LICENSE).
