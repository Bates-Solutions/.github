# .github

Bates Solutions' organisation profile and shared repository files.

`profile/README.md` is what GitHub shows on
[github.com/Bates-Solutions](https://github.com/Bates-Solutions). The facts in it come from the
company site and its content library (`Bates-Solutions/bates-solutions`, `libs/content`); change
them there first.

## Shared files

GitHub uses these in every public repository in the organisation that doesn't have its own copy:

- [`CONTRIBUTING.md`](CONTRIBUTING.md)
- [`SECURITY.md`](SECURITY.md): vulnerabilities go to security@bates-solutions.com.
- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md)
- [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md)
- [`ISSUE_TEMPLATE/`](ISSUE_TEMPLATE): bug report and feature request forms. Blank issues are off,
  and vulnerability reports point at `SECURITY.md`.

## READMEs

[`README-TEMPLATE.md`](README-TEMPLATE.md) is the layout every public repo's README follows: the
section order, the badge row, the header banner and the footer. `brand/` holds the Bates Solutions
lockups the README footers load, copied from the brand library (`libs/brand/logo/horizontal-on-*.svg`
in `Bates-Solutions/bates-solutions`). The repos load them from `raw.githubusercontent.com`, so
don't rename them.
