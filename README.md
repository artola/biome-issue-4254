# Repro for #4225

Running the following command should not error.

```sh
yarn format --write --since $(git rev-parse HEAD)
```

Output:

```text
flags/invalid ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Incompatible arguments since and changed


error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
