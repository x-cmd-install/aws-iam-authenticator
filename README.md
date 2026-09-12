# aws-iam-authenticator

[中文版本](./README.cn.md)

A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster

![aws-iam-authenticator](https://repo.x-cmd.io/aws-iam-authenticator.svg)

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
- **Fuzzing** (0/10) — project is not fuzzed
- **Pinned-Dependencies** (4/10) — dependency not pinned by hash detected -- score normalized to 4

## Source

- **Upstream**: <https://github.com/kubernetes-sigs/aws-iam-authenticator>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.7.20` (2026-08-26)
- **Last commit**: 2026-08-26
- **Assets in release**: 8

## Popularity

- **Stars**: 2,333 · **Forks**: 453 · **Open issues**: 299 · **Contributors**: 501

## Totals (cumulative)

- **Releases**: 66 · **Merged PRs**: 524 · **Open PRs**: 12 · **Closed issues**: 293 · **Open issues**: 6 · **Commits**: 1030

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 2 | 3 | 3 | 0 | 1 | 5 |
| last60d | 2026-07-14 | 2 | 4 | 6 | 0 | 1 | 7 |
| 90d | 2026-06-14 | 3 | 10 | 8 | 0 | 2 | 14 |
| last180d | 2026-03-16 | 9 | 34 | 11 | 1 | 2 | 41 |
| 360d | 2025-09-17 | 13 | 72 | 12 | 1 | 2 | 94 |
| last720d | 2024-09-22 | 24 | 160 | 12 | 5 | 2 | 365 |

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

## Distribution status

Reported by **58** distros on [repology.org](https://repology.org/project/aws-iam-authenticator). **6** are ✅ on the latest upstream release, **12** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `0.7.20` | ✅ latest |
| Nix unstable | `0.7.11` | ⚠️ outdated |

## Improve this data

Install metadata for aws-iam-authenticator lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `aws-iam-authenticator` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/aws-iam-authenticator.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260912.yml` · 2026-09-12T06:01:14Z._
