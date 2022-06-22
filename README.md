# blackjack
とらんぷげーむのブラックジャックをつくる

### ルール
+ プレイヤー(自分)とコンピュータ（ディーラー）には、最初にそれぞれ2枚カードが配られます

    ※この時、コンピュータ（ディーラー）の1枚目のカードは見えるようになっています
    ※プレイヤー（自分）自身の手札はもちろん見れます

+ プレイヤー(自分)：自分で次のカードを引くかどうかが選べます

+ コンピュータ（ディーラー）：手札が16ポイントを超えていなければ(16ポイント以下ならば)必ず引きます

    ※手札が17ポイント以上になった時点で引けなくなります

+ Aは1ポイント、Jack,Queen,Kingは10ポイント、Jokerは無しとします

+ 手札が21ポイントを超えずに、より21ポイントに近い方が勝ちとする

    ※プレイヤー（自分）は21ポイントを超えた場合、負けが確定する：バースト
    ※両者とも21ポイントを超えてバーストした場合、コンピュータ（ディーラー）の勝ち

