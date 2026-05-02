# サポートサイト（GitHub Pages 用）

App Store Connect の **サポート URL** として使うための静的ページです。

## 専用リポジトリへの反映手順

1. このフォルダ内の **`index.html`** を、作成済みの GitHub 専用リポジトリの **ルート** にコピーする（またはこのフォルダごと中身だけリポジトリに置く）。
2. Git でコミット・プッシュする。
3. GitHub 上で **Settings → Pages** を開く。
4. **Source**: Deploy from a branch → Branch **main**（または **master**）/ folder **/ (root)** を選んで Save。
5. 表示される URL（例: `https://（ユーザー名）.github.io/（リポジトリ名）/`）を App Store Connect の **サポート URL** に入力する。

## ファイル

| ファイル | 説明 |
|----------|------|
| `index.html` | 問い合わせ先メール付きのサポートページ |

メールアドレスを変更する場合は `index.html` 内の `mailto:` と表示テキストを編集してください。
