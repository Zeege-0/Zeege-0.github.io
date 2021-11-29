---
title: helloworld
date: 2021-11-29 21:01:36
tags:
---

# Hello World

This is a test page to see if all elements are rendering correctly.

$$
 \LaTeX\begin{cases} \frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} &= 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\cdots} } } }\\
 \lim\limits_{n\rightarrow\infin}(1+\dfrac{1}{n})^{n}&=e\\
 abcdEFGH &= \mathcal{ABCD}\mathscr{EFGH}
 \end{cases}
$$

Lorem ipsum `dolor` sit amet[^first], [test link](/archive) consectetur adipiscing elit. **Strong text** pellentesque ligula ==commodo viverra vehicula==. *Italic text* at ullamcorper enim un inline footnote^[Text of inline footnote]. Morbi a euismod nibh. <u>Underline text</u> non elit nisl. ~~Deleted text~~ tristique, sem id condimentum tempus, inline $f(x)=\int \dfrac{1}{1+e^{-x}}\text{d}x$ render. Sed ultricies ac arcu quis molestie[^first][^second]. Lorem <sup>superscript</sup> dolor <sub>subscript</sub> amet, consectetuer adipiscing elit. Nullam dignissim convallis est. Quisque aliquam. <cite>cite</cite>. <acronym title="National Basketball Association">NBA</acronym> Mauris a ante. Morbi imperdiet augue quis tellus.  <abbr title="Avenue">AVE</abbr>

> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
> > Praesent diam elit, interdum ut pulvinar placerat, imperdiet at magna.

{% pullquote right %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
{% endpullquote %}

::: note
*note*
:::

::: tip
*tip*
:::

::: attention
*attention*
:::

::: warning
*warning*
:::

```c++
#include <iostream>
class HelloWorld{
public:
    std::string text;
    HelloWorld(const std::string &t): text(t){}
    void greet(const std::string &t){
        std::cout << this->text;
    }
}
int main(){
    HelloWorld world("Hello World!");
    world.greet();
    return 0;
}
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# List Types

**Ordered List**

1. List Item 1
   1. List Item 1.1
   2. List Item 1.2
      1. List Item 1.2.1
2. List Item 2
3. List Item 3

**Unordered List (ul)**

- List Item 1
   - List Item 1.1
   - List Item 1.2
      - List Item 1.2.1
- List Item 2
- List Item 3

**Checkbox List (ul)**

- [ ] List Item 1 unchecked
- [x] List Item 2 checked
- [X] List Item 3 checked

## Table

| Table Header 1 | Table Header 2 | Table Header 3 |
| :- | :-: | -: |
| Division 1 | Division 2 | Division 3 |
| Division 1 | Division 2 | Division 3 |
| Division 1 | Division 2 | Division 3 |


[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.
