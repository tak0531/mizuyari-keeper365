■サービス概要

このサービスは、水やりや鉢替えの日にちをつい先延ばしにしてしまったり、忘れたりしてしまう方にLINEで通知を行い、植物を枯らしてしまったりしないようにするためのサービスです。

植物の成長記録も付けられるようにし、育てている植物に対して、さらに愛着を持ってもらうという目的もあります。

■ このサービスへの思い・作りたい理由

自分自身、植物の水やりを忘れて気に入っていた植物を枯らしてしまったことがあり、その経験を踏まえてこのサービスを作りたいというふうに思いました。

■ ユーザー層について

・水やりをよく忘れてしまう方 ・正しい周期で水やりをしたいと思っている方

■サービスの利用イメージ

・ユーザーは育てている植物を登録（最後に水やりを行った日、植物の画像なども登録できるように）

・登録した内容、季節に応じて、適切なタイミングでの水やり推奨日までの日数ををユーザーに提示し、水やり推奨日の当日にLINEで通知

・植物ごとに鉢替え日も、ユーザー自身で設定することができ、鉢替え日もLINEで通知が行くようにする

※通知は'LINE Messaging API'を使用して行う

■ ユーザーの獲得について

・X

・MatterMost

■ サービスの差別化ポイント・推しポイント

・水やりの通知などを行うサービスはあるのですが、LINEで行うというところが差別化ポイントです。

スマートフォンを持っている方であれば、LINEは1日に1回以上は目を通すと思います。それによりほぼ確実に、いつが水やりの日なのか、鉢替えの日なのかということが知ることができ、それらを忘れてしまうこともなくなるかと思います。

・ユーザーが登録した、植物と会話しているような雰囲気にする。

（「水やりの日です。」などではなく、「喉が渇きました。」や「水飲みたい。。」のような）

■ 機能候補

MVPリリース時

・サインアップ機能

・ログイン機能

・植物登録機能

・登録した植物を削除する機能

・水やり推奨日提示機能

本リリース時

・LINE通知機能

>植物と会話している風で

・植物の成長記録機能

■ 機能の実装方針予定

LINEでの通知機能

'LINE Messaging API'を使用して水やりの推奨日やユーザー自身で設定した、鉢替えの日になるとLINEが送られるようにする。 この時送られる内容は、上記したが、植物と会話しているかのような形式で送信するようにする予定です。