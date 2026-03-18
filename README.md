# Welcome!

This mini repo should contain two `.csv` files you should be able to download and mess around with.

- `finhub_export.csv`: invoices
- `ordtrack_export.csv`: orders

## Download via CLI

```bash
curl -O https://raw.githubusercontent.com/jloxh/muds-deng-workshop-feb26/main/finhub_export.csv
curl -O https://raw.githubusercontent.com/jloxh/muds-deng-workshop-feb26/main/ordtrack_export.csv
```

## Read directly via URL

```python
import pandas as pd

finhub = pd.read_csv("https://raw.githubusercontent.com/jloxh/muds-deng-workshop-feb26/main/finhub_export.csv")
ordtrack = pd.read_csv("https://raw.githubusercontent.com/jloxh/muds-deng-workshop-feb26/main/ordtrack_export.csv")
```

# Questions for you to try to answer

- How many orders were placed in 2024?
- What was the lab's total spend in 2024?
- Which orders don’t appear in invoices? What is going on there?

Feel free to generally just explore the data as well!
