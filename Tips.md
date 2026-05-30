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



## 2. Output Screen
``` python
#화면 출력 확대
pd.set_option('display.width',None)
pd.set_option('display.columns',None)
pd.set_option('display.rows',None)

#줄바꿈 방지 to_string()
print(train.describe().to_string())
```


