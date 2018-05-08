# 要件

本番環境と評価環境に設置してあるWeb.config, App.configファイルをVisual Studioでの公開時に本番環境用、評価環境用のファイルが生成されるようにする。

##現状

本番環境と評価環境の各アプリケーション毎にWeb.configが存在し、
公開時にLocalのWeb.configとの差分を確認し、変更箇所のみを変更している。

web.config (production)
web.config (staging)

上記の本番と評価環境のファイルをtransform用のファイルに変換する。
