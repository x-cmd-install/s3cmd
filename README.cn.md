# s3cmd

[English version](./README.md)

Official s3cmd repo -- Command line tool for managing S3 compatible storage services (including Amazon S3 and CloudFront).

![s3cmd](https://repo.x-cmd.io/s3cmd.svg?lang=zh)

## 安装

```sh
x install s3cmd
```

## 代码洞察

合计: **10,402** 行代码（覆盖前 5 种语言、共 **31** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 10,003 | 1,264 | 1,878 | 26 |
| Perl | 212 | 7 | 4 | 1 |
| Autoconf | 124 | 3 | 49 | 2 |
| Makefile | 34 | 5 | 5 | 1 |
| Dockerfile | 21 | 0 | 3 | 1 |

## OpenSSF Scorecard 评分

总评分: **3.8 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Maintained** (0/10) — 0 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/s3tools/s3cmd>
- **官网**: <https://s3tools.org/s3cmd>
- **许可证**: GPL-2.0

## 发布

- **最新版本**: `v2.4.0` (2023-12-12)
- **最近提交**: 2025-10-22
- **Release 含资产**: 6 个

## 流行度

- **Star**: 4,908 · **Fork**: 905 · **开放 issue**: 936 · **贡献者**: 172

## 累计统计

- **发布数**: 10 · **已合并 PR**: 307 · **开放 PR**: 42 · **已关闭 issue**: 667 · **开放 issue**: 269 · **提交数**: 1944

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 2 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 3 | 0 |
| last180d | 2026-03-15 | 0 | 0 | 0 | 0 | 6 | 0 |
| 360d | 2025-09-16 | 0 | 0 | 0 | 0 | 11 | 5 |
| last720d | 2024-09-21 | 0 | 8 | 4 | 2 | 24 | 24 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [s3cmd-2.4.0-py2.py3-none-any.whl](https://github.com/s3tools/s3cmd/releases/download/v2.4.0/s3cmd-2.4.0-py2.py3-none-any.whl) | 161.1 KiB | `other` |
| [s3cmd-2.4.0-py2.py3-none-any.whl.asc](https://github.com/s3tools/s3cmd/releases/download/v2.4.0/s3cmd-2.4.0-py2.py3-none-any.whl.asc) | 833 B | `other` |
| [s3cmd-2.4.0.tar.gz](https://github.com/s3tools/s3cmd/releases/download/v2.4.0/s3cmd-2.4.0.tar.gz) | 141.6 KiB | `native/unknown` |
| [s3cmd-2.4.0.tar.gz.asc](https://github.com/s3tools/s3cmd/releases/download/v2.4.0/s3cmd-2.4.0.tar.gz.asc) | 833 B | `other` |
| [s3cmd-2.4.0.zip](https://github.com/s3tools/s3cmd/releases/download/v2.4.0/s3cmd-2.4.0.zip) | 157.6 KiB | `other` |
| [s3cmd-2.4.0.zip.asc](https://github.com/s3tools/s3cmd/releases/download/v2.4.0/s3cmd-2.4.0.zip.asc) | 833 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/s3cmd) 上共有 **105** 个发行版报告此项目。**74** 个 ✅ 已是最新上游版本，**28** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `2.4.0` | ✅ latest |
| Debian 14 | `2.4.0` | ✅ latest |
| Debian 13 | `2.4.0` | ✅ latest |
| Ubuntu 26.04 LTS | `2.4.0` | ✅ latest |
| Ubuntu 24.04 LTS | `2.4.0` | ✅ latest |
| Arch | `2.4.0` | ✅ latest |
| Homebrew | `2.4.0` | ✅ latest |
| Fedora rawhide | `2.4.0` | ✅ latest |
| Nix unstable | `2.4.0` | ✅ latest |
| Void | `2.4.0` | ✅ latest |
| Alpine edge | `2.4.0` | ✅ latest |
| openSUSE Tumbleweed | `2.4.0` | ✅ latest |

## 改进这些数据

s3cmd 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `s3cmd` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/s3cmd.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T19:04:27Z._
