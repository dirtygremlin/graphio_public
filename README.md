# Graphio

Graphio is a graph-based universal media tracker and discovery app — think Letterboxd, but for *everything* (films, series, games, music…), built around an explorable graph instead of lists.

## The idea

Every piece of media is a **node**. Edges connect it to similar things, so you *walk* through culture instead of scrolling:

- Pick a film and see the films closest to it — by theme and feel, not just shared actors or a genre tag.
- Track what you've seen, want to see, or are watching, and build a profile.
- **Cross domains:** from a film, jump to the music or series that sits near it in the same space. That cross-domain leap is the thing existing trackers don't do.

Under the hood every item is turned into an embedding (a vector) and placed in one shared space, so "similar" is measured by meaning and distance — and films, music, and games all live in the *same* space, which is what makes the jumps between them possible.

## Status

Early prototype. Build order: a walkable film graph first, then the tracker layer, then the cross-domain bridge into music.
