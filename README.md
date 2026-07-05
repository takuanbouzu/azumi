# AZUMI

Static clickable prototype of Azumi, a music/culture social network. Reconstructed from 145 original 2014-era design frames with all real artist names, photos, and film stills replaced by fictional equivalents.

## Run it

Double-click `AZUMI_LIVE.html`, or open it directly in a browser. No build step, no dependencies, no network connection required.

## Views

| Route | Contents |
|---|---|
| `#/explore` | Masonry discovery grid — click a tile for an overlay detail card |
| `#/home` | Personal feed with inline comments |
| `#/tribe/velvet-static` | Artist community: gallery, announcements, board, events, contests, members, library |
| `#/user/mariko` | Member profile: stats, skills matrix, connections filters, tribes, events |

Persistent shell: top bar (search, player), left nav, right rail (feed, chat, queue).

## Stack

Vanilla JS, hash-based router, inline `SEED` data object. Single self-contained HTML file — no frameworks, no CDN dependencies.
