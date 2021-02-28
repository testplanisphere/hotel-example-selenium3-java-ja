# hotel-example-selenium3-java-ja

[![selenium3-java-ja](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/actions/workflows/test.yml/badge.svg)](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/actions/workflows/test.yml)

このプロジェクトはテスト自動化学習のためのサンプルコードです。

### テスト対象

https://hotel.testplanisphere.dev/ja/

### 概要

#### プログラミング言語

* Java

#### 自動化フレームワーク

* [Selenium WebDriver](https://www.selenium.dev/)

#### テスティングフレームワーク

* [JUnit 5](https://junit.org/junit5/)

#### ビルドツール

* [Gradle](https://gradle.org/)

#### 静的解析ツール

* [Checkstyle](https://checkstyle.sourceforge.io/)

### 実行方法

#### 必須環境

* JDK 11
* Google Chrome
* [ChromeDriver](https://chromedriver.chromium.org/downloads)

ChromeDriverはダウンロードして環境変数`PATH`の通った場所に置いてください。

#### テスト・静的解析の実行

##### Windows

```
gradlew.bat clean check
```

##### macOS/Linux

```
./gradlew clean check
```

### 変更履歴

#### v2021.2.0 (2021-02-28)

* [#48](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/48) Bump junit-jupiter-api from 5.7.0 to 5.7.1
* [#49](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/49) Bump junit-jupiter-engine from 5.7.0 to 5.7.1
* [#50](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/50) Bump Gradle from 6.6.1 to 6.8.2
* [#51](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/51) Update branch name
* [#52](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/52) update cache setting
* [#53](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/53) Remove jcenter
* [#54](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/54) Bump Gradle from 6.8.2 to 6.8.3

#### v2020.9.0 (2020-09-30)

* [#44](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/44) Bump junit-jupiter-engine from 5.6.2 to 5.7.0 
* [#45](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/45) Bump junit-jupiter-api from 5.6.2 to 5.7.0

#### v2020.8.0 (2020-08-30)

* [#42](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/42) Bump Gradle from 6.5.1 to 6.6.1

#### v2020.7.0 (2020-07-26)

* [#37](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/37) Update Dependabot config file
* [#38](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/38) fix site title
* [#39](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/39) update actions and dependabot
* [#40](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/40) move to ja site

#### v2020.6.0 (2020-06-30)

* [#35](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/35) Bump Gradle from 6.4.1 to 6.5.1

#### v1.2.0 (2020-05-31)

* [#25](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/25) Firefoxサポートを停止
* [#26](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/26) Dependabotを導入
* [#27](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/27) Bump junit-jupiter-api from 5.6.0 to 5.6.2
* [#28](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/28) Bump junit-jupiter-engine from 5.6.0 to 5.6.2
* [#29](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/29) Github actions/cacheをv2にアップデート
* [#32](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/32) 未使用のimportを削除
* [#33](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/33) Gradleを6.4.1にアップデート

#### v1.1.0 (2020-04-29)

* [#6](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/6) Github Actionsにpull_requestトリガーを追加
* [#8](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/8) テスト名を修正
* [#9](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/9) ConfirmPageのモーダルを閉じるボタンのセレクターを修正
* [#11](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/11) import文をアルファベット順に修正
* [#13](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/13) Github ActionsでLintを実行するように修正
* [#14](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/14) READMEの記述内容を変更
* [#16](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/16) 連絡手段の変更によるinputの表示切り替えテストを追加
* [#19](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/19) テストデータのアドレスをexample.comに修正
* [#20](https://github.com/testplanisphere/hotel-example-selenium3-java-ja/pull/20) 日付入力が空の場合のテストを追加

#### v1.0.0 (2020-04-14)

* 正式リリース