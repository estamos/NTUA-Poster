---
panflute-filters: [div-table]
panflute-path: 'panflute/docs/source'
---

::::: {.divtable}
:::: {.tcaption}
a caption here (optional), only the first paragraph is used.
::::
:::: {.thead}
[Header 1]{width=0.4 align=center}
[Header 2]{width=0.6 align=default}
::::
:::: {.trow}
::: {.tcell}

1. any
2. normal markdown
3. can go in a cell

:::
::: {.tcell}
![](https://pixabay.com/get/e832b60e2cf7043ed1584d05fb0938c9bd22ffd41cb2144894f9c57aae/bird-1771435_1280.png?attachment){width=50%}

some text
:::
::::
:::: {.trow bypara=true}
If bypara=true

Then each paragraph will be treated as a separate column
::::
any text outside a div will be ignored
:::::
