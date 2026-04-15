# jamchi-lp

合同会社ジャムチ（Jamchi, LLC）の公式サイト。

- 本番：https://jamchi.club/
- デプロイ：GitHub Pages（`main` branch push で自動）
- ドメイン管理：Squarespace（A レコード × 4 本で GitHub Pages apex に接続）
- メール：Google Workspace（`fukutomi@jamchi.club`）
- 連絡先：fukutomi@jamchi.club

## 編集方針

- 法人名刺ミニマル。事業内容 1 行 + 会社概要 + 連絡先 + 代表プロフィールリンクのみ
- ブランド表現・事業詳細は個人発信側（SNS / blog）に集約する

## DNS 設定（Squarespace 側）

`jamchi.club` の A レコードを以下に設定：

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

MX レコード（Google Workspace の Gmail 用）は**削除しない**。
