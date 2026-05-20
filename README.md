# MARIO WEB DESIGN

小さなお店・個人事業主向けホームページ制作サービスの静的サイトです。

## ファイル構成

- `index.html`: ページ本文
- `style.css`: レイアウト・デザイン
- `assets/`: ページ内で使う画像

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作成します。
2. このフォルダをそのリポジトリへpushします。
3. GitHubの `Settings` → `Pages` で、`Deploy from a branch` を選びます。
4. Branchを `main`、Folderを `/ (root)` にして保存します。
5. Custom domainに `mariowebdesign.net` を設定します。

公開後は、`index.html` と `style.css` を編集してpushするとサイトへ反映されます。

## 独自ドメイン

`CNAME` ファイルに `mariowebdesign.net` を設定済みです。
ドメイン管理画面では、GitHub Pages用のDNS設定が別途必要です。
