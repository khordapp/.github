# Khord

**Music, across every platform.**

Khord is a self-hosted, decentralized music sharing platform built on the [AT Protocol](https://atproto.com). Share a song once — your friends listen on whichever streaming service they use. Spotify, Apple Music, Deezer, etc.

## What makes it different

- **Cross-platform by default** — every shared song is automatically resolved to major streaming services
- **Decentralized identity** — sign in with your Bluesky account; your records live in your own AT Protocol identity, not a central database
- **Collaborative mixtapes** — create ordered playlists, let friends propose songs, accept or dismiss them, and share the result
- **Self-hosted** — run your own instance around a genre, an era, a scene, or a group of friends

## Repositories

| Repo | Description |
|---|---|
| [khord](https://github.com/khordapp/khord) | SvelteKit web app — AT Protocol OAuth, song sharing, feed, mixtapes, admin panel |
| [khord-indexer](https://github.com/khordapp/khord-indexer) | AT Protocol firehose subscriber — indexes songs, votes, and proposals into SQLite |
| [khord-unraid](https://github.com/khordapp/khord-unraid) | Unraid Community Applications templates |
| [khord-www](https://github.com/khordapp/khord-www) | Landing page (khord.app) |

## Getting started

The easiest way to run Khord is via **Unraid Community Applications** — search for `khord` and install both the `khord` and `khord-indexer` templates. Set both to the same Data Path and you're up in minutes.

For VPS or home server installs, see the [khord repo](https://github.com/khordapp/khord) — a `docker-compose.yml` is included.

## Status

Khord is currently in **beta**. Core features are stable; expect rough edges, especially on Android. Bug reports and feedback welcome via [GitHub Issues](https://github.com/khordapp/khord/issues).
