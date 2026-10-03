# Upstream

Vendored from:

https://github.com/amosblomqvist/pi-interactive-subagents

Current local changes:

- Removed the nested `.git` directory so this config repo can track the files directly.
- Updated imports from the old `@mariozechner/*` package scope to the current `@earendil-works/*` package scope.
- Updated `@sinclair/typebox` imports to Pi's host-provided `typebox` package.
- Removed nested `package-lock.json` and nested dev dependencies; the root `pi-config` package manages local dependencies.

If we want this as a true separate repository later, create a fork, apply these patches there, then replace this vendored directory with a git submodule pointing at your fork.
