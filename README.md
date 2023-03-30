# docker_nextcloud
nextcloudデプロイツール  
当ツールは、Dockerを用いて簡易的にnextcloud環境を立ち上げるツールです。  

# DEMO
 ※デモ画像等後程記載を予定

# Requirement
 ※バージョン等後程記載を予定
* Mac M1
    * Docker
        * nextcloud
        * MySQL

# Installation
Local deploy
1. Git clone https://github.com/makoto-kamimura/docker_nextcloud.git
2. "docker_nextcloud/docker-compose.yml"の存在するディレクトリまで移動
3. "docker-compose down -v && docker-compose up -d"をターミナルにて実行
4. "localhost:8888"をブラウザにて入力/実行

# Note
* MySQL Default user
    * user:root
    * pass:root


# License
This system is MIT licensed.
