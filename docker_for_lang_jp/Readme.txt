【イメージ作成手順】

windows:コマンドプロンプト
mac:ターミナル

①cd Dockerfileがある階層へ移動

②Dockerfileからイメージ作成
docker build . -t {リポジトリ名}:{TAG}

コマンド例)
docker build . -t mariadb_utf8

※TAGを省略するとlatest（最新）となる。
※TAGとは・・・イメージのバージョンのこと。
