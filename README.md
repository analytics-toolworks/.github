# analytics-toolworks (.github repo)

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/license/MIT)
[![Check Links](https://github.com/analytics-toolworks/.github/actions/workflows/links.yml/badge.svg)](https://github.com/analytics-toolworks/.github/actions/workflows/links.yml)
[![Dependabot](https://img.shields.io/badge/Dependabot-enabled-brightgreen.svg)](https://github.com/analytics-toolworks/.github/security)

<img
src="https://raw.githubusercontent.com/analytics-toolworks/.github/main/docs/images/profile.png"
alt="analytics-toolworks logo"
width="110">

> Organization profile and shared community-health files for the
> **analytics-toolworks** GitHub organization.

This is the organization's special `.github` repository.
It contains the public organization profile and community-health files GitHub
can apply across repositories that do not provide their own.

## Repository Contents

- `profile/README.md` - public landing page shown at
  `github.com/analytics-toolworks`
- `CODE_OF_CONDUCT.md` - organization-wide conduct expectations
- `CONTRIBUTING.md` - organization-wide contribution guidance
- `SECURITY-POLICY.md` - shared security reporting guidance
- `docs/images/profile.png` - organization profile image
- shared repository configuration used by this repository

## Organization Scope

**analytics-toolworks** develops small, reusable, open-source tools for
analytical work.

Tools may support activities such as:

- visualization
- model inspection
- experiment comparison
- analytical evidence
- privacy-preserving logging
- reporting and diagnostics

The tools automate common mechanics to allow analysts to focus
on the project decisions and interpretation.

## Related Organizations

- [composable-data](https://github.com/composable-data) -
  small, typed vocabularies for analytical meaning, decisions, rationale,
  evidence, and conclusions
- [applied-models](https://github.com/applied-models) -
  reproducible machine-learning experiments on accessible datasets

## Maintenance

Validate repository content before committing:

```shell
npx markdownlint-cli2 --fix

git add -A
git commit -m "update"
git push -u origin main
```

## Annotations

[.annotations/annotations.md](./.annotations/annotations.md)

## License

[MIT](./LICENSE)
