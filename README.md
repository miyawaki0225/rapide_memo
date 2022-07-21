# rapide_memo

リーンかんばんを用いたアジャイル開発（スクラム開発）
- チーム構成
  - アジャイル開発経験がある杉原が、スクラムマスターを担当させていただきます。
- タスク管理をかんばん方式で行う
  - 「リーンかんばん方式」
  - 「スプリントバックログ」
- デイリースクラム
  - 朝に15分程度MTG。
  - 前の日にやったことと、今日やることをシェア（Todo, InProgress, Close）
  - 今困っていることをシェア→ これらを行うことにより1スクラムのスケジュール調整やチームメンバー間の業務の調整をおこないます。
- スプリントMTG（ミーティング）
  - スプリント最終日に1時間ほどのミーティングを行います。
  - 今回のスプリントの振り返り、進め方や技術に関するシェア
  - 次回のスプリントでやることの決定、進め方調整の決定

参考資料  
[アジャイル開発とは？　特徴とメリット・デメリット、スクラムまで徹底解説](https://monstar-lab.com/dx/solution/about-agile_methods/)
[5分で分かる、「スクラム」の基本まとめ](https://atmarkit.itmedia.co.jp/ait/articles/1208/07/news128.html)

- 新しい言語するときは結構公式doc見る、ネットで調べる以外、Kindle Unlimitedに登録しているので、がーって言語やFWでタイトルを調べてとりあえず3,4冊目次みて、ななめよみしたり、ネットでも本でも一冊（or 1記事、1シリーズ）読んだら簡単なアプリケーションが作れる系のものを選んで、作りながら読んだりしている気がします。

## 命名規則系
- [新人エンジニアに役立った命名規則6選とアンチパターン3選 - Qiita](https://qiita.com/tatsuya_1995/items/4b706fc40fe2f300bbc0)
- [データベースオブジェクトの命名規約 - Qiita](https://qiita.com/genzouw/items/35022fa96c120e67c637)
- [DB設計基礎の「キ」　命名規則](https://qiita.com/tatsuya_1995/items/4b706fc40fe2f300bbc0)
- [データベース列名の名前付け（英単語での）採用例を集めてみた](https://qiita.com/otagaisama-1/items/4d7e2eb5c274e9fce664)
- [プログラミングでよく使う英単語のまとめ【随時更新】](https://qiita.com/Ted-HM/items/7dde25dcffae4cdc7923)


## データベース
- [【DB/SQL】データベースやらSQLやらで悩むこと](https://qiita.com/rhap/items/5c82cb6ba4a8f1d541bb)
- [データベース設計の基本の進め方！ポイントとあわせて解説](https://hibiki.dreamarts.co.jp/smartdb/learning/le-sp211202-3/)
- [やさしい図解で学ぶ　ER図　表記法一覧](https://qiita.com/ramuneru/items/32fbf3032b625f71b69d)
- [Laravel Eloquentでリレーション](https://qiita.com/mtakehara21/items/3cef9d12869d162e1ce9)


## Linux
- [grep](https://eng-entrance.com/linux-command-grep)
- [よく使うLinuxコマンド](https://qiita.com/arene-calix/items/41d8d4ba572f1d652727)
- [Linuxコマンド：Windowsコマンド対応表](https://qiita.com/asmin/items/d53e71ed98a377ca7823)
- [Chromeをvimライクに使えるようにするvimium](https://qiita.com/satoshi03/items/9fdfcd0e46e095ec68c1)


## テスト
- [テスト仕様書の作り方大公開：テスト設計の手順とセオリー](https://elecs-softwaretest.com/colum/%E3%83%86%E3%82%B9%E3%83%88%E4%BB%95%E6%A7%98%E6%9B%B8%E3%81%AE%E4%BD%9C%E3%82%8A%E6%96%B9%E5%A4%A7%E5%85%AC%E9%96%8B%EF%BC%9A%E3%83%86%E3%82%B9%E3%83%88%E8%A8%AD%E8%A8%88%E3%81%AE%E6%89%8B%E9%A0%86/)
- [テスト観点レビュー時のチェックポイント](https://medium.com/wingarc/%E3%83%86%E3%82%B9%E3%83%88%E8%A6%B3%E7%82%B9%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC%E6%99%82%E3%81%AE%E3%83%81%E3%82%A7%E3%83%83%E3%82%AF%E3%83%9D%E3%82%A4%E3%83%B3%E3%83%88-932adf70111d)

- [SHIFT](https://service.shiftinc.jp/service/softwaretest/inspection/)
- [SHIFT_資料](https://service.shiftinc.jp/download/)
- [SHIFT_会談](https://industry-co-creation.com/report/46321)

- [失敗しないテストケースの作り方と、効率よくテストを進める方法](https://qangaroo.jp/info/test-case-plan-do/)
- [単体テストの観点とは｜漏れのない洗い出し・網羅性がポイント！](https://biz.techvan.co.jp/tech-quality/quality-blog/000242.html)
- [【実践】ロジカルシンキングの基礎、『MECE』で考慮漏れを防ぐ（エンジニア向け）](https://taako-biz.com/se-mece/)

## 障害対応
- [バグ報告書 テンプレート（書き方とサンプル例）](https://notepm.jp/template/bug-report)
- [ウェブ技術者がもらってうれしいバグ報告書のテンプレート](https://dyno.design/articles/bug-reports-kind-for-web-developers/)

```console
Step1 影響範囲の確認
 - このバグがどれくらいのユーザに影響を及ぼしているのか
  - iOS, Android, PC, - OSやブラウザの問題なのか
  - 1人のユーザでのみ発生しているとなのか、全員に発生しているのか
  - etc.

Step1.5 えらいひとに報告（影響範囲、バグの深刻さ）

Step2 発生した経緯・原因を確認する
 * どの画面で発生していますか？
 * キャッシュクリアとか、なんかしましたか？/したらなおりましたか？
 * どういう操作をしたときに発生しましたか？（再現手順）
 
※ 「原因ってなんですか？」とユーザに聞いても答えは返ってこない
* ヒアリングをする場合、
同じエラーが発生する原因となりそうなものを頭の中でピックアップしていって、
その原因のときどこの段階でエラーが発生しているかしていないかをアテをつけて
ヒアリングしていく必要があります。

Step3 推定した原因が実証の原因として合っているかどうかを確認する。
 * レスポンスをみたり
 * DBをみにいく
 * ログをみたり

Step3.5 事象の詳細と原因について報告・1次対応と、恒久対策（根本的な解消の方法）についてえらい人に相談する
* なにか修正や対応をする前にかならず報告・判断を仰ぐ。自分の判断が誤っている場合もある。

Step4 1次対応を行う。
Step5 根本的な解消の方法について議論・決定。
Step6 必要な場合、事故報告書・経緯書などを作成。（原因・その時の対処・今後の対策・補填）
Step7 Step6で合意をとれた内容を元に、恒久対策（根本的な解消の方法）を行う
```

- [障害対応の流れ：事前準備、一次対応、恒久対策の実行](https://www.rworks.jp/monitoring/monitoring-column/monitoring-design/25595/)


- [要件定義](https://notepm.jp/template/requirement-definition)
- [要件定義と要求定義の違い](https://qiita.com/sunstripe2011/items/61df719fb1f6178b2605)


- [Spring boot における静的ファイルのアクセス優先順位 - Qiita](https://qiita.com/TKR/items/4ec3733d44c9d2b618ee)
- [知ってるようで知らない YAML のご紹介](https://engineers.ntt.com/entry/2021/09/10/100708)
- エディタの便利機能：矩形選択(VSCodeだと Defaultは Alt + Ctr)


## Git
- [Gitソースコードのバージョン管理や 共同開発を可能にするツール](https://prog-8.com/courses/git)
- [git](https://qiita.com/RubyLrving/items/6ae8bff333d72f8cb21e)
- [Git-flowって何？ - Qiita](https://qiita.com/KosukeSone/items/514dd24828b485c69a05)
- [Git-flowをざっと整理してみた | DevelopersIO](https://dev.classmethod.jp/articles/introduce-git-flow/)
- [【Git-Flow+PR】プロジェクトをGit-Flowに移行してみた。](https://zenn.dev/akino/articles/1dcecd60009dbb)

（参考）チケット駆動開発
- [チケット駆動開発を上手に運用するためのプラクティス（ゲストブログ）](https://www.atlassian.com/ja/blog/tidd-part2)
- [チケット駆動開発の解説～タスク管理からプロセス改善へ](https://www.slideshare.net/akipii.oga/ss-250996606)
- [https://azu.github.io/slide/workflow/git-redmine-tidd.html#slide1](https://azu.github.io/slide/workflow/git-redmine-tidd.html#slide1)


```console
▼ コマンド安心表
clone,init,config,remote add
--- ↑ 基本的に最初の一回しか使わない
pull （こまめにpullするようにする）
push,branch,checkout,commit,log,diff,status,add
--- ↑ 気兼ねなく使ってOK
merge develop -> 作業中のブランチ (大丈夫。むしろこまめに)
merge 作業中のブランチ -> develop (気を付ける！github上でやってもらう方が安全)
reset --soft HEAD (commitの取り消し。commit前の状態に戻るので、編集した部分は残る。未pushのcommitに対してなら大丈夫。push後のcommitだと:まいった:)
reset --hard HEAD (気を付ける！最新のcommitを取り消して、編集したものも全部消す。)
fetch (pull使ってくれる方が嬉しい)
--- ↑ 気を付けつつ使う
--- ↓ なれるまで絶対使わない
revert
squash  (--squash merge)
rebase
```

## JavaScript
- [モダンフロント開発に必須の知識(ES2015~ES2022まとめ + 高階関数)](https://qiita.com/c-shiraga/items/33812799e4dc17d89b44)
- [エープリルフールなのでJavaScriptの信じがたい話をします](https://qiita.com/suin/items/461c096bef318a259c80)


## その他ツール
- [StackEdit　（webでマークダウン）](https://stackedit.io/)
- [TickTick(タスク管理ツール)](https://ticktick.com/home)
- [pocket](https://getpocket.com/ja/)

なんか刺激をもらいたいとき    
- https://dribbble.com/search  
- [SESで契約更新してもらうために現場に入る前にやること](https://qiita.com/yoshinyan/items/214d2cfd9a5a1c907cef)

```console
Eclipse, VSCode, etc.(エディタ)ってどのくらいできます？
Lv1 基本操作/コードとりあえずかけるマン（ファイル検索・jump系）
→ 開発環境構築済みだったら、コードかけるマンに徹せる
Lv2 開発環境構築自力でできる
→ PC与えられたら、自力でコードかくところまで這い上がってこれる
Lv3 ○○系（言語など）の拡張機能を把握している・使いこなせる（linter系）
→ 何か困ったときに、Lv1~2の人教えられるレベル感。コード書く時のお作法わかってますよ。
Lv4 プロジェクトでの開発環境構築の方針を決めることができる
→ 手取り足取り、Lv1~2の人教えられるレベル感。
（VS Codeだけかもしれないです。gitに.vscode をシェアしたりして、揃えたりすることアリ）
```

- CoC（設定より規約）ということばがあります 地でいってることで、有名なのはRails, CakePHPだとおもうのですが、フレームワークつかってると、Timestampを有効にしていると、created_atやdeleted_atのカラムが追加されたりすること、テーブル名は複数系でとか、一覧ページは複数形、詳細ページのファイルは単数形で…とかいろいろ自動生成され、そこに「暗黙のルール」みたいなのが大量に遭遇します。なんで？ってなると思うのですが、それこそがCoCですRuby on Rails勉強するのがてっとりばやいんですが、下火感がいなめないんで、Railsでどんなことしてるのか。設定より規約をどう実現してるのかをサーっと下の記事群でも見れるんでよければ見てください。覚えていて困ることはないというか、もはやWebAppつくってたら勝手に身についていきます。
https://www.techscore.com/tech/Ruby/Rails/quick-start/Rails1/


