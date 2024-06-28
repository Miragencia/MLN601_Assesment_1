# MLN601_Assesment_1
Repository for the 1st Assessment.

# Load the data
The following code can be used to import a wine quality red CSV file containing 1600 samples:

```python
import pandas as pd

data = pd.read_csv('https://raw.githubusercontent.com/Miragencia/MLN601_Assesment_1/main/wine%2Bquality/winequality-red.csv',
                   sep=';', encoding='utf8')
```

Data source: [https://www.cs.jhu.edu/~mdredze/datasets/sentiment/index2.html](https://archive.ics.uci.edu/dataset/186/wine+quality)
