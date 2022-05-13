# seibaribot
- 身内のサーバーで使うことを目的としたbotです。
- 開発段階のためバグや唐突な仕様変更があります。
## メインコマンド
### !ping
テスト用コマンドです。pongが返ってきます。
### !giratina
テスト用コマンドです。ギラティナの画像が返ってきます。
### !help
どんなコマンドがあるか見れます。
### !bokuseku
ボイスチャンネルに参加している状態でこのコマンドを使うと、課長と恋の実験室を流します。
### !chiibakun
なのはな体操の動画のリンクを貼ります。
### !falco(!syai !faruko)
ファル子☆面白画像集チャンネルに貼られた画像やテキストをランダムで返します。
## !inm
聖バリさんがいまだに淫夢ごっこをします。
### !kaosu
@kaosu_picから最新の画像を貼ります。
### !komachan
@komachan_picから最新の画像を貼ります。
### !lucky
@LuckyStarPicBotから最新の画像を貼ります。今は画像のみですが動画にも対応できるようにしたいです。
### !raika
Twitterをやってるときの指の動作またはスマートフォンを凝視するという行動が同じだけなのであって容姿がこのような姿であるという意味ではありません
### !twitter
Twitterの検索を使って画像を返します。
たとえば`!twitter 猫`と打つと、Twitterで猫と検索した時に表示されるツイートの画像を送信します。

`!twitter from:@hikakin 猫`みたいなこともできます。

TwitterのJSONの仕様がよくわかってなくて、画像が返ってこないときがあります。そもそも検索したツイートがないか、検索ワードがでかすぎると返されないっぽいです。`!twitter ウマ娘`だと何も返ってこないけど`!twitter アグネスタキオン`だとひっかかる場合がありました。
## 音楽系コマンド
### !join
ボイスチャンネルにbotを追加するためのコマンドです。コマンドを使う人がボイスチャンネルに参加している必要があります。
### !leave
ボイスチャンネルからbotを退出させるコマンドです。
### !play(!p)
曲を流すコマンドです。
大抵のサイトに対応していますが、ニコニコは再生までにかなり時間がかかります。近いうちに改善します。

リンクでの再生のほか、検索ワードでの再生も対応しています。

再生中に曲を追加するとキューに追加されます。
### !queue(!q)
キューを表示するコマンドです。まだ開発中です。

キューの表示はできませんが、キュー自体は機能しています。
### !nowplaying(!np)
再生している曲の情報とリンクを表示するコマンドです。バグがあります。
### !skip
次の曲を再生するコマンドです。
### !stop
曲を止めるコマンドです。キューもリセットされます。
## 言葉狩り機能
言葉狩りをして画像やテキストを返します。
以下の言葉に対応しています。
- ドナルド
- 死んだ
- ゆるゆり
- 一週間
- バキ
- big brother
- DJ
- メタ
- 風呂
- ランキング
- おはよう
- いい曲
- やんぱ
## その他の機能
音声ファイルを動画に変換する機能があります。
mp3_to_mp4チャンネルに音声を投げると自動で変換されます。
スマホアプリで音声を聴くのに使えます。

