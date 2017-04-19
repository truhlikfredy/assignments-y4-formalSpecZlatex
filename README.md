![titlepage](/images/hammer.png)

Description
-----------

This is formal specification assignment written in Z and Latex (just warning this is my first assignment of using both, so the quality might not be as good).

Part I liked a lot is maybe not impressive but I made me interested in latex, even more, I had to repeat often what did not change a state and there very often many of them which did not change. So I written two simple commands to automate this tasks, it saved a lot of tedious work:

```
\newcommand{\same}[1]{\\{#1}'={#1}}

\newcommand{\sameObvious}[1]{\same{rooms}\same{allThings}\same{noiseThings}\same{tempThings}\same{lightThings}\same{actuatorThings}}
```

As I said not impressive, but it saved a good bit of typing. 