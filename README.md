# MaverickHQ's Homebrew tap

Homebrew formulae for MaverickHQ's tools.

| Formula | What it installs |
|---|---|
| `herdr-pager` | [herdr-pager](https://github.com/MaverickHQ/herdr-pager): a 1990s-style pager for the coding agents in herdr. `pager-bridge` for macOS on Apple Silicon, and the firmware its setup page flashes. |

```sh
brew install maverickhq/tap/herdr-pager
pager-bridge setup
```

Each formula is written by its project's release workflow, pinned by sha256 to the archive that release built and published, and copied here by the maintainer. Don't change a formula in this repository: change its template in the project (herdr-pager's is `contrib/homebrew/herdr-pager.rb.tmpl`).

The formulae are licensed under Apache-2.0 (`LICENSE`); the software they install has its own licences, listed in each project.
