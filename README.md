# Flathub Update for v0.12.5

## Files to update in flathub/io.github.totoshko88.RustConn:

1. `io.github.totoshko88.RustConn.yml` - Updated manifest with new tag
2. `cargo-sources.json` - Regenerated Cargo dependencies

## Manual steps:

1. Fork https://github.com/flathub/io.github.totoshko88.RustConn
2. Replace the files with these updated versions
3. Create a Pull Request with title "Update to v0.12.5"

## Or wait for Flathub Bot:

The manifest includes `x-checker-data` which allows Flathub Bot
to automatically detect new releases and create PRs.

With `automerge-flathubbot-prs: true` in flathub.json,
bot PRs will be auto-merged after CI passes.

**Note:** cargo-sources.json still needs manual update as
Flathub Bot doesn't regenerate Cargo dependencies automatically.
