# AwesomeOS

## Table of Content

### Partial(microsoft/*)

- typescript
- vscode mainly for compat with exisiting users

### Partial(InversifyJs/*)

- theia mainly for compat with existing users

### Partial(Isomorphic-Git)

- mainly for compat with existing users

### Partial(pouchdb)

- mainly for compat with existing users of couchdb and sync-gateway in quaternion

## Roadmap

### Implement Compatible Interfaces and Publish and Expose them

- Universal Git as Git Replacement
- universal-git\worktrees\components\web-interfaces\ide road to universal-ide
- Better AppLaunchers and Publishing Concepts maybe linked Stores?
- offer 1:1 Electron Replacement.

## Quick Start (Windows / Linux / macOS)

```sh
# Clone & enter repository (all platforms)
git clone https://github.com/awesome-os/repository.git && cd repository
```

## Quick Install & Run (Windows / Linux / macOS)

```sh
# Install / hydrate from v11 CAS via holo-pm
holo-pm install repository://github.com/awesome-os/repository@main

# Or project & run directly via holo-project (0-byte hardlink)
holo-project "project://cpp/repository?from=repository://github.com/awesome-os/repository@main"
```
