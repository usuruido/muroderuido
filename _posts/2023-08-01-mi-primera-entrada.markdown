---
layout: post
title:  "Mi primera entrada"
date:   2023-08-01 10:06:57 +0200
# categories: jekyll update
#katex: True
tags: [Matemáticas, Tipeado]
---
{% include math/katex-head.html %}

Hola, esta es la primera entrada de mi blog personal. En ella simpleamente dejaré información sobre el uso de _Jekyll_, _GitHub-Pages_ y _KaTeX_ que me servirá de "chuleta" de uso personal, además de, quizás, ser útil para otras personas que lleguen hasta aquí.

## Sobre _Jekyll_

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

## Sobre _GitHub-Pages_
## Sobre _KaTeX_

<p>
  Aquí podemos obervar la inclusión en una línea de etxto de una fórmula matemática <b>TeX</b> construida gracias a <b>KaTeX</b>: \(P = V \cdot I \cdot \cos\phi\). 
</p>

<p>
  Aquí vemos una fórmula en una línea aparte.

  \[V \left( \bigwedge_{i=1}^n p_i \right) = \dfrac{1}{n} \sum_{i=1}^n V(p_i)\]
</p>

<p>
  Aquí podemos obervar la inclusión en una línea de etxto de una fórmula matemática <b>TeX</b> construida gracias a <b>KaTeX</b>: $$P = V \cdot I \cdot \cos\phi$$. 
</p>

En una misma línea $$V=I\cdot R$$

En distinta línea:

$$V=I\cdot R$$

O:

$$f(n) = \begin{cases}
  \frac{n}{2}, & \text{if } n \text{ is even} \\
  3n+1,        & \text{if } n \text{ is odd}
\end{cases}
$$

The code for the example above is:

```
$$f(n) = \begin{cases}
  \frac{n}{2}, & \text{if } n \text{ is even} \\
  3n+1,        & \text{if } n \text{ is odd}
\end{cases}
$$
```

Both inline and display modes are [supported](https://kramdown.gettalong.org/syntax.html#math-blocks). Powered by [KaTeX](https://github.com/Khan/KaTeX).

<!--
## Canvas

 <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
</canvas> 

<canvas id="myCanvas" width="300" height="150">
Fallback content, in case the browser does not support Canvas.
</canvas>
-->