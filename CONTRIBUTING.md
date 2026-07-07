# Contributing to Balsm

Thank you for your interest in contributing to **Balsm** (بَلسَم) — the open-source unified healthcare ecosystem for the MENA region. Whether you fix a bug, improve documentation, translate a screen, or propose a feature, your contribution helps build technology in the service of healing.

> This document lives in the organization-wide [`.github`](https://github.com/balsm-health/.github) repository and applies to **every repository** in the `balsm-health` organization. Individual repositories may add their own `CONTRIBUTING.md` with repo-specific instructions, which takes precedence over this one.

## Repository Map

| Repository | What it is |
|---|---|
| [Balsm-Core](https://github.com/balsm-health/Balsm-Core) | Core platform — domain model, specs, and architecture |
| [Balsm-API-DotNet](https://github.com/balsm-health/Balsm-API-DotNet) | Backend API (.NET) |
| [balsm_app_flutter](https://github.com/balsm-health/balsm_app_flutter) | Mobile & desktop app (Flutter) |
| [Balsm-AI](https://github.com/balsm-health/Balsm-AI) | AI agents, skills, and tooling |
| [website](https://github.com/balsm-health/website) | Public website |
| `file_type_plus`, `file_sized`, `time_of_day`, `paging_plus`, `tawakkalna_sdk_flutter`, `media_source` | Standalone Flutter/Dart packages (MIT licensed) |

## Ways to Contribute

- **Report bugs** — open an issue in the relevant repository with steps to reproduce, expected vs. actual behavior, and environment details.
- **Suggest features** — open an issue describing the problem you want solved before proposing a solution.
- **Improve documentation** — corrections and clarifications are always welcome, in English or Arabic.
- **Translate & localize** — Balsm serves the Arab world; Arabic translations and RTL fixes are first-class contributions.
- **Write code** — pick an open issue (look for `good first issue` / `help wanted` labels) or propose your own change.

## Before You Start

1. **Search existing issues** to avoid duplicates.
2. **Open an issue first** for anything non-trivial (new features, breaking changes, architectural changes) so maintainers can confirm direction before you invest time.
3. Small fixes (typos, obvious bugs, doc tweaks) can go straight to a pull request.

## Development Workflow

1. **Fork** the repository and clone your fork.
2. **Create a branch** from the default branch with a descriptive name, e.g. `fix/appointment-timezone` or `feature/lab-results-export`.
3. **Make your changes.** Follow the code style of the repository you are working in (linters and analyzers are configured per repo — run them before committing).
4. **Test your changes.** Add or update tests where the repository has a test suite, and make sure existing tests pass.
5. **Commit** using the convention below.
6. **Push** your branch and open a **pull request** against the default branch.

### Commit Message Convention

We use a `[Tag] summary` format:

```
[Fix] boundary_lint: allow infrastructure/ DI exports in module barrels
[Feature] core: typed i18n via compile-time bundles
[Docs] clarify appointment booking flow
```

Common tags:

| Tag | Use for |
|---|---|
| `[Feature]` | New functionality |
| `[Fix]` | Bug fixes |
| `[Refactor]` | Code restructuring without behavior change |
| `[Docs]` | Documentation only |
| `[Chore]` | Maintenance, dependencies, tooling |
| `[CI]` | Build and CI pipeline changes |
| `[UI]` | Visual/design changes |
| `[Test]` | Adding or fixing tests |

Keep the summary imperative and under ~72 characters; add a body when the *why* is not obvious.

### Pull Request Guidelines

- Keep PRs **focused** — one logical change per PR. Split large work into reviewable pieces.
- Fill in a clear description: what changed, why, and how it was tested.
- Link related issues (`Closes #123`).
- Include screenshots or recordings for UI changes (both LTR and RTL where relevant).
- Be responsive to review feedback; maintainers may request changes before merging.

## Code Style

Each repository defines its own tooling — respect what is configured there:

- **Flutter/Dart**: run `dart format` and `flutter analyze`; custom lints (e.g. boundary lints) must pass.
- **.NET**: follow the existing project conventions and analyzers.
- **Web**: follow the formatter/linter configured in the repository.

When in doubt, match the style of the surrounding code.

## Security Vulnerabilities

Balsm is healthcare software — security issues are treated with the highest priority.

**Do not open public issues for security vulnerabilities.** Instead, report them privately via [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-security-advisories) ("Report a vulnerability" on the repository's Security tab). We will acknowledge your report and work with you on a fix and coordinated disclosure.

## Licensing

Licensing varies by repository — always check the `LICENSE` file of the repository you are contributing to:

- **Platform repositories** (Balsm-Core, Balsm-API-DotNet, balsm_app_flutter, Balsm-AI, website) are licensed under the **GNU AGPL-3.0 with Additional Terms** (see the [LICENSE](https://github.com/balsm-health/.github/blob/main/LICENSE) file).
- **Standalone Flutter/Dart packages** (`file_type_plus`, `file_sized`, `time_of_day`, `paging_plus`, `tawakkalna_sdk_flutter`, `media_source`) are licensed under the **MIT License** and are *not* covered by the platform license or its Additional Terms.

By submitting a contribution, you agree that it will be licensed under the same terms as the repository you contribute to.

## Questions?

Open a discussion or issue in the relevant repository — we're happy to help you get started.

**Your care. Your data. Your system.** Open. Arab. Owned.
