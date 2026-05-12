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
