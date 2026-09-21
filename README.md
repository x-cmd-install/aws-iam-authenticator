# aws-iam-authenticator

[中文版本](./README.cn.md)

A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster

[![x-cmd/install — aws-iam-authenticator Code Quality Monitoring Repo Card](https://repo.x-cmd.io/aws-iam-authenticator.svg)](https://x-cmd.com/install/aws-iam-authenticator)

## Install

```sh
x install aws-iam-authenticator
```

## Code insight

Total: **12,066** lines of code across **121** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 10,137 | 1,628 | 1,454 | 83 |
| Sh | 966 | 297 | 219 | 16 |
| Yaml | 768 | 170 | 39 | 20 |
| Makefile | 155 | 31 | 37 | 1 |
| Python | 26 | 1 | 2 | 1 |

## OpenSSF Scorecard

Overall score: **6.9 / 10**

Lowest-scoring checks:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Pinned-Dependencies** (4/10) — dependency not pinned by hash detected -- score normalized to 4
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/kubernetes-sigs/aws-iam-authenticator>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.7.20` (2026-08-26)
- **Last commit**: 2026-08-26
- **Assets in release**: 8

## Popularity

- **Stars**: 2,335 · **Forks**: 455 · **Open issues**: 300 · **Contributors**: 505

## Totals (cumulative)

- **Releases**: 66 · **Merged PRs**: 524 · **Open PRs**: 14 · **Closed issues**: 293 · **Open issues**: 7 · **Commits**: 1030

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-22 | 2 | 2 | 5 | 0 | 2 | 0 |
| last60d | 2026-07-23 | 2 | 4 | 7 | 0 | 2 | 7 |
| 90d | 2026-06-23 | 2 | 8 | 9 | 0 | 3 | 11 |
| last180d | 2026-03-25 | 8 | 29 | 12 | 1 | 3 | 34 |
| 360d | 2025-09-26 | 13 | 69 | 14 | 1 | 3 | 86 |
| last720d | 2024-10-01 | 24 | 160 | 14 | 5 | 3 | 365 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [authenticator_0.7.20_checksums.txt](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/authenticator_0.7.20_checksums.txt) | 759 B | `other` |
| [aws-iam-authenticator_0.7.20_darwin_amd64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_darwin_amd64) | 33.3 MiB | `native/darwin/x64` |
| [aws-iam-authenticator_0.7.20_darwin_arm64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_darwin_arm64) | 31.2 MiB | `native/darwin/arm64` |
| [aws-iam-authenticator_0.7.20_linux_amd64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_amd64) | 32.5 MiB | `native/linux/x64` |
| [aws-iam-authenticator_0.7.20_linux_arm64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_arm64) | 30.2 MiB | `native/linux/arm64` |
| [aws-iam-authenticator_0.7.20_linux_ppc64le](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_ppc64le) | 32.1 MiB | `other` |
| [aws-iam-authenticator_0.7.20_linux_s390x](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_s390x) | 33.5 MiB | `other` |
| [aws-iam-authenticator_0.7.20_windows_amd64.exe](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_windows_amd64.exe) | 33.2 MiB | `native/win/x64` |

## Improve this data

Install metadata for aws-iam-authenticator lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `aws-iam-authenticator` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/aws-iam-authenticator.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260921.yml` · 2026-09-21T06:25:37Z._
