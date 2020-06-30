# hotel-example-selenium3-java

![selenium3-java](https://github.com/testplanisphere/hotel-example-selenium3-java/workflows/selenium3-java/badge.svg)

このプロジェクトはテスト自動化学習のためのサンプルコードです。
This project is example codes for learning test automation.

### テスト対象 / Test Object

https://hotel.testplanisphere.dev/

### 概要 / Overview

#### プログラミング言語 / Programming Language

* Java

#### 自動化フレームワーク / Automation Framework

* [Selenium WebDriver](https://www.selenium.dev/)

#### テスティングフレームワーク / Testing Framework

* [JUnit 5](https://junit.org/junit5/)

#### ビルドツール / Build Tool

* [Gradle](https://gradle.org/)

#### 静的解析ツール / Lint Tool

* [Checkstyle](https://checkstyle.sourceforge.io/)

### 実行方法 / How to Run

#### 必須環境 / Requirements

* JDK 11
* Google Chrome
* [ChromeDriver](https://chromedriver.chromium.org/downloads)

ChromeDriverはダウンロードして環境変数`PATH`の通った場所に置いてください。
Download Chromedriver and place it in the System `PATH`.

#### テスト・静的解析の実行 / Run Tests and lint

##### Windows

```
gradlew.bat clean check
```

##### macOS/Linux

```
./gradlew clean check
```

### 変更履歴

#### v2020.6.0 (2020-06-30)

* [#35](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/35) Bump Gradle from 6.4.1 to 6.5.1

#### v1.2.0 (2020-05-31)

* [#25](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/25) Firefoxサポートを停止
* [#26](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/26) Dependabotを導入
* [#27](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/27) Bump junit-jupiter-api from 5.6.0 to 5.6.2
* [#28](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/28) Bump junit-jupiter-engine from 5.6.0 to 5.6.2
* [#29](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/29) Github actions/cacheをv2にアップデート
* [#32](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/32) 未使用のimportを削除
* [#33](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/33) Gradleを6.4.1にアップデート

#### v1.1.0 (2020-04-29)

* [#6](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/6) Github Actionsにpull_requestトリガーを追加
* [#8](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/8) テスト名を修正
* [#9](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/9) ConfirmPageのモーダルを閉じるボタンのセレクターを修正
* [#11](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/11) import文をアルファベット順に修正
* [#13](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/13) Github ActionsでLintを実行するように修正
* [#14](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/14) READMEの記述内容を変更
* [#16](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/16) 連絡手段の変更によるinputの表示切り替えテストを追加
* [#19](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/19) テストデータのアドレスをexample.comに修正
* [#20](https://github.com/testplanisphere/hotel-example-selenium3-java/pull/20) 日付入力が空の場合のテストを追加

#### v1.0.0 (2020-04-14)

* 正式リリース