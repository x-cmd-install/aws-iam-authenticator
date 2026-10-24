# aws-iam-authenticator

[中文版本](./README.cn.md)

A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster

[![x-cmd/install — aws-iam-authenticator Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/aws-iam-authenticator.svg)](https://x-cmd.com/install/aws-iam-authenticator)

## Install

```sh
x install aws-iam-authenticator
```

## Code insight

Total: **12,173** lines of code across **121** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 10,244 | 1,637 | 1,466 | 83 |
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

- **Latest**: `v0.7.24` (2026-10-23)
- **Last commit**: 2026-10-23
- **Assets in release**: 8

## Popularity

- **Stars**: 2,338 · **Forks**: 456 · **Open issues**: 300 · **Contributors**: 524

## Totals (cumulative)

- **Releases**: 70 · **Merged PRs**: 534 · **Open PRs**: 13 · **Closed issues**: 294 · **Open issues**: 6 · **Commits**: 1051

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-24 | 4 | 9 | 3 | 0 | 0 | 10 |
| last60d | 2026-08-25 | 5 | 11 | 5 | 1 | 1 | 14 |
| 90d | 2026-07-26 | 6 | 14 | 6 | 1 | 1 | 18 |
| last180d | 2026-04-27 | 11 | 28 | 11 | 2 | 2 | 35 |
| 360d | 2025-10-29 | 16 | 69 | 13 | 2 | 2 | 91 |
| last720d | 2024-11-03 | 28 | 164 | 13 | 5 | 2 | 365 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [authenticator_0.7.24_checksums.txt](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/authenticator_0.7.24_checksums.txt) | 759 B | `other` |
| [aws-iam-authenticator_0.7.24_darwin_amd64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/aws-iam-authenticator_0.7.24_darwin_amd64) | 33.4 MiB | `native/darwin/x64` |
| [aws-iam-authenticator_0.7.24_darwin_arm64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/aws-iam-authenticator_0.7.24_darwin_arm64) | 31.1 MiB | `native/darwin/arm64` |
| [aws-iam-authenticator_0.7.24_linux_amd64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/aws-iam-authenticator_0.7.24_linux_amd64) | 32.6 MiB | `native/linux/x64` |
| [aws-iam-authenticator_0.7.24_linux_arm64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/aws-iam-authenticator_0.7.24_linux_arm64) | 30.3 MiB | `native/linux/arm64` |
| [aws-iam-authenticator_0.7.24_linux_ppc64le](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/aws-iam-authenticator_0.7.24_linux_ppc64le) | 32.1 MiB | `other` |
| [aws-iam-authenticator_0.7.24_linux_s390x](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/aws-iam-authenticator_0.7.24_linux_s390x) | 33.6 MiB | `other` |
| [aws-iam-authenticator_0.7.24_windows_amd64.exe](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.24/aws-iam-authenticator_0.7.24_windows_amd64.exe) | 33.3 MiB | `native/win/x64` |

## Distribution status

Reported by **62** distros on [repology.org](https://repology.org/project/aws-iam-authenticator). **3** are ✅ on the latest upstream release, **15** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `0.7.24` | ✅ latest |
| Nix unstable | `0.7.11` | ⚠️ outdated |

## Improve this data

Install metadata for aws-iam-authenticator lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `aws-iam-authenticator` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/aws-iam-authenticator.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261024.yml` · 2026-10-24T05:53:41Z._
