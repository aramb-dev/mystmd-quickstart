# Arithmetic Sequence

## Scenario

I want to buy a MacBook Pro that costs \$2,063. I'm starting with \$100 in savings and adding \$10 every week.

## Data

Start Amount ($a$): $\$100$ 

Weekly Savings ($d$): $\$10$ 

Week 1: $\$100$  |  Week 2: $\$110$

Week 3: $\$120$  |  Week 4: $\$130$

Week 5: $\$140$  |  Week 6: $\$150$

Week 7: $\$160$  |  Week 8: $\$170$

Week 9: $\$180$  |  Week 10: $\$190$

## Table

| Week ($n$) | Calculation $a+(n-1)d$ | Total Balance ($a_n$) |
|------------|------------------------|----------------------|
| $1$        | $100+0(10)$            | $\$100$              |
| $2$        | $100+1(10)$            | $\$110$              |
| $3$        | $100+2(10)$            | $\$120$              |
| $4$        | $100+3(10)$            | $\$130$              |
| $5$        | $100+4(10)$            | $\$140$              |
| $6$        | $100+5(10)$            | $\$150$              |
| $7$        | $100+6(10)$            | $\$160$              |
| $8$        | $100+7(10)$            | $\$170$              |
| $9$        | $100+8(10)$            | $\$180$              |
| $10$       | $100+9(10)$            | $\$190$              |

## Calculations

**First Term:** $a = 100$

**Common Difference:** $d = 10$

**Nth-Term Formula:**
$$a_n = a + (n-1)d$$
$$a_n = 10n + 90$$

**Sum Formula:**
$$S_n = \frac{n}{2}[2a + (n-1)d]$$
$$S_n = 5n^2 + 95n$$

**Amount in Week 10:**
$$a_{10} = 100 + (10-1)10 = 190$$

So I'd have \$190 by week 10.

**Predicting When I Reach \$2,063:**
$$2063 = 100 + (n-1)10$$
$$n = 197.3$$

I'll need about 198 weeks to afford the MacBook.

## Graph

![Graph](../images/ap_graph.png)

## Explanation

This is an Arithmetic Sequence because I'm adding the same amount (\$10) every week instead of multiplying by a percentage.

- $a = 100$ → my starting savings
- $d = 10$ → what I add each week
- $a_n$ → my balance at any week $n$