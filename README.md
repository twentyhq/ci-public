# ci-public

CI workflows for [twentyhq/twenty](https://github.com/twentyhq/twenty) that run in a public repository to benefit from free GitHub Actions minutes.

Workflows here are triggered via `repository_dispatch`, which only accepts events from tokens with write access to this repository. Run logs are public; repository secrets are never exposed to forks or external triggers.
