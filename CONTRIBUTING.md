# Contributing to Towertail

Thank you for your help. This guide applies to all repositories in the [towertail](https://github.com/towertail) organization.

## Build and test

Each repository has its own build and test steps. Read the README of the repository:

- [towertail/towertail](https://github.com/towertail/towertail#readme): macOS app, Windows app, and server.
- [towertail/sampler](https://github.com/towertail/sampler#readme): the Go collector.

## Before you start

- For a large change, open an issue first. Then we can agree on the design before you write the code.
- Search the open issues and pull requests. Make sure that nobody does the same work.

## Pull request rules

- Put one topic in each pull request. Do not mix a fix, a refactor, and a feature.
- Make sure that all tests pass. Add tests for new behavior.
- Write docs and code comments in [ASD-STE100 Simplified Technical English](https://www.asd-ste100.org/): short sentences, active voice, present tense.
- If you change the sampler JSON schema (the wire format), increase the schema version `v`. Update the sampler and all the clients.
- Fill in the pull request template.

## Contributor License Agreement (CLA)

You must sign the [Contributor License Agreement](CLA.md) before we can merge your first pull request.
The CLA lets the project owner keep the option to offer the code under a different license.

When you open a pull request, a bot asks you to sign. To sign, add this comment to the pull request:

```
I have read the CLA Document and I hereby sign the CLA
```

You sign one time. The signature applies to all repositories in the organization.

## Code of conduct

All contributors must obey the [Code of Conduct](CODE_OF_CONDUCT.md).

## Security issues

Do not report a security issue in a public issue. Follow the [security policy](SECURITY.md).
