# Cassetteur — free music

The free albums that [Cassetteur](https://cassetteur.com), a music player for your own library, offers to download.
Each one is freely licensed by its performers, who know it is offered here, and each comes from the performers' own
download, unchanged.

This repository holds this README and nothing else. The albums are **release assets**, one release for each version of
an album.

## The albums

| Album | Performer | Licence | Where the files come from | Release | Internet Archive mirror |
|---|---|---|---|---|---|
| *J.S. Bach: "Open" Goldberg Variations, BWV 988 (Piano)* (2012) | Kimiko Ishizaka, piano | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain) | The performer's Bandcamp download, [kimikoishizaka.bandcamp.com](https://kimikoishizaka.bandcamp.com/), unchanged (FLAC 24-bit / 96 kHz). Cover photograph: Robert Douglass. | [`open-goldberg-v1`](https://github.com/cassetteur/free-music/releases/tag/open-goldberg-v1) | `cassetteur-open-goldberg-v1` |
| *J.S. Bach: The Art of the Fugue (Kunst der Fuge), BWV 1080* (2017) | Kimiko Ishizaka, piano | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain) | The performer's Bandcamp download, [kimikoishizaka.bandcamp.com](https://kimikoishizaka.bandcamp.com/), unchanged (FLAC 24-bit / 96 kHz). Cover photograph: Robert Douglass; cover design: NASK 041. The programme notes are not included. | [`art-of-the-fugue-v1`](https://github.com/cassetteur/free-music/releases/tag/art-of-the-fugue-v1) | `cassetteur-art-of-the-fugue-v1` |
| *Live at the Hope and Anchor* (2014) | Improvisi | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | The band's Bandcamp free download, [improvisi.bandcamp.com](https://improvisi.bandcamp.com/), unchanged (FLAC 24-bit / 44.1 kHz), offered with the band's written permission. Cover art: Ignacio Urrutia Gamper. | [`live-at-the-hope-and-anchor-v1`](https://github.com/cassetteur/free-music/releases/tag/live-at-the-hope-and-anchor-v1) | `cassetteur-live-at-the-hope-and-anchor-v1` |

Two more releases, `cassetteur-test-album-v1` and `cassetteur-test-album-2-v1`, are not music. They hold short, silent
test tracks made for the app's own download tests, released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/),
and are never offered to anyone.

## What a release holds

- Each track, under a short name: `01.flac`, `02.flac`, …
- `sidecars.pack`: Cassetteur's own analysis of those tracks (the waveform and the harmonic data its player draws), so
  the app need not analyse them after the download.
- `manifest.json`: every file's size and SHA-256, and the name each track takes in a library. The app carries its own
  copy of each manifest and checks every downloaded file against that copy. It never reads the one published here.

The release notes are the album's `Credits.txt`, the same file that is installed with the album.

## Not an endorsement

The performers allowed their albums to be offered here. That is not an endorsement of Cassetteur by them.

## Releases are never deleted

The releases here are immutable: once a release is published, its files and its tag cannot change. A corrected file
gets a new release under a new tag (`open-goldberg-v2`, …) that holds all of the album's files again.

We never delete a release, because a copy of the app that is already installed downloads from the releases it knows
for as long as it is in use. This is our policy. GitHub itself would allow a deletion.

## The mirror

Each release is mirrored on the [Internet Archive](https://archive.org/), under the item named in the table
(`https://archive.org/details/<item>`). The app uses the mirror when it cannot download from GitHub. The mirror is
uploaded by hand after each release. Until an album's item is there, GitHub is its only source.

## Questions

[spencer@cassetteur.com](mailto:spencer@cassetteur.com)
