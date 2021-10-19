# note_oreilly_time_seriese_analysis

これは、オライリーから出版された「[実践　時系列解析](https://www.oreilly.co.jp/books/9784873119601/)」の[輪読会](https://reading-circle-beginners.connpass.com/event/227344/)向けの個人的な実験用リポジトリです。

該当の書籍と本リポジトリには一切の関係はありません。

## 環境構築

実験用の環境構築。

書籍ではRとPythonのコードが記載されていますので、jupyter labで両方を扱えるようにします。

### 事前の準備

事前に以下のアプリケーションの導入が必要

- Docker
- docker-compose

### 環境構築手順

本リポジトリをclone

```bash
git clone {URL}
cd note_oreilly_time_seriese_analysis
```

dockerコンテナを構築

```bash
docker-compose up -d
```

ブラウザから以下のURLにアクセスしてjupyter labが起動することを確認。
起動しない場合はログを確認。

`http://localhost:8102`

接続ポートは`docker-compose.yml`で環境に合わせて設定する（空きポートを指定する）。
