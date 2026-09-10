# aws-iam-authenticator

[English version](./README.md)

A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster

![aws-iam-authenticator](https://repo.x-cmd.io/aws-iam-authenticator.svg?lang=zh)

## 安装

```sh
x install aws-iam-authenticator
```

## 代码洞察

合计: **12,066** 行代码（覆盖前 5 种语言、共 **121** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 10,137 | 1,628 | 1,454 | 83 |
| Sh | 966 | 297 | 219 | 16 |
| Yaml | 768 | 170 | 39 | 20 |
| Makefile | 155 | 31 | 37 | 1 |
| Python | 26 | 1 | 2 | 1 |

## OpenSSF Scorecard 评分

总评分: **6.9 / 10**

评分最低的几项:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed
- **Pinned-Dependencies** (4/10) — dependency not pinned by hash detected -- score normalized to 4

## 源代码

- **上游仓库**: <https://github.com/kubernetes-sigs/aws-iam-authenticator>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.7.20` (2026-08-26)
- **最近提交**: 2026-08-26
- **Release 含资产**: 8 个

## 流行度

- **Star**: 2,332 · **Fork**: 453 · **开放 issue**: 299 · **贡献者**: 500

## 累计统计

- **发布数**: 66 · **已合并 PR**: 524 · **开放 PR**: 12 · **已关闭 issue**: 293 · **开放 issue**: 6 · **提交数**: 1030

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 2 | 3 | 3 | 0 | 1 | 5 |
| last60d | 2026-07-12 | 2 | 5 | 6 | 0 | 1 | 7 |
| 90d | 2026-06-12 | 3 | 10 | 8 | 0 | 2 | 14 |
| last180d | 2026-03-14 | 9 | 37 | 11 | 1 | 2 | 41 |
| 360d | 2025-09-15 | 13 | 72 | 12 | 1 | 2 | 94 |
| last720d | 2024-09-20 | 24 | 160 | 12 | 5 | 2 | 365 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [authenticator_0.7.20_checksums.txt](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/authenticator_0.7.20_checksums.txt) | 759 B | `other` |
| [aws-iam-authenticator_0.7.20_darwin_amd64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_darwin_amd64) | 33.3 MiB | `native/darwin/x64` |
| [aws-iam-authenticator_0.7.20_darwin_arm64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_darwin_arm64) | 31.2 MiB | `native/darwin/arm64` |
| [aws-iam-authenticator_0.7.20_linux_amd64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_amd64) | 32.5 MiB | `native/linux/x64` |
| [aws-iam-authenticator_0.7.20_linux_arm64](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_arm64) | 30.2 MiB | `native/linux/arm64` |
| [aws-iam-authenticator_0.7.20_linux_ppc64le](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_ppc64le) | 32.1 MiB | `other` |
| [aws-iam-authenticator_0.7.20_linux_s390x](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_linux_s390x) | 33.5 MiB | `other` |
| [aws-iam-authenticator_0.7.20_windows_amd64.exe](https://github.com/kubernetes-sigs/aws-iam-authenticator/releases/download/v0.7.20/aws-iam-authenticator_0.7.20_windows_amd64.exe) | 33.2 MiB | `native/win/x64` |

## 发行版状态

在 [repology.org](https://repology.org/project/aws-iam-authenticator) 上共有 **58** 个发行版报告此项目。**6** 个 ✅ 已是最新上游版本，**12** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `0.7.20` | ✅ latest |
| Nix unstable | `0.7.11` | ⚠️ outdated |

## 改进这些数据

aws-iam-authenticator 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `aws-iam-authenticator` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/aws-iam-authenticator.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T22:36:05Z._
