# Contributing

Thank you for taking the time to contribute. These repositories are
measurements of trust boundaries in Erlang/OTP and the tools built on it, so
the rules below are about keeping every claim reproducible.

## Before you start

- For a security vulnerability, do not open an issue or a pull request; follow
  [SECURITY.md](SECURITY.md).
- For anything beyond a small fix, open an issue first and describe what you
  want to change and why. It avoids work that cannot be merged.
- Check the repository's `LICENSE`. A repository without one is published for
  reading only and does not accept contributions.

## Measurements

Every claim in these repositories is measured. A contribution that changes a
claim must come with the measurement that supports it:

- Run the repository's own runner (for example `./run-docker.sh 27 28 29`)
  on the OTP versions it lists, in a container, not on the host.
- Commit the regenerated results together with the change, in the same pull
  request.
- If something could not be measured, say so in the "Not measured, and why"
  section instead of leaving it out.

## Pull requests

- One change per pull request, with a title that says what changed.
- Write code, comments and documentation in English.
- Explain in the description what you measured and how; a reviewer should be
  able to repeat it from the description alone.
- Keep the runner passing on every version the repository supports.

## License

By contributing, you agree that your contribution is licensed under the same
license as the repository it goes into (see its `LICENSE` file).
