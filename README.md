# isat252
import pandas as pd
data = pd.read_excel('Eligible Bachelor's.xlsx')
summary_stats = data.describe()
print(summary_stats)
