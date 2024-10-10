# Repro for #4225

Running the following command should not error.

```sh
yarn format --write --since $(git rev-parse HEAD)
```
