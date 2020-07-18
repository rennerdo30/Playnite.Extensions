# Extensions for Playnite

Collection of Extensions I created for [Playnite](https://github.com/JosefNemec/Playnite).

- [Installation](#installation)
- [Metadata Providers](#metadata-providers)
  - [DLSite](#dlsite)
  - [F95Zone](#f95zone)
  - [VNDB](#vndb)
- [Troubleshooting](#troubleshooting)

## Installation

1) Get the latest Release from the [Release Tab](https://github.com/erri120/Playnite.Extensions/releases/).
2) Copy the folder to your `Playnite/Extensions/` folder.

## Metadata Providers

### DLSite

**Website**: [ENG](https://www.dlsite.com/ecchi-eng/), [JPN](https://www.dlsite.com/maniax/)

**Supported Fields**:

- Name
- Developers
- Publishers
- Description
- Release Date
- Genres
- Cover Image
- Background Image
- Links

**Usage**:

Copy either the entire URL or just the ID (eg `RE234198` or `RJ173356`) into the Name field, click the _Download Metadata..._ button in the bottom left corner and select _DLSite_.

![how-to-dlsite-1](images/how-to-dlsite-1.png)

Change any fields you want afterwards and click the _Save_ button in the bottom right corner.

![how-to-dlsite-2](images/how-to-dlsite-2.png)

### F95Zone

**Website**: [F95](https://www.f95zone.to)

**Supported Fields**:

- Name
- Developers
- Description
- Genres
- Tags
- Cover Image
- Background Image
- Links (not really)

**Usage**:

Copy the entire URL into the Name field, click the _Download Metadata..._ button in the bottom left corner and select _F95Zone_.

![how-to-f95-1](images/how-to-f95-1.png)

Change any fields you want afterwards and click the _Save_ button in the bottom right corner.

![how-to-f95-2](images/how-to-f95-2.png)

### VNDB

**Website**: [VNDB](https://vndb.org/)

**Supported Fields**:

- Name
- Description
- Cover Image
- Background Image
- Release Date
- Community Score
- Genres
- Links

**Usage**:

You can either use the ID (eg: `v11`), Link (eg: `https://vndb.org/v11`) or Name (eg: `Fate/Stay Night`) of the game in the Name field. Click the _Download Metadata..._ button in the bottom left corner and select _VNDB_.

![how-to-vndb-1](images/how-to-vndb-1.png)

You will get a list of search results if you used the Name of the game.

![how-to-vndb-2](images/how-to-vndb-2.png)

Change any fields you want afterwards and click the _Save_ button in the bottom right corner.

![how-to-vndb-3](images/how-to-vndb-3.png)

## Troubleshooting

If an extension is not working correctly, make sure you take a look at the `playnite.log` file in `%appdata%/Playnite`.
