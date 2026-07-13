# 借入返済管理 — サポートサイト

App Store Connect 向けのサポート／プライバシーページです。

## 公開 URL（GitHub Pages）

| 用途 | URL |
|------|-----|
| サポート URL | https://shunsukesaito00.github.io/loanrepayment-support/ |
| プライバシーポリシー URL | https://shunsukesaito00.github.io/loanrepayment-support/privacy.html |
| ads.txt | https://shunsukesaito00.github.io/loanrepayment-support/ads.txt |

リポジトリ: https://github.com/shunsukesaito00/loanrepayment-support

## 更新手順

```bash
# プロジェクト内の最新素材を同期
cp ../support-website/{index.html,privacy.html,ads.txt} .

git add index.html privacy.html ads.txt README.md
git commit -m "Update support site content for App Store listing"
git push origin main
```

GitHub Pages は `main` ブランチのルートから配信されています（Settings → Pages）。

## ファイル

| ファイル | 説明 |
|----------|------|
| `index.html` | サポート・お問い合わせ |
| `privacy.html` | プライバシーポリシー |
| `ads.txt` | AdMob 用販売者宣言 |
