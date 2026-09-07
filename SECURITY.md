# Security policy

This is the default policy for ClassEve repositories. Where a repository ships
its own `SECURITY.md`, that file is the authority for that project — it will
describe the actual attack surface, which this cannot.

## Reporting a vulnerability

Email **security@classeve.com**, or open a private advisory from the Security
tab of the repository in question. Please do not open a public issue.

Include what you did, what happened, and what you expected. A proof of concept
helps but is not required to file.

We acknowledge within three working days and tell you our assessment and the
timeline we intend to fix on. If we disagree that something is a vulnerability
we will say so and explain why, rather than letting the report go quiet.

We credit you when the fix ships unless you would rather we did not.

Our disclosure record: <https://classeve.com/.well-known/security.txt>

## What is in scope

Anything that lets someone reach data or a machine they should not: memory
safety, injection, authentication and transport bypasses, credential exposure,
persistence corruption, and vulnerable published dependencies we ship.

Out of scope: the behaviour of third-party services a product talks to, unless
a ClassEve product handles their response unsafely; and findings from automated
scanners submitted without a demonstrated impact.

## Supported versions

Fixes land on `main` and in the newest release. Older releases are not
backported unless the issue is severe and the upgrade path is genuinely blocked.
