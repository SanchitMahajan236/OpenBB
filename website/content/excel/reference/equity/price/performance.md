---
title: performance
description: Learn how to calculate the price performance return for a symbol over
  different time periods using the OBB.equity.price.performance function. Retrieve
  data such as one-day return, week to date return, one-week return, month to date
  return, and more. Understand the parameters, returns, and data structure of the
  function.
keywords: 
- price performance
- return
- symbol
- data
- provider
- chart
- metadata
- one-day return
- week to date return
- one-week return
- month to date return
- one-month return
- quarter to date return
- three-month return
- six-month return
- year to date return
- one-year return
- three-year return
- five-year return
- ten-year return
- max return
- time series
- ticker symbol
---

<!-- markdownlint-disable MD041 -->

Price performance as a return, over different periods.

## Syntax

```excel wordwrap
=OBB.EQUITY.PRICE.PERFORMANCE(symbol;[provider])
```

### Example

```excel wordwrap
=OBB.EQUITY.PRICE.PERFORMANCE("AAPL")
```

---

## Parameters

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| **symbol** | **Text** | **Symbol to get data for.** | **True** |
| provider | Text | Options: fmp, defaults to fmp. | False |

---

## Return Data

| Name | Description |
| ---- | ----------- |
| one_day | One-day return.  |
| wtd | Week to date return.  |
| one_week | One-week return.  |
| mtd | Month to date return.  |
| one_month | One-month return.  |
| qtd | Quarter to date return.  |
| three_month | Three-month return.  |
| six_month | Six-month return.  |
| ytd | Year to date return.  |
| one_year | One-year return.  |
| three_year | Three-year return.  |
| five_year | Five-year return.  |
| ten_year | Ten-year return.  |
| max | Return from the beginning of the time series.  |
| symbol | The ticker symbol. (provider: fmp) |