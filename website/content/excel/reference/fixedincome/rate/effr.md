---
title: effr
description: Fed Funds Rate
keywords: 
- fixedincome
- rate
- effr
---

<!-- markdownlint-disable MD041 -->

Fed Funds Rate.  Get Effective Federal Funds Rate data. A bank rate is the interest rate a nation's central bank charges to its domestic banks to borrow money. The rates central banks charge are set to stabilize the economy. In the United States, the Federal Reserve System's Board of Governors set the bank rate, also known as the discount rate.

## Syntax

```jsx<span style={color: 'red'}>=OBB.FIXEDINCOME.RATE.EFFR([provider];[start_date];[end_date];[parameter])</span>```

### Example

```excel wordwrap
=OBB.FIXEDINCOME.RATE.EFFR()
```

---

## Parameters

| Name | Type | Description | Optional |
| ---- | ---- | ----------- | -------- |
| provider | Text | Options: federal_reserve, fred, defaults to federal_reserve. | True |
| start_date | Text | Start date of the data, in YYYY-MM-DD format. | True |
| end_date | Text | End date of the data, in YYYY-MM-DD format. | True |
| parameter | Text | Period of FED rate. (provider: fred) | True |

---

## Return Data

| Name | Description |
| ---- | ----------- |
| date | The date of the data.  |
| rate | FED rate.  |