# ja-novel-formatter

## overview

This application formats texts by the Ja( = Japanese) novel writing rule, converting numeric characters to Kanji Numerals.

*Public Domain.*

---

## 概要

　半角数字と全角数字を漢数字に置換したりして、日本の小説の書き方の規則(ルール)で文を直します。

　*パブリック ドメインです。*

　*不具合が有るかもしれないので、利用は自己責任でお願いいたします。*

　半角数字と全角数字を漢数字に置換したい場合、各行の全角空白の字下げを全て、または、一部、忘れているのを直したい場合、文を縦書き表示に対応したい場合などに役立つと思います。

　ただし、読点(、)や句点(。)の後ろ以外で改行している場合は、正しく整形できません。

　整形後、目視で自分で見直してください。


　チェック ボックスにチェックすると、半角ドット(.)を全角ドット(．)に置換しますが、半角ドット以外の半角記号は全角には置換しません。

　縦書き表示すると、半角記号が不自然に表示される場合が有ります。


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


　、改行の後の半角空白や全角空白の連続を除去します。


　半角数字と全角数字を漢数字に置換します。

　半角ドット(.)を全角ドット(．)に置換します。

　ただし、整数部が千垓の十倍以上の数に相当する25文字以上の数字の場合は、〇から九までの漢数字の羅列に置換します。

　また、整数部が2文字以上の数字で第1文字目が半角数字のゼロ(0)か全角数字のゼロ(０)の場合も、〇から九までの漢数字の羅列に置換します。

　また、1文字だけの半角数字ゼロ(0)や全角数字ゼロ(０)を零に置換します。

　そして、チェックを外せば、半角数字と全角数字を漢数字に置換しませんし、半角ドット(.)を全角ドット(．)に置換しません。


　半角数字を全角数字に置換します。

　半角ドット(.)を全角ドット(．)に置換します

　ただし、チェックを外せば、半角数字を全角数字に置換しませんし、半角ドット(.)を全角ドット(．)に置換しません。


　半角英字を全角英字に置換します。

　半角ドット(.)を全角ドット(．)に置換します

　ただし、チェックを外せば、半角英字を全角英字に置換しませんし、半角ドット(.)を全角ドット(．)に置換しません。
