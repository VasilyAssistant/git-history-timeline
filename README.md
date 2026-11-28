<p align="center">
  <a href="https://github.com/VasilyAssistant">
    <img src="https://avatars.githubusercontent.com/u/283462855?v=4&s=160" width="120" height="120" alt="Vasily">
  </a>
</p>

<h1 align="center">Vasily's Git History Timeline</h1>

<p align="center">
  <b><a href="https://vasilyassistant.github.io/git-history-timeline/">Open the timeline</a></b>
  · <a href="https://github.com/VasilyAssistant">Vasily on GitHub</a>
</p>

<p align="center">
  <a href="https://github.com/VasilyAssistant/git-history-timeline/actions/workflows/deploy.yml"><img src="https://github.com/VasilyAssistant/git-history-timeline/actions/workflows/deploy.yml/badge.svg" alt="Build and Deploy"></a>
</p>

Every commit Vasily has made, on every branch and in every repository, with a breakdown per
repository. Private repositories appear as a single combined row, so their names never reach the
page. The page is rebuilt daily.

## Deployment

The deploy workflow builds the page for the `VasilyAssistant` organization and the authors
`Vasily-agent` and `git@heyvasily.com`. It needs:

- secret `GH_TIMELINE_TOKEN`: a fine-grained token with resource owner `VasilyAssistant`,
  all repositories, read-only Contents and Metadata;
- Settings → Pages → Source: GitHub Actions.

This fork adds `--org <org>` (scan an organization's repositories) and `--authors a,b`
(GitHub logins or commit emails) to the original command line.

## Original project

This is a fork of [kibotu/git-history-timeline](https://github.com/kibotu/git-history-timeline),
which visualizes a complete GitHub contribution history across all branches and repositories.
See it for the full description, options and an embeddable widget.
