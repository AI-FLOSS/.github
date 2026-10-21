# Contributing

Thanks for helping. This guide applies to every X-Tech Laboratories repository that does not have
its own.

## Before you start

- For anything bigger than a small fix, open an issue first so we can agree on the approach.
- Check whether the change fits as a plugin, setting or extension point rather than a fork of
  existing behaviour. We would rather make projects configurable than split them.
- Prefer open formats and standard protocols, so the project keeps working with other tools.
- Bringing over a feature from a competing project? Say where it comes from, and respect its
  licence.
- Read the repository's `README.md` and `AGENTS.md` for how to build and test it.

## AI-assisted contributions

AI tools are welcome. Read the [AI policy](AI_POLICY.md): you are accountable for what you submit,
and you say how AI was involved in the pull request.

## Pull requests

1. Write or update tests for the behaviour you change, and make sure the full suite passes. CI runs
   the same checks on every pull request, and a change merges only when they pass.
2. Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages, for example
   `fix(parser): handle empty input`.
3. Fill in the pull request template, including the AI involvement section.
4. Expect an automated AI review alongside human review. Treat its comments as suggestions; a
   maintainer makes the final call.

## Conduct

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).

## Talk to us

Questions are welcome on Matrix in
[#x-tech-laboratories-general](https://matrix.to/#/#x-tech-laboratories-general:matrix.org).
