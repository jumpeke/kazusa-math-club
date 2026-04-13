# かずさ数学クラブ

「かずさ数学クラブ」の公式ウェブサイト（GitHub Pages）のソースコードです。

## ローカル環境でのプレビュー（確認用）

ローカル環境（ご自身のPC）で表示や動作を確認する場合は Jekyll のインストールが必要です。（`jekyll: command not found` エラーが出る場合の対応になります）

### 手順

1. Rubyがインストールされているか確認してください。
2. 以下のコマンドで Jekyll と Bundler をインストールします。
   ```bash
   gem install jekyll bundler
   ```
   *(※システム標準のRubyで権限エラーが出る場合は、Rubyのパスや rbenv 等を使うか、`sudo gem install` が必要になる場合があります)*

3. インストールが完了したら、当リポジトリのディレクトリにて以下のコマンドを実行します。
   ```bash
   jekyll serve
   ```
4. ブラウザで `http://localhost:4000` にアクセスすると、ページの表示確認ができます。