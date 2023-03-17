# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|三代 伊知朗(Miyo Ichiro)|
|生年月日|1999/05/21|
|学歴|2022年 日本大学理工学部物質応用化学学科 卒業|

---

<!-- ## 保有スキル

- C# と Python を用いた自動化スクリプトの開発
- C# のテスト
- COBOL→Java へのマイグレーション及び COBOL, Java での開発
- JUnit と Mockito を使用した Java ソース及び自作ツールのテスト
- Maven を使用したビルド
- PostgreSQL を用いた DB 操作 -->


---

## 技術スタック

### 言語
(言語のスキルを表現するのであれば、言語のバージョン、パフォーマンスを意識したコーディングテクニック、関連ライブラリなどの組み合わせ経験などを書く)
**Go**
    - Go 1.19 ~ 1.20を自己学習で利用。
    - Docker, PASETO, Viper, sqlc, Gin (それぞれ選定理由を語れるように)を利用した REST API の作成
    - JWT, PASETO, Gin, Viper, 後はlesson_goで使ってた標準のパッケージとか
    どう使ったか、工夫の内容を書く

**C#**
    - C# 10 ~ 11を業務および自己学習で利用。業務では変換ツールに対応していない予約後などに対応するためのツールを作成。
    - 自己学習では…
    - （GUI MVVM DDDで自己学習）
    なんでそのバージョン、技術なのか選定してなくても考えておく！！

**Java**
    - Java 17.（0.4.1）を業務で利用。システム固有のサブルーチンの作成、単体テスト、ツールで変換した Java コードの修正に使用。

**Python**
    - python 3.10 ~ 3.11を業務及び自己学習で利用。
    - プログラムの依存関係収集やファイルの読み書きを行う自動化スクリプトを業務で作成。
    なんでそのバージョン、技術なのか選定してなくても考えておく！！


**Ruby**
    - 2 年ほど前に簡易的なSNS（個人開発）を独学で作成。


**JavaScript/TypeScript**
    - Typescript 4.9.5

<p>
    <img alt="Go" src="https://img.shields.io/badge/-Go-76E1FE.svg?logo=go&style=flat-square" />
    <img alt="TypeScript" src="https://img.shields.io/badge/-Typescript-00008B.svg?logo=typescript&style=flat-square" />
    <img alt="Python" src="https://img.shields.io/badge/-Python-1E90FF.svg?logo=python&style=flat-square" />
    <img alt="Ruby" src="https://img.shields.io/badge/-Ruby-CC342D.svg?logo=ruby&style=flat-square" />
    <img alt="Java" src="https://img.shields.io/badge/-Java-007396.svg?logo=java&style=pflat-square" />
    <img alt="C#" src="https://img.shields.io/badge/-C%EF%BC%83-BA55D3.svg?logo=&style=flat-square" />
</p>

技術に関してはどこまでできるのか？
基本的なCRUD処理はできますよとか
自己PRとかに学習遍歴としてどんなことやったか書く
技術工夫



### フレームワーク・その他
**PostgreSQL**
    - 15.1を業務及び自己学習で利用。

**Docker**
    - 業務及び自己学習で利用。
    - プライベートのチーム開発ではDockerfileとdocker-composeを用いて...

<p>
    <img alt="rails" src="https://img.shields.io/badge/-Rails-CC0000.svg?logo=rails&style=pflat-square" />
    <img alt=".NET" src="https://img.shields.io/badge/-.NET-BA55D3.svg?logo=&style=flat-square" />
    <img alt="Docker" src="https://img.shields.io/badge/-Docker-1488C6.svg?logo=docker&style=pflat-square" />
    <img alt="Postgresql" src="https://img.shields.io/badge/-Postgresql-336791.svg?logo=postgresql&style=pflat-square" />
</p>
- 

---

## 職務経歴詳細

### 株式会社FIXER（2022/04〜現在）
保険系大規模行政システムのマイグレーション案件。
COBOL から Java への変換を担当。
どう取り組んだか、取り組みの工夫、考え方
業務してるときにくふうしてること
言語となんのパソコン
CI, CD 
使ってる媒体
職務経歴書に関しては必要最低限（言語とか工夫）
志望理由もめっちゃ聞かれる
数打つ
てっくぼうる
ぱいざ 人よさげ (紹介もあり)
新卒担当から中途の話も

- **プロジェクト規模**
    - 業務委託含めて 60 人以上
    - チーム： 10 人
- **プロジェクト詳細**
    - C#, Python を用いた自動化スクリプトの開発
    - COBOL から Java への変換
    - COBOL 及び Java を用いたツールの作成
    - JUnit 及び Mockito を用いた Java のテスト
    - Maven を用いたビルド
    - PostgreSQL を用いた DB 操作
    - 実行時エラーの解消
    - 変換後の Java にエンコード
    - テスト環境へのデプロイ
- **その他** 
    - Spring Boot で作成されたフロントエンドのテスト
- **プロジェクトでの課題**
    - 初めは COBOL も Java も経験がなく、学生時代は Ruby と JS しか経験していませんでした。そのため型の意識、Byte 型の扱い、文字コード（ shift-jis と utf-8 など具体的に）の意識などがほとんどわからない状態でした。
    とにかく理解することに努めました。知らない単語が出たら都度調べ、読んだ内容をコードやドキュメントに落とし込み、実際にどういう変化が起きるのかを試しました。それでもわからなければ有識者に対話するような形で理解を深めていきました。

    - 特に COBOL から Java への変換で問題が発生しがちだった（有識者がいない（３人しかいないうえにシフト制勤務）、納期が短い、単純に量が多い上に修正がされるべきところに修正がないなどの問題が発生していたため、一括で変換してデプロイするのはリスクが大きかった）


    - COBOL から Javaへの変換で、有識者の不足とドキュメントの管理不足により増員に際する知識の共有問題が難しくなっておりました。そこで以下のような対応も行っておりました。
      - タスクの洗い出しと優先順位付け
      - わかりづらいドキュメントの改善
      - なんか加えたり




    一つの文が長い
    学生っぽい文章を直す
    相手から見てどう思われるか


##

 
## 意欲・興味
- 成長していくことが自分にとってのモチベーションであり、知らなかった知識や考え方などを学ぶのが好きです
- 現在は開発職として技術力を磨きたいと考えており、将来的には自分の強みを活かして企画や設計、技術選定などの業務に挑戦したいです
- バックエンド開発が好きなので、バックエンドを中心にインフラやフロントなどの知識を身に着けたいと考えています

## 強み
非常に強い好奇心（ワードだけでも）
エピソード
課題
技術とカラメルと良い
性格面のはなしとか（好奇心、激務）

自己PR（）
＜大切にしている価値観＞
僕が日常で大切にしている価値観は「楽しい・気になるを止めない」ことです。

＜どのような価値を技術によって提供したいか＞
徹底的に互いが中長期的に利益や利便性を得られるような価値を提供したい。
例えばどういうデータを扱うのかによってDBだったり、アルゴリズムとか変わってくる。（速度であったり、データの安定性）
どれだけ堅牢なシステムを作成するかによって使う技術が変わってくる（シビアな金額の計算（保険、銀行）であればCOBOLみたいな浮動小数点の扱いが厳密な技術とか、クラウドでも堅牢な構築ができるAWSとか）




学習遍歴