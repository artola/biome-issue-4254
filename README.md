# Repro for #4254

Running the following command should not error.

```sh
yarn lint
```

Output:

```text
/biome-issue-4254/src/Button.tsx lint/style/useFilenamingConvention ━━━━━━━━━━

  ✖ The filename should be in kebab-case or equal to the name of an export.

  ℹ The filename could be renamed to one of the following names:
    button.tsx


Checked 3 files in 19ms. No fixes applied.
Found 1 error.
lint ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Some errors were emitted while running checks.


error Command failed with exit code 1.
```
