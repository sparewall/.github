# Contributing to Sparewall

Thanks for your interest! Sparewall is early, so the most useful
contributions right now are bug reports, testing in homelabs, and review of
the design and code.

## Ground rules

- Discuss substantial changes in an issue before opening a large pull request.
- Every change goes through a pull request with passing CI.
- Keep commits focused, with messages that explain *why*.
- Sign off your commits (`git commit -s`) to certify the
  [Developer Certificate of Origin](https://developercertificate.org/).
- Code you contribute is licensed under the repository's license
  (GPL-3.0 for the core).

## Development

See the `README.md` and `AGENTS.md` in each repository for build and test
instructions. For the core:

```shell
cargo fmt --all --check
cargo clippy --workspace --all-targets -- -D warnings
cargo test --workspace
```

## Reporting security issues

Do not open public issues for vulnerabilities; see [SECURITY.md](SECURITY.md).
