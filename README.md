# ことばの世界

自作人工言語を紹介するサイトです。Zola で構築しています。

## 言語ページを更新する

各言語の紹介文や語彙は `content/languages/` 内の Markdown ファイルで編集します。サイト名や説明は `config.toml` で設定します。

ローカルで確認するには、Zola をインストールした環境で `zola serve` を実行してください。

## GitHub Pages

`master` ブランチへの push で GitHub Actions が Zola でビルドし、GitHub Pages に公開します。公開先は <https://nh0102heiya-lab.github.io/langen/> です。
