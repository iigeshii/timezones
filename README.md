# Crimson Cuckoo Coven — Time Zone Board

A single-page time zone board for the Crimson Cuckoo Coven. It shows every member's local time side by side so the group can find times that work for everyone and share event announcements.

## Features

- **Current Times** — an hour-by-hour timeline for each member, colour-coded by how reasonable the hour is for them (good / okay / bad). Step between days or jump to a date.
- **Select a time** — drag across columns to pick a time slot; click a name to hide or show that member.
- **Announcement** — turn a selected slot into a poster listing the event time in every member's time zone, then copy it as an image or download it as a PNG.

## Usage

No build step. Open `index.html` in a browser, or serve the folder with any static host (e.g. GitHub Pages).

## Adding a member

Add an entry to the `members` array in `index.html`, using an [IANA time zone name](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones):

```js
{ name: "PlayerName", timeZone: "Europe/Dublin" },
```

Comment out an entry with `//` to hide that member without deleting them.

## License

[MIT](LICENSE)
