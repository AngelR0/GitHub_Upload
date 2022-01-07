# Loan Analyzer

This is a loan analyzer for different loans, using the present value formula.

---
## Present Value Function

```python
  def calculate_present_value(future_value, remaining_months, annual_discount_rate):
      present_value = future_value / (1 + annual_discount_rate / 12) ** remaining_months
      return present_value
```
