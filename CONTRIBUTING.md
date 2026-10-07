# Contributing to 3leaps projects

Thank you for helping improve 3leaps open source. Start with the affected
project's README and its own contribution instructions, if present. This guide
supplies the organization default.

## Propose a change

- Search existing issues and pull requests first.
- Discuss substantial features or breaking changes in an issue before implementation.
- Keep pull requests focused. Explain the problem, resulting behavior, and relevant validation.
- Follow the project's build, formatting, and test instructions. Include tests and documentation when behavior changes.
- Identify breaking changes and compatibility implications explicitly.

For this repository, run `make check` and `make quality`. Profile changes should
link only to public projects and describe current capabilities accurately.

## Keep contributions public-safe

We follow the [3 Leaps Sensitive Local Data policy](https://github.com/3leaps/oss-policies/blob/main/SENSITIVE-LOCAL-DATA.md).
Keep proprietary data, private identifying context, and credentials outside
repository folders and all durable git surfaces. A `.gitignore` entry is not
a confidentiality boundary. Use synthetic examples and sanitized reports.

Follow the [Code of Conduct](https://github.com/3leaps/oss-policies/blob/main/CODE-OF-CONDUCT.md)
and respect the [Trademark Policy](https://github.com/3leaps/oss-policies/blob/main/TRADEMARK-POLICY.md).
Licensing is defined by the affected repository's license files.

## Security and help

Report suspected vulnerabilities privately using the
[security policy](https://github.com/3leaps/.github/blob/main/SECURITY.md).
For other questions, see the [support guide](https://github.com/3leaps/.github/blob/main/SUPPORT.md).
