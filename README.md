# sample
以下をGPT-4で生成したものを公開する．

数字を使ったゲームをブラウザ上で作りたい。

1. プレイヤーに2以上10000以下のある自然数を与える
2. プレイヤーはその素因数のうち最も大きいと思うものを答える。
3. 正解ならcollect表示、不正解ならincorrect表示&正解表示してから次の問題へ移る。また、正解なら与えた自然数の桁数×10点、2番目に大きい素因数なら与えた自然数の桁数×5点、それ以外の素因数なら与えた自然数の桁数×1点、素因数でない数を答えた場合は0点をプレイヤーに付与し、現時点の総得点を表示する。
4. 次の自然数を与える(計10ラウンド用意する)
5. 10ラウンド終わったら最終結果の得点を表示
