<h1 align="center">crystal-actions</h1>

<p align="center"><strong>GitHub Actions, written in Crystal, that turn your repository into art.</strong></p>

<p align="center">
  <a href="https://crystal-lang.org"><img alt="Crystal" src="https://img.shields.io/badge/built%20with-Crystal-000000?style=flat-square&logo=crystal&logoColor=white"></a>
  <a href="https://github.com/marketplace?type=actions&query=crystal-actions"><img alt="Marketplace" src="https://img.shields.io/badge/GitHub-Marketplace-0076D6?style=flat-square&logo=github&logoColor=white"></a>
  <img alt="MIT License" src="https://img.shields.io/badge/license-MIT-3da639?style=flat-square">
</p>

Each action reads what already happened in your repository, renders it as a
self-contained SVG, and commits it back — so your README has something worth looking at.
No service to sign up for, no runtime to install; just a static Crystal binary in a
prebuilt image.

## Actions

| | |
|---|---|
| **[activity-weather](https://github.com/crystal-actions/activity-weather)** | Your last seven days as a weather report — sunny commits, issue storms, foggy silence, a rainbow right after a release. Five styles, ten conditions, animated skies. |
| **[contributor-mural](https://github.com/crystal-actions/contributor-mural)** | A mural of the people behind your project. Contributors, sponsors, stargazers, or a hand-picked list, in ten styles from a plain grid to a stencil that spells a word out of faces. |

## Shared by all of them

- **Theme-aware** — the SVG carries both palettes and follows the viewer's light/dark scheme
- **Self-contained** — assets are embedded; the image makes no outbound requests when viewed
- **No runtime** — a static binary in a prebuilt container, nothing to install on the runner
- **Deterministic** — same input, same bytes out; every renderer is golden-file tested
- **Zero config** — works out of the box on the repository running the workflow
- **MIT licensed**

Pin to a major tag (`@v0`, `@v1`) to follow releases, or to an exact version for an
immutable image. Each repository's README carries the full configuration reference.

## Contributing

Issues and pull requests are welcome anywhere. Every repository ships the same
`justfile` entry points: `just build`, `just test`, `just check`.

<p align="center">
  <sub>Made with <a href="https://crystal-lang.org">Crystal</a> by <a href="https://github.com/hahwul">@hahwul</a></sub>
</p>
