# github-pages-template

数式を TeX で記述できる GitHub Pages のテンプレートです。

公開ページ: <https://kino-3.github.io/github-pages-template/>

- Jekyll のテーマとして [Dinky](https://github.com/pages-themes/dinky) を使用しています。
- TeX を利用するためのライブラリとして [MathJax](https://github.com/MathJax/MathJax) を使用しています。

## 導入手順

1. 新しくリポジトリを作成して, 作成したリポジトリにこのリポジトリのファイルなどを全て複製してください。
1. [Settings](../../settings) の `GitHub Pages` の項目中の `Source` を `Branch: master`, `/ (root)` にして保存してください。
1. [Settings](../../settings) の `GitHub Pages` の項目中の `Theme Chooser` で, `Change theme` を選択して, `Select theme` を押してください。
1. `./_config.yml` の `title` と `description` を適当なタイトル・説明に書き換えてください。

## 詳細情報

- GitHub Pages の作成については [GitHub Pages サイトを作成する](https://docs.github.com/ja/github/working-with-github-pages/creating-a-github-pages-site) を参照してください。
- `./_config.yml` の他の設定については [作者の GitHub](https://github.com/pages-themes/dinky) を参照してください。
- `./_layouts/default.html` は前述の作者の GitHub から複製されたものに [追記](https://github.com/kino-3/github-pages-template/commit/20e5db7af491d192ff4c7b645f0124899214e7ed) したものになります。
- `./_includes/mathjax-v3.html` は <https://github.com/memakura/mathjax-test> のものを複製しました。
