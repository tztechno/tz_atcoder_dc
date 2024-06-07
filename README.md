# tz_atcoder_dc

```
https://kazmax.zpp.jp/cmd/d/dc.1.html

https://ja.wikipedia.org/wiki/Dc_(UNIX)
```

<br/><br/>

```
!tr '\n' ' '|awk '{xxxxxxxxxxxxxxxxxx}'
!tr '\n' ' '|awk '{if($1==substr($2,1,length($2)-1))print"Yes";else print"No";}'

dcは、デスクトップ計算機(Desk Calculator)のための逆ポーランド記法のプログラムです。以下がそれぞれのコマンドの意味です。

p - プリントスタック:スタックの最上位の値を出力します。
t - トランスポーズ値:スタックの2番目と3番目の値を入れ替えます。
a - 算術演算:スタックの最上位の2つの値を使って四則演算を行います(+,-,*,/,%等)。
c - 計算と表示:スタックの最上位の値を計算して表示します。
l - 負の値に:スタックの最上位の値の正負を反転させます。
f - 呼び出し:ユーザ定義関数を実行します。
q - quit:dcを終了します。

sedは、ストリームエディタで、テキストの置換や削除などの処理を行うUNIXのユーティリティです。
```
### latest

---
```

```
---
```

```
---
```

```
---
```

```
---
```

```
---
```

```
---
```

```
---
```
python
!python3 -c "print('YES' if int(input()) in [7, 5, 3] else 'NO')"
awk
!tr '\n' ' '|awk '{if (($1-7)*($1-5)*($1-3)==0) print "YES";else print "NO";}'
sed
!sed 's/7\|5\|3/YES/;s/1\|2\|4\|6\|8\|9/NO/'
```
---

