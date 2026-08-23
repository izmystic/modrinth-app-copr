# modrinth-app-copr

Rebuilds the [Modrinth App](https://modrinth.com/app) Copr package whenever Modrinth ships a new release.

## Install

```bash
sudo dnf copr enable mystic/modrinth-app
```
```bash
sudo dnf install modrinth-app
```

## What's in here

One GitHub Action on a cron schedule. It checks for a new Modrinth release and pings Copr's webhook if there is one. No spec file, no build logic, that all lives on Copr's side.

## Not official

Unofficial repackage. Modrinth App itself is made by [Modrinth](https://github.com/modrinth/code), this repo has nothing to do with them beyond redistributing their RPM.
