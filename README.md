# Laravel 向け Docker 環境

Visual Studio Code の拡張機能 Remote - Containers に対応した Docker 環境です

## 動作環境

* Docker: 20.10.2
* Docker Compose: 1.27.4
* Docker Desktop for Windows: Version 3.1.0 (51484) にて動作確認
* Visual Studio Code
    * 拡張機能 Remote - Containers

## 作成されるコンテナー

### web-app

* Alpine: 3.9
* Apache: 2.4.*
* PHP: 7.2.*
    * Composer: 1.*.*

### postgres

* PostgreSQL: 9.6
