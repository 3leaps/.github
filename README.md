# 3leaps GitHub community files

This repository maintains the [3leaps organization profile](profile/README.md)
and shared contributor guidance for [3leaps](https://github.com/3leaps).

## Contents

- `profile/README.md` and `profile/assets/`: public organization introduction and artwork.
- `CONTRIBUTING.md`, `SUPPORT.md`, `SECURITY.md`, and `CODE_OF_CONDUCT.md`: community defaults.
- `.github/ISSUE_TEMPLATE/` and `.github/PULL_REQUEST_TEMPLATE.md`: issue and pull request templates adapted from [3 Leaps OSS policies](https://github.com/3leaps/oss-policies).

GitHub displays the profile and supplies community defaults when this
repository is public. A project's own corresponding files take precedence.
Defaults are not copied into downstream clones; each project keeps its own
license files. See [GitHub's community-file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Maintaining the profile

List only public projects. Describe what each project does, and link to its
README for current capabilities and maturity. Use **3 Leaps** as the display
brand and **3leaps** as the GitHub organization. Product names stay with the
projects; this organization is the publisher, not a SKU.

When reviewing the published organization page, select **View as: Public**
to check the profile and pinned repositories as visitors will see them.

The wordmark is shared with the 3 Leaps brand kit (green staircase mark,
primary `#46A758`). Keep image URLs in `profile/README.md` absolute so they
also work on the organization overview. Use the color lockup with dark
lettering on light backgrounds and the white-lettering lockup on dark
backgrounds.

Run `make check` and `make quality` before proposing changes. Organization
settings, repository descriptions, topics, and pins are managed separately
from these files.

## Governing policies

This repository follows the [Sensitive Local Data policy](https://github.com/3leaps/oss-policies/blob/main/SENSITIVE-LOCAL-DATA.md):
keep proprietary material outside the repository, including its commit
messages, pull requests, and branch names. See also the
[Trademark Policy](https://github.com/3leaps/oss-policies/blob/main/TRADEMARK-POLICY.md)
for brand usage and [LICENSE](LICENSE) for this repository's licensing.
