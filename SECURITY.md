# Security Policy

## Supported Versions

These repositories are not released in numbered versions. Only the latest
commit on `main` is supported; reports against older commits are still
welcome and will be checked against `main`.

## Reporting a Vulnerability

Please do not report security vulnerabilities through public GitHub issues.

Report them privately through GitHub: open the **Security** tab of the
affected repository and click **Report a vulnerability**. This creates a
private draft advisory where we can discuss the problem and prepare a fix.

If you are unable to use GitHub, email <erts.sched@gmail.com>.

Please include:

- A description of the vulnerability and its impact
- Steps to reproduce, or a minimal proof of concept; a container recipe
  (Dockerfile or Compose) is welcome when applicable, so the report can be
  reproduced as-is
- The affected versions or commits you tested

## Response

I maintain these repositories on my own, so I cannot promise a fixed
response time. You can expect me to acknowledge the report, confirm whether I
can reproduce it, and keep you informed until a fix is published.

Reporters are credited in the published advisory unless they ask not to be.

## Scope

This policy applies to all repositories under
[erts-sched](https://github.com/erts-sched) that do not include a security
policy of their own.
