# data-science-projects

<p align="center">
    <img src="https://i.ibb.co/tCKc47b/memee.jpg">

## :)

```python
import pingouin as pg
import pandas as pd

# Data Science Wizardry with pingouin

# Generate some fake data for analysis
data = pd.DataFrame({
    'Group': ['A'] * 50 + ['B'] * 50,
    'Scores': list(range(50)) + list(range(50, 100))
})

# Perform an independent t-test
ttest_result = pg.ttest(x=data[data['Group'] == 'A']['Scores'],
                        y=data[data['Group'] == 'B']['Scores'])

# Display the result
print("Data Science Wizardry with pingouin:")
print(ttest_result)

```
