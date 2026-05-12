# Contributing to Top Robbers

Thank you for your interest in contributing to **Top Robbers**.

This document explains how to contribute properly.

## Ways to contribute

You can help by:

- Reporting bugs
- Suggesting features
- Improving documentation
- Translating the project
- Testing builds
- Reviewing issues
- Opening pull requests
- Improving code quality
- Sharing technical feedback

## Repository usage

Please use the correct repository:

| Type | Repository |
| --- | --- |
| Gamemode logic | `gamemode` |
| WebView / CEF UI | `webview` |
| Launcher | `launcher` |
| Translations | `locales` |
| Suggestions / roadmap / global feedback | `meta` |

If you are unsure where to report something, open it in `meta`.

## Before opening an issue

Please check:

1. The issue does not already exist.
2. You are using the latest available version.
3. You have included enough details.
4. You selected the correct repository.
5. You included logs, screenshots, or reproduction steps when relevant.

## Bug reports

A good bug report should include:

- A clear title
- What happened
- What you expected to happen
- Steps to reproduce
- Logs or screenshots
- Repository / component affected
- Version or commit if known
- Operating system if relevant

Example:

```txt
When starting a store robbery, cops do not receive the alert.

Steps:
1. Join as robber.
2. Start a store robbery.
3. Join another player as cop.
4. No alert appears.

Expected:
Cops should receive a robbery alert.
```

## Feature suggestions

A good feature suggestion should explain:

- The problem or use case
- The proposed solution
- Why it improves the project
- Possible drawbacks
- Which part of the project is affected

Please avoid vague suggestions like:

```txt
Add more stuff.
```

Prefer:

```txt
Add crew-based street races with leaderboards and weekly rewards.
```

## Pull requests

Before opening a pull request:

1. Keep the scope small and focused.
2. Link the related issue when possible.
3. Explain what changed.
4. Explain how you tested it.
5. Follow the existing code style.
6. Avoid unrelated formatting changes.

## Code style

General expectations:

- Keep code readable.
- Prefer clear names over clever code.
- Keep features modular.
- Avoid hardcoded user-facing text.
- Use localization keys for messages and UI text.
- Avoid mixing unrelated concerns in the same class or file.
- Keep server logic, UI logic, and persistence separated.

## Localization

User-facing text should use translation keys.

Do not hardcode text directly in gamemode or UI code when it should be translatable.

Preferred:

```txt
robbery.started
crew.created
common.confirm
common.cancel
```

Not preferred:

```txt
The robbery has started.
```

## Commit messages

Use clear commit messages.

Recommended format:

```txt
type(scope): short description
```

Examples:

```txt
feat(robbery): add store robbery objective
fix(webview): correct crew dashboard layout
docs(meta): update roadmap
chore(locales): add missing English keys
```

Common types:

- `feat`
- `fix`
- `docs`
- `refactor`
- `chore`
- `test`
- `perf`

## Community behavior

All contributors must follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## Security issues

Do not open public issues for vulnerabilities or exploits.

See [SECURITY.md](SECURITY.md).
