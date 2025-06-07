### Next.jsの自動デプロイメモ
- Next.jsのディレクトリがgitリポジトリの配下でなければ、working-directoryで指定する必要がある
- outの出力先も適宜変更する必要がある
- Nodeのバージョンはgithub actionの方と合わせる必要がある
- `detect-package-manager` のところでディレクトリ指定をする必要がある
- actions/setup-node@v4の実行で `cache-dependency-path` の指定をする必要がある、ファイル名までを指定するっぽい
- exportがもしテンプレートであればコメントアウトか削除でいいのかもしれない
