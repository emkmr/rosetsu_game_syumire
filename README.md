# rosetsu_game_syumire

## GitHub Pagesで公開する手順

このリポジトリは `main` ブランチに push すると、GitHub Actions で自動的に Pages へデプロイされます。

1. GitHub にリポジトリを作成して、このフォルダを `main` に push する
2. GitHub の `Settings` > `Pages` で `Source: GitHub Actions` を選ぶ
3. `Actions` タブで `Deploy static site to GitHub Pages` が成功するのを待つ

公開URL:
- ルート: `https://<username>.github.io/<repo>/`
- オープニング単体: `https://<username>.github.io/<repo>/opening_starwars.html`

## ローカル確認

`opening_starwars.html` をブラウザで開くと単体再生できます。
