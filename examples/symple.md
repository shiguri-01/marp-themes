---
marp: true
theme: symple
math: mathjax
---

<!--
paginate: true
_class: title
header: '\<header\> theme: symple'
footer: '\<hooter\> theme: symple'
-->

# \<h1\>テーマの見本: symple

サブタイトル

> Marp同好会
> 山田 太郎

---

## \<h2\>見出し2

### \<h3\>見出し3

#### \<h4\>見出し4

##### \<h5\>見出し5

段落です。**強調**はこんな感じです。[リンク](#)はこんな感じです。

改段落しています。
改行しています。

---

- リストの要素
- リストの要素
  - リストの要素

1. リストの要素
2. リストの要素

> 引用はこんな感じです。
> `<cite>`タグを使って引用元を表示できます。
> <cite>引用元</cite>

---

コードを表示できます。

`ls`コマンド

```python
# Python
def hello():
    print('Hello, world!')
```

$\LaTeX$の表記で数式を表示できます。

$$
  f(x) = \frac{d}{dx} \int_a^x f(t) dt
$$

---

<div class="columns">
<div>

HTMLを使って段組みを実現できます。

</div>
<div>

```md
<div class="columns">
<div>

左側

</div>
<div>

右側

</div>
</div>
```

</div>
</div>
