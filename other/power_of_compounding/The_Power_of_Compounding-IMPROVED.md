# The Power of Compounding

**Key Takeaways**
- Compound interest grows your wealth exponentially over time.  
- Adding regular contributions dramatically accelerates growth.  
- Rule of 72: Years to double ≈ 72 ÷ Annual Return.  
- Small rate differences compound into large value gaps.  
- Hands-on modeling helps personalize your plan.

## Understanding Compounding

### Simple vs. Compound Interest
- **Simple Interest**: Interest on principal only.  
- **Compound Interest**: Interest on principal *plus* accumulated interest.

**Formula**:  
```
A = P (1 + r/n)^(n*t)
```
- *A*: future value  
- *P*: principal  
- *r*: annual rate  
- *n*: compounding periods per year  
- *t*: years  

### Rule of 72
**Rule of 72**:  
```
Years to double ≈ 72 ÷ r%
```

## Growth Examples

| Scenario                         | Value after 10 Years |
|----------------------------------|----------------------:|
| £1,000 @ 8% annually             |           £2,159. |
| £1,000 + £100/mo @ 8% annually   |          £18,417. |

```python
# Try It Yourself: Python snippet
P = 1000
r = 0.08
n = 12
t = 10
A = P * (1 + r/n)**(n*t) + 100 * (((1 + r/n)**(n*t) - 1) / (r/n))
print(f"Future Value: £{A:,.2f}")
```

## Real-World Application

- **Invest early**: Every year counts.  
- **Automate contributions**: Leverage discipline.  
- **Monitor & adjust**: Reinvest dividends and review rates.

## Next Steps
1. Model your own numbers using the Python snippet above.  
2. Explore online compound calculators (e.g., [Investopedia](https://www.investopedia.com)).  
3. Set up regular contributions with your broker or platform.

