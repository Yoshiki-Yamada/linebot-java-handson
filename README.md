# ハンズオンの内容

[line/line-bot-sdk-java](https://github.com/line/line-bot-sdk-java)を使って、Java アプリケーション（Spring Bootフレームワーク）でLINE BOTを作ってみる

**次の環境で動作確認しています**

- macOS 10.12.6
- Oracle JDK 1.8.0_181 & Oracle OpenJDK 11+28 builds
- Maven 3.5.4 
- IntelliJ 2018.2.4
- ngrok 2.2.8 (mac os)
- line-bot-sdk-java 2.1.0
- Spring Boot 2.0.5

## 前準備

- [ngrokの準備と起動](doc/01.md)
- [Spring Bootのプロジェクトの準備](doc/02.md)
- [LINE Bot（Message API）の準備](doc/03.md)
- [Spring Bootのプロジェクトの編集](doc/04.md)

## 基本編

- [LINE Botの中身を作成](doc/05.md)
- [時間帯にあわせてあいさつするBot](doc/06.md)
- [おみくじBot](doc/07.md)
- [Web-APIとの連携（ハンズオン専用）](doc/ex01.md)
- [バイナリデータを受信する](doc/Binary/Binary.md)

## 応用編1 特別なやりとり

- [Botから話しかける](doc/08.md)
- [Botからの話しかけを自動化する](doc/09.md)
- [確認画面を表示し、ユーザの回答に対応する](doc/10.md)
- [LINE Beaconに反応させる](doc/Beacon/Beacon.md)

## 応用編2 ユーザーインターフェース

- [Flexメッセージを送信する](doc/Flex/Flex.md)
- [リッチメニューを作成・利用する](doc/RichMenu/RM.md)
- [LIFFを動かす](doc/Liff/Liff_P1.md)

## 参考資料

- [LINEのBot開発 超入門（前編） ゼロから応答ができるまで](https://qiita.com/nkjm/items/38808bbc97d6927837cd)
- [【LINE BOT】Java(Maven)+Heroku+SpringBootでラーメンBOTを作ってみたよ(1)](https://qiita.com/megaitai22/items/e3e130df1c044ec0f3fd)
- [line-bot-sdk-javaでごみ出しリマインダーを作る](https://qiita.com/aytdm/items/7b8692662a0b161c555c)
- [Spring Bootでtaskを定期実行する方法](https://qiita.com/rubytomato@github/items/4f0c64eb9a24eaceaa6e)