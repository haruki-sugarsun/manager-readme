Hi, I'm Haruki
==============

_STILL DRAFT: 2020-04-06_


# この文書について
2018年に何やら（一部で）流行っているのをみて、
自分もやってみようと思ったのがきっかけなので、
fork treeをリスペクトして日本語で書くことにします。

特にマネージャーという立場は、多くの人に影響を与えることが仕事のうちなのですが、
同時に個々の特殊化が強い内容のため、
マネージャー本人も、そして部下を含めて周りのメンバーも、
何を期待すればいいのか、何を期待されているのか混乱しがちだと思います。

それを解決することは簡単ではないでしょうが、
自分自身の考え方や事情を共有することで、
その助けになればと思います。
以下では、マネジメントに限らず、
私が仕事に対してどのように考えているか、
何を重要だと考えているか、
あるいは何を重要ではないと考えているか、などを徒然なるままに書いています。

基本的には聞かれたら（聞かれなくても）喋っていることとと同じ内容のはずです。



# 立場と仕事内容について

私は2020年の4月現在で、副室長という肩書・立場であり、
開発1室という組織内のチームを複数統括する立場です。

また、同時に、開発チームとしては東京と福岡にまたがる
拠点ごとに大体同規模の

ある立場では10人程度。またある立場では20人程度をまとめる立場である、


仕事内容・役割としては、
周りがどう考えているかは置いておいて、
自分自身の認識は
Engineering Managerであり、People Managerがprimary roleだと思っています。


エンジニア組織を見ている以上、
良くも悪くも、技術的な話題や議論には参加できるようになりたいと思っていますが、

技術面や個々の判断については正直、メンバーに頼ることのほうが多いはずです。
ただ、参加しているメンバーとしては、説得力のある内容であってほしいとは思っています。


開発観点の好き嫌い、やりがちなパターンは私も持っていますが、
Engineering Managerとしては、個別の実装についてベストな判断を行う自信もありませんし、
適切な立場にもないと考えています。


一方で、個人やチームに閉じない
後方から、あるいはサイドから援護・調整をすることは仕事だと思っています。
個人がそれぞれの
チームが
チームという存在が勝手に意思や意見を統一することはないので、リーダーとしての役割にはチームの意思を作り、仮想的に代表することだと思っています。
そして、組織図上に存在する組織のリーダーはマネージャーなので、この立場と役割も
開発チームである以上、ここに総意としての技術的な判断が入ってきています。


# なんとかマネジメントについて

前節で、私が何をしているのか、しているつもりなのか、
について書きました。

一般的にマネージャーが
マネジメントするものが多岐にわたると思われている、あるいはそう理解している人が
（management, manager, leadなど）

自分自身としてかかわる範囲で、
* People Management
* Product Management
* Project Management
* Development Lead

などなどがあるかなあ、と思っています。
（本当は、<https://qiita.com/hirokidaichi/items/95678bb1cef32629c317>を全部読みたいのが私です）


それぞれはさらに特殊化する話題だと思いますし、
正直、私はどの分野でも理解があるとは思えないので、
ここでは各マネジメントの内容には立ち入りませんが
、
私はそのくらいの区別をしているよ、ということが伝われば助かります。

よって、それぞれにはそれぞれのスペシャリストがいるはずだと思っています。
場合によって、同じ人が兼任していることももちろんあるでしょうが、
本質的にはそれぞれがせめぎあう部分があり、マネージャー自身にも、周りのメンバーにも難しさを感じさせていると感じます。


例えば前節で触れたような個別の実装の例であれば、
Engineering Manager と Development Lead をたまたま兼任している人が、
People Managementを行いながら、個別の実装にも携わっていること自体はあり得ると思います。



# 具体的な仕事内容
## 組織を維持すること
### 1 on 1
## 採用
### 情報発信
## Product Decision の（ざっくり）技術面支援
## Project Management の（ざっくり）技術面支援
## 僕がやらないことについて
（Fork もとの README でこれはよいな、と思った部分なのでタイトルそのまま）
 

# 仕事上の方針と意見
## コミュニケーション
## 


# その他思想


# 参考資料



## Miscellaneous Facts
* I implemented <https://github.com/haruki-sugarsun/markdown_editor> to write this document.
  * Since I'm too lazy to search for a good tool, even though I know that some JS implementations exist.
* I forked the repo in 2018. and long time has passed to start writing.
  * 根本的に文章を書き始めると長くなる質なので、書き始めるのに腰が重いという面もあります。


## Other Resources
* <https://managerreadme.com/readme/singing_hacky/z2q2je>
* <https://sites.google.com/site/harukisato1031/home>


-----

_ここくらいまで自分の言葉に変換中_

-----



僕は Engineering Manager / Architect として仕事をしています。
サービスの全体のアーキテクチャの整合性、誰にどのような仕事をしてもらうか、というようなことについて責任をもっています。

また、技術的な側面から、サービスを運用していくためのあれやこれやをやります。

そして、センター全体に関する仕事とか、会社全体の技術的なことに関する仕事とか、まあそういうのもぼちぼちやっています。

# マネージャーとしての進め方について

基本的に、各メンバーのスキルが上がるような仕事を振りたいと考えています。そのためには、その人がやったことがないような仕事を振りたいと考えています。
やったことあることだけを延々とやっていても人は成長しづらいものですからね。

僕個人は飽きっぽいので、いろんな仕事を体験したいと考えていますが、人によっては、同じ仕事をずっとやるほうが性に合ってるという場合もあるでしょう。
そういう場合については、言ってくれれば調整します。

# チームワークとかについて

チームワークは重要ですね。
Trust and Respect でやってくれ、というお達しを CTO からもらっているから、そういうふうにやっていければ良いと思っています。

# 僕が普段、何をやっているかについて

僕が普段やっているのは以下のようなことです。

* 社内で今後利用しそうなツールの評価とか
* 中途社員の書類審査
* 中途社員のコーディングテストの評価
* 中途社員の面接(これはあんまやってない)
* 1 on 1
* DD とか
* Planner のお悩み相談を聞いたり
* 関連する wiki page のモニタリング。
* メンバーの github のアクティビティを眺めたり
* 業務がスムーズに回ってない場合に、他の部署との調整
* 社外向けのプレゼンとか。パネルディスカッションへの登壇とか。
* 技術勉強会に参加して、名刺を交換したり。。

他にもいろいろやってますけど、なんか細々としていて、忘れてそうなので、思い出したら追記します。

# 僕がやらないことについて

基本的にコードは書きません。プロトタイピングとか、なんかちょっとしたツールの開発しかしません。
実際にコード書いてみないとわからないことも多いので IDE を開いていることも多いですが、基本的には大したコードは書いていません。

僕がやっている仕事は「今日発生して明日までに仕上げる必要があり、かつ時間が5時間かかる仕事」みたいなのが多いので、締切がある仕事をやることが難しいからです。

コードレビューも基本的にしません。場合によってはやります。

# チャットについて

業務用のチャットグループができた場合は僕を招待してください。招待してもらわないとなにか問題があったときに、サポートすることができません。
エンジニアが自分しかいないグループとかの場合は僕と合わせて席が隣の人とか、適当な人を何人か招待してください。自分が休みのときとかにサポートしてもらえたりするかもしれません。

個別チャットを Planner がやたらしてくる場合は、グループを作って会話するように依頼してください。

# コードレビューについて

コードレビューは、必要なのでやってください。コードレビューは3つのぐらい役割があると思います。
「技術的知見の共有」「サービス全体を把握するため」「コードの品質を高めるため」とかそのへん。

基本的にコードレビューはコストがかかるので、コストを圧縮するように工夫をしましょう。

# 残業について

基本的に、残業はしないですめばしないほうがいいと思っています。
僕自身、この会社に入ってからほぼ残業していません(やっぽと飲みに行こうってことになっててやっぽの仕事が終わらないで待ってるときとかを除く)。

チームメンバーが残業せざるをえないような状況になるのは基本的にはマネージャーの敗北だと僕は考えています。残業しないといけないような状況になったときはマネージャーに相談してください。うちのチームは結構人数がいるし、全員が仕事でパツパツ、という状態にはならないようになっているので、誰かがヘルプに入ることが可能なはずです。

# スケジュールについて

スケジュールは、マネージャーがざっくりとした見積もりを出すことも多いです。基本的に余裕をもって進められる期間プラスアルファで見積もりを出しているつもりですが、短いと思ったらいってください。
無理をする必要はないです（ダラダラやってていいという意味ではないです）。

基本的にソフトウェアの開発は、過去に作ったものをもう一回作ることがないので、いざ実際に作ってみたら時間がかかる項目が判明した! みたいなことは珍しくありません。
まあ、そういうもんですよね!
なので、まあスケジュールを途中で伸ばすことは、まあしょうがない面があると思いますので、スケジュールに遅れそうな時は早めに言ってください。
締切のその日になってから「間に合わない! 助けて!」っていわれても何もできることがないです。

ただもちろん、同じ仕事をする場合、短いスケジュールで実装出来る人のほうが評価は上がりやすいです。

# チームの目標について

僕らのチームは B2B の開発を担当していますので、売上を最大化できることがまず第一の目標になります。
売上の向上を、技術的な面から支援していくことが僕らの役割です。

# ぼくの働く時間について

子供を保育園に連れて行ってから会社に来ているので、だいたい 10 時ぐらいには会社にいて、19時ぐらいに帰ります。
時々は保育園のお迎えを僕がしないといけない日もあるのでそういう場合は17時に帰る時もあります。

あと、GABA に行ってからくる時もあるのでそういう場合は昼ぐらいに来ます。

# なんか相談ごととかあるときについて

僕の予定は、時期によっては割と埋まってますが、適当に声かけてもらえればあけるので、声かけてください。

# チームの懇親会とかの開催について

時代の趨勢的に、あんまチーム飲み会をゴリゴリ開催するみたいな風潮じゃないので得にマメに開催する予定はないですが、やりたい人がいたら幹事をしてくれたら参加はします。

一緒に飲みに行きたい人がいたら誘ってくれれば行きます。飲み会の誘いは基本的に断らないです。
サシでも大丈夫です。

あとはまあ、歓迎会はやります。

ランチは適宜いきましょう。サシとかだったら奢りでいいです。

# キャリアプランについて

人によって、今後はマネージャーになりたいと思ってる人もいれば、現場でコードをずっと書いていたいという人もいますね。
まあ、どっちも面白いことはあるし、辛いこともあるので、どっちが良いとも言えませんね。。

僕は自分がマネージャーになりたいと思ってなったわけではないですが、なんか流れでそうなりました。別に嫌じゃないのでやってます。
複数のプロダクトを見れるのは楽しいし、アーキテクチャの設計とかをメインでやれるのは楽しいですが、細かい部分についての議論に参加する暇がなかったり、実装をしている暇がないのは少しさみしくもあります。

この section には得にオチはありません。

# マネージャーの権限について

基本的に、うちの会社ではマネージャーはそんなにすごい権限があるわけでもないし、社内のことも知らないことが多いので、わからないことがあったら室長に聞いてくれ!
ってなることも多いです。まあそんなもんですね。

マネージャーじゃない人が思ってる以上に権限がないのが僕です。

# 1 on 1 について

1ヶ月に一回、30分から1時間程度やっています。

キャリアプランの話や、やりたいこと、やりたくないこと、人間関係、などなど。ざっくばらんに話しましょう。

進捗確認など、マネージャーのためにやる会ではなくて、メンバーのためにやる会です。

基本的には、オープンな雰囲気でやったほうが話やすいとおもうので、フリースペースでやるのが良いと考えています。
ただ、人がいるところでは話しづらい話もあると思うんで、3ヶ月に一回ぐらい、スタディブースでやることにしています。

スタディブースで話したほうが話やすいことがある場合には言ってください。

1 on 1 については、僕の時間があいたタイミングで突発的にやっています。
スケジュール入れてやると、そのタイミングまで話す内容を貯め込んでしまう可能性があっていやんだからです。

# 飽きた

なんかこれ書くのに飽きてきたのでここで終わりです。
気がむいたら追記します。

