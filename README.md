# ja-novel-formatter
This application formats text by Ja( = Japanese) Novel Writing Rule, converting numeric characters to Kanji Numerals.

Public Domain.

パブリック ドメインです。

日本の小説の規則(ルール)で文を直します。

半角数字と全角数字を漢数字に置換します。置換しない事もチェック ボックスで選択可能です。

ただし、千垓の十倍以上の数の場合は、〇から九までの漢数字の羅列に置換します。
ただし、1文字だけの半角数字ゼロ(0)や全角数字ゼロ(０)を零に置換します。

半角英字を全角英字に置換します。置換しない事もチェック ボックスで選択可能です。

各行の最初が1文字以上の全角空白や半角空白の連続の場合は1文字だけの全角空白の字下げに置換します。

各行の最後が1文字以上の全角空白や半角空白の連続の場合は除去します。

各行の最初の文字が全角空白でも「でもない場合は全角空白で字下げします。

1つだけの…を2つの……に置換します。
3つだけの………を4つの…………に置換します。
5つだけの……………を6つの………………に置換します。
ただし、7つ以上の奇数の…………………などは、偶数に置換しても、奇数と偶数を見分けるのが困難なので、置換しません。

1つだけの―を2つの――に置換します。
3つだけの―――を4つの――――に置換します。
5つだけの―――――を6つの――――――に置換します。
ただし、7つ以上の奇数の―――――――などは、偶数に置換しても、奇数と偶数を見分けるのが困難なので、置換しません。

会話文の、改行の後の半角空白か全角空白の連続と、改行を除去します。

会話文の後に地の文が繋がっていて混在している文は、全角空白で字下げします。

。」を」に置換します。
。』を』に置換します。

」や』の前の1文字以上の半角空白や全角空白の連続を除去します。

全角の？か全角の！の次が全角空白でも全角の？でも全角の！でも」でも』でも(でも)でも改行でもない場合は全角空白を挿入します。

。の後の半角空白や全角空白の連続を除去します。
