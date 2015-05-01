dbflute.github.io
====


## DBFlute とは
### DB変更に強いをテーマにした開発支援ツール
- リーン・スタートアップ＆インクリメンタル開発
- 設計しながら実装する開発 (納期の短い開発)

ビジネス要求の変化が激しいシステム開発が増えてきました。DB変更は日常の風景。そんな現場でDB変更に対しアプリケーションが**できるだけスピーディーに** 対応できるようにするために、DBFlute は大きく二つの機能を備えています。

- 　　**O/Rマッパー**
    - 　　自動生成ドリブンでDB変更の影響範囲をスピーディーに検知
- 　　**DB管理支援ツール**
    - 　　DB環境構築自動化や履歴管理など、DB変更の運用上の悩みを解決

両方の機能を利用することで最大の効果を得られますが、開発運用支援ツールの機能だけを利用することも可能であり、様々なアーキテクチャと組み合わせて利用することもできます。

## DBFlute セットアップ方法
1. [Maven DBFlute Plugin でコマンドからセットアップ](http://dbflute.seasar.org/ja/environment/setup/maven.html "Maven DBFlute Plugin でコマンドからセットアップ") ※Java8 (1.1.x) はこちら
    - Maven の pom.xml に必要な情報を記述し、DBFluteクライアントを作成します。
2. [EMecha (Eclipse Plugin) で Eclipse にてセットアップ ](http://dbflute.seasar.org/ja/environment/setup/emecha.html "EMecha (Eclipse Plugin) で Eclipse にてセットアップ ") ※Java6,7 (1.0.x) はこちら
    - Eclipse上でウィザード画面から必要な情報を入力し、DBFluteクライアント作成とDBFluteモジュールのダウンロードと配置が可能です。 (Java版の1.0.x用のみ、Java8の1.1.xからは別の方法で)
3. [テンプレートを利用して手動でセットアップ ](http://dbflute.seasar.org/ja/environment/setup/plain.html "テンプレートを利用して手動でセットアップ ") ※.NET(C#) or Java8でMaven使わないならこちら
    - DBFluteエンジンをサイトからダウンロードし、その中に含まれているDBFluteクライアントのテンプレートを手動修正します。他の方法が利用できないときのための方法です。

## DBFlute 使い方
#### チュートリアル
- [アーキテクトのためのチュートリアル](http://dbflute.seasar.org/ja/tutorial/architect.html "アーキテクトのためのチュートリアル")
- [ディベロッパーのためのチュートリアル](http://dbflute.seasar.org/ja/tutorial/developer.html "ディベロッパーのためのチュートリアル")
- [ひとめでDBFlute](http://dbflute.seasar.org/ja/tutorial/hitomeflute.html "ひとめでDBFlute")

#### 機能マニュアル
DBFluteの機能に関するマニュアル(機能マニュアル)です。
- [自動生成ツール](http://dbflute.seasar.org/ja/manual/function/generator/index.html "自動生成ツール") メタ情報からクラスを自動生成する
- [O/Rマッパ](http://dbflute.seasar.org/ja/manual/function/ormapper/index.html "O/Rマッパ") アプリケーション上でDBにアクセスする
- [現場フィット](http://dbflute.seasar.org/ja/manual/function/genbafit/index.html "現場フィット") 様々な局面で現場にフィットした支援
- [支援ツール](http://dbflute.seasar.org/ja/manual/function/helper/index.html "支援ツール") EclipseプラグインやMavenプラグインなど

#### リファレンス
機能マニュアルを補完する様々な参考資料(リファレンス)です。
- [DBMS Way](http://dbflute.seasar.org/ja/manual/reference/dbway/index.html "DBMS Way") DBMSごとの取扱い
- [DI Container Way](http://dbflute.seasar.org/ja/manual/reference/diway/index.html "DI Container Way") DIコンテナごとの取扱い
- [DBFlute Property](http://dbflute.seasar.org/ja/manual/reference/dfprop/index.html "DBFlute Property") DBFluteプロパティ(DBFluteの設定)
- [DBFlute Dictionary](http://dbflute.seasar.org/ja/manual/reference/dictionary/index.html "DBFlute Dictionary") DBFluteの世界で利用される用語の辞書
- [DBFlute Example](http://dbflute.seasar.org/ja/manual/reference/example/index.html "DBFlute Example") DBFluteを使ったプロジェクトの実装例

#### トピックス
DBFluteの周りを取り巻く様々なトピックです。
- [DB Design]( "DB Design") DB設計
- [Programming]( "Programming") プログラミング
- [Friends]( "Friends") 他のフレームワーク
- [Office]( "Office") 事務的な話
- [DBFlute.NET]( "DBFlute.NET") DBFlute.NET (C#)
