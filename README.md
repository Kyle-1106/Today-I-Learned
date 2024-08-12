# Today-I-Learned
毎日学んだことをアウトプットしていく(2024/7月スタート)


# 2024年7月

## アプリケーション設計
アプリケーションレベルで設計ができるように、まずはいいコード悪いコードで学ぶ設計入門を読んで
ソースコードレベル、クラスレベルでどのようなクラスを設計するべきかを学ぶ。

### 基礎的な設計、コーディングのお作法を学んでコードレビューチェックリストを作成
[いいコード悪いコードで学ぶ設計入門](https://gihyo.jp/book/2022/978-4-297-12783-1)を読んで、設計の基礎的なお作法とソースコードの書き方について学んだ。
その後に特に、ソースコードの書き方を学ぶという面で、[リーダブルコード](https://www.oreilly.co.jp/books/9784873115658/)を読んだ。
最終的なアウトプットとして、本で学んだこととネット上の有益な記事から引用して、自分なりのコードレビューチェックリストを作った。
これは、自分がコードレビューを実施する際に確認する観点に漏れがないようにするため、コードレビューをしてもらう際には、レビュー前に事前確認をするために作成した。

こちらに記載↓

設計/コーディング/コーディングチェックリスト.md
これは所属企業にも展開して、品質向上に高めた。

## システム設計

### システム設計で考えなければいけないこと
上記でソースコードレベルにおける設計で気をつけなければいけない基礎的なお作法については学ぶことができた。ただ、要件定義〜基本設計までの経験がほとんどないので、
そもそもソースコードレベルの前段階である、「システム全体の設計をするにはどんなことを考えないといけないのか」に対する自分なりの知見が全くないので、学ぶことにした。
そこで、[システム設計のセオリーと実践⽅法がこれ1冊でしっかりわかる教科書](https://gihyo.jp/book/2023/978-4-297-13791-5)を読んで、
インフラレイヤーも含めた、システム設計全体で何を考えないといけないのかを表面的に理解できた。
ただ、この本は入門書なので、これから深く学んでいく必要がある。



# 2024年8月

## PJ管理をする上で考えないといけないこと
8月から新しい案件を任されそこではメンバーは２人だが、PLポジションを任されたので、PJ管理をする上で考えないといけないことなどについて学ぶ。

##　PJ管理をする上でのテクニカルスキル習得
まずは[新任リーダーのためのITプロジェクト管理入門](https://jrqssjp.udemy.com/course/team-leader-basic/learn/lecture/25435140#overview)を視聴して、PJ管理をする上でどんな資料を作成するべきなのか、
何を管理しないといけないのかという基礎的なことについて学んだ。前PJでサブリーダポジションをやっていたので、概ね把握できていたことではあるが、数箇所学びになることがあった。

## API設計
７月までのPJでAPIを開発したが基本的には設計書に従って実装する形だったので、いざ自分で１からAPIを実装するとなると何を考えないといけないのか、基本的なAPI設計の決まりについて理解していなかったので、
自分が１からAPIを実装するために必要な知識を特に[Web API: The Good Parts](https://www.oreilly.co.jp/books/9784873116860/)を読んで学んだ。

## Vueのキャッチアップ
Vueの案件にアサインされたので、Vueのキャッチアップを行う。すでにAngularの経験はあるのでフロントエンドの基礎的な考え方は身についている。
Vueの記述に慣れるのと、Piniaなどの状態管理ライブラリの使用法について学習する。
まずはPJに既存のソースがあるのでこちらを理解していきながら、補足として以下のUdemyの講座を受講する。
[超Vue.js 完全ガイド2024 (Vue Router, Pinia含む)](https://jrqssjp.udemy.com/course/vue-js-complete-guide/learn/lecture/42562630#overview)

