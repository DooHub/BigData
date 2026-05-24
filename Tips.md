# Tips
## 1. Use dir()

### 1) Find 'Method' name
To find 'get_dummies'

```python
import pandas as pd

Look_function ='get_'

Found_list=[ i for i in dir(pd) if Look_function in i]
print(Found_list)

['get_dummies', 'get_option']
```






