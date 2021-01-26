---
controls: true
touch: true
theme: "serif"
transition: "slide"
center: false
hideAdressBar: true
slideNumber: true
title: "指数対数関数"
logoImg: false
---

# 公営塾
# テスト対策勉強会

---

## 指数

指数って? {.fragment fade-in style="text-align:left"}

$2^3$，$3^4$などで数字が表されたときの右上の数字のこと {.fragment fade-in}

<aside class="notes">
今回のテーマは指数です。指数の定義をまずは確認してみます。
$2^2$，$3^4$などで数字が表されたときの右上の数字
$2^2$なら3，$3^4$なら4が指数です。今日はこの指数の性質について復習と，問題演習をします。
</aside>

---

## 整数の指数 {style="text-align:left"}

$a\neq 0$，$n$は正の整数とするとき {.fragment fade-in}

<span class="fragment fade-in">$a^n=\underset{n個}{\underbrace{a\times a\times \cdots \times a}}$</span>
<span class="fragment fade-in">$，a^{-n}=\dfrac{1}{a^n}$</span> 

<p class="fragment fade-in" style="text-align:right">$n=0$のとき，$a^0=1$</p>

<aside class="notes">
まずは整数($\cdots-2,-1,0,1,2\cdots$)の指数について考えましょう。
まず，は指数が正の場合について考えてみます。$a$は0でない数，$n$は正の数，つまり$1,2,3，\cdots$とします。$a^n$ ($a$の$n$乗）と書いたとき，これは$a$を$n$個かけた数を表します。例えば，$2^2$は$2\times2$，$3^4$は$3\times3\times3\times3$のことです。
次に，指数が負の場合を考えてみます。
さっきと同じ文字を使うと，$-n$は負の数です。このとき，$a^{-n}$は$\frac{1}{a^n}$，つまり，$a^n$の逆数になります。
指数が負の時は$-$が分数の棒になって棒の上に1が立つと考えると覚えやすいかもしれないですね。
最後に指数が0の時を考えてみましょう。
指数が$0$，tつまり，$a$の0乗は1になります。これは$a$がどんな値でも1になることに注意してください。
</aside>

--

## 問題演習・解説1

--

3TRIAL 299(1)～(5)

--

--

--

--


---

## 指数法則

$a,b\neq0$，$m,n$は整数とする{.fragment .fade-in} 

1. $a^m\times a^n=a^{m+n}${.fragment fade-up}

1. $a^m\div a^n=a^{m-n}${.fragment fade-up}

1. $(a^m)^n=a^{mn}${.fragment fade-up}

1. $(ab)^m=a^mb^m${.fragment fade-up}

<aside class="notes">
次に指数の計算について復習してみましょう。これは指数法則と呼ばれるものででした。大きく4つあります。
1つめ。底が等しい2つの数の掛け算は指数の足し算になります。
2つめ，艇が等しい2つの数の割り算は指数の割り算になります。
3つめ。
</aside>


--

## 問題演習・解説2

3TRIAL 300(1)～(4)

--

--

--


---

## 累乗根

<div class="fragment fade-in"style="text-align:left">$a>0$，$n$を正の整数とする</div>

<div class="fragment fade-in" style="text-align:left">$\sqrt{a}\cdots$$n$回かけると$a$になるような正の数
</div>

<div class="fragment fade-in" style="text-align:left">
※$n=2$のときは$\sqrt{a}$とかく
</div>

注：$(\sqrt[n]{a})^n2=a$，$\sqrt[n]{a^n}=a$ {.fragment .fade-in}

--

## 問題演習・解説3

3TRIAL 302，303(2),(3)

--
<!-- 2問目-->

--

<!-- 3問目 -->

--

<!-- 4問目　-->

---

## 累乗根の性質

$a>0$，$b>0$で，$m$，$n$は正の整数 {.fragment .fade-in}

1. $\sqrt[n]{a}\sqrt[n]{b}=\sqrt[n]{ab}$ {.fragment fade-in}
1. $\dfrac{\sqrt[n]{a}}{\sqrt[n]{b}}=\sqrt[n]{\dfrac{a}{b}}${.fragment fade-in}
1. $(\sqrt[n]{a})^m=\sqrt[n]{a^m}$ {.fragment fade-in}
1. $\sqrt[m]{\sqrt[n]{a}}=\sqrt[mn]{a}$ {.fragment fade-in}


--

## 問題演習・解説4

3TRIAL 304(2),(4),(5),(8)

<!-- 1問目　-->

--

<!-- 2問目 -->

-- 

<!-- 3問目 -->

--

<!-- 4問目 -->

---

## 有理数の指数

$a>0$，$m$，$n$は正の整数，$r$は正の有理数{.fragment fade-in}

1. $a^{\frac{1}{n}}=\sqrt[n]{a}${.fragment fade-in}

1. $a^{\frac{m}{n}}=\sqrt[n]{a^m}${.fragment fade-in}

1. $a^{-r}=\dfrac{1}{a^r}${.fragment fade-in}

--

## 指数法則 {style="text-align:left"}

$a,b\neq0$，$r,a$は有理数とする{.fragment .fade-in} 

1. $a^r\times a^s=a^{r+s}${.fragment fade-up}

1. $a^r\div a^s=a^{r-s}${.fragment fade-up}

1. $(a^r)^s=a^{rs}${.fragment fade-up}

1. $(ab)^r=a^rb^r${.fragment fade-up}

--

## 問題演習・解説5

3TRIAL 305(2)，(3),  (5)．306(2)，(4)

--

<!-- 2問目 -->

--

<!-- 3問目 -->

--

<!-- 4問目 -->

---

## 指数関数 {style="text-align:left}

<span class=fragment>$a\cdots$</span>
<span class=fragment style="color:red">0でない正の整数</span>

<span class=fragment>$y=a^x\cdots$</span> 
<span class=fragment style="color:red">指数関数</span>

--

## 指数関数の特徴 {style="text-align:left"}

1. $y$は常に正（$y$は-つかない）{.fragment fade-in}
2. $a>1\Rightarrow $<span style="color:red">右上がりなグラフ</span> {.fragment fade-in}
3. 点(0,1)，(1,$a$)を通る　{.fragment fade-in}
