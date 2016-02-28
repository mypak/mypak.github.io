---
title       : Investment value of owning non-landed property
subtitle    : Computation Made Simple
author      : Pak Mei Yuet
job         : Hobbyist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---


## Challenges


Would you like to make an informed decision on whether your investment on a non-landed property will yield you the return you desired? Would you like to know which location yields the better return?

---

## Solution


This tool will allow you to do a quick computation on the return of your investment such as rental yield and yearly cash flow in mere seconds. All it does is compute the rental yield minus holding costs. 

---

## How the tool computes rental yield?

To compute rental yield, key-in Property Purchase Price and monthly rental.
Formula to compute rental yield in percentage is
(monthly rental * 12) divide by property purchase price multiple by 100. 

For example, Property Purchase Price is RM600,000 and monthly rental is RM1,000. The rental yield in percentage is 2%


```r
1000 * 12 / 600000 * 100
```

```
## [1] 2
```

---

## How the tool computes cash flow per year?

To compute yearly cash flow, key-in monthly loan repayment, monthly rental and estimated costs to hold the property such as quit rent, water bill and management fee.

Formula = (monthly rental * 12) - ((quit rent + water + management fees) * 4) - monthly loan repayment. 

For example, Monthly rental is RM1,000. Monthly loan repayment is RM2,000. Quit Rent per quarter is RM100. Water bill per quarter is RM30. Management fee per quarter is RM450.

Yearly cash flow is RM7680

```r
1000 * 12 - (100 + 30 + 450) * 4 - 2000
```

```
## [1] 7680
```

---

## Thanks and Concluding Remark

>1. Thank you for using this tool.
>2. I hope you find this tool helpful. 
>3. This tool is my first developed tool.
>4. I welcome any suggestions on improving this tool. 


