# gpt-office

TK 视频项目的工作区仓库,用于存放项目代码、素材说明与相关文档。

## 克隆

```bash
git clone git@github.com:yeyeye227/gpt-office.git
cd gpt-office
```

本仓库使用 SSH 认证,推送前需先把本机公钥登记到 GitHub
(Settings → SSH and GPG keys → New SSH key)。

## 分支约定

| 分支 | 用途 |
| --- | --- |
| `main` | 稳定版本,始终可部署 |
| `dev` | 日常开发分支,功能完成后再合回 `main` |

## 提交规范

- 提交信息用中文,一句话说明本次改动的**目的**而非罗列文件
- 单次提交只做一件事,不要把重构和功能混在一起
- 推送前先 `git pull --rebase` 同步远端,避免产生无意义的合并提交

## 目录结构

```
gpt-office/
├── README.md      本文件
├── .gitignore     忽略规则
└── .gitattributes 行尾策略
```

后续按项目实际进展补充。
