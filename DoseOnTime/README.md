# 到点吃药 — 法律协议文档

本目录存放 到点吃药 的全部用户协议与隐私政策文件（中英文合一）。App 通过 `LegalLinks` 常量引用这些文档的 GitHub Blob URL。

- 开发者：wangzz
- 联系邮箱：wzzvictory_tjsd@163.com
- 生效日期：2026-09-01
- 工程英文名（远端目录名）：`DoseOnTime`

## 文档清单

- [PRIVACY_POLICY.md](PRIVACY_POLICY.md) — 隐私政策 / Privacy Policy
- [USE_TERMS.md](USE_TERMS.md) — 使用条款 / Terms of Use
- [SUBSCRIPTION.md](SUBSCRIPTION.md) — 订阅条款 / Subscription Terms（App 含自动续期订阅）

## 访问 URL（GitHub Blob，App 内引用与 ASC 提交的唯一规范）

```
https://github.com/wangzz/md-doc/blob/main/DoseOnTime/<DOCNAME>.md
```

`<DOCNAME>` 取自协议矩阵的远端文件名，使用 SCREAMING_SNAKE_CASE：

- `PRIVACY_POLICY` — 隐私政策（禁止写作 `PRIVACY` / `POLICY`）
- `USE_TERMS` — 使用条款（禁止写作 `TERMS` / `EULA` / `TERMS_OF_USE`）
- `SUBSCRIPTION` — 订阅条款（仅订阅 App）
- `ACCOUNT_DELETION` — 账号删除说明（仅有账号体系）
- 其余按 `references/legal-docs-playbook.md` §1 协议矩阵展开

GitHub 会自动将 `.md` 文件渲染为带样式的 Markdown 页面，无需启用 GitHub Pages。

## 发布到 foogry.wang

三个文档同时发布到 `https://foogry.wang/doc/DoseOnTime/`，文件名即 URL slug：

```
https://foogry.wang/doc/DoseOnTime/PRIVACY_POLICY.html
https://foogry.wang/doc/DoseOnTime/USE_TERMS.html
https://foogry.wang/doc/DoseOnTime/SUBSCRIPTION.html
```

## 更新流程

协议更新不需要重新发版 App。直接修改本目录下的对应文件，提交并 push 到 main 分支，URL 内容即时更新。

更新后建议：

1. 修改对应文档的「生效日期 / Effective Date」字段为新日期
2. 在 App 内发送一次「协议已更新」通知（如适用）
3. 对于实质性变更（收集新类型数据、新增第三方 SDK、订阅价格调整），必须提前 30 天通知用户
