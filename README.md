# **CLI Essentials**
#### Essential pieces of code aimed at making your Python projects a little bit better.

[![MIT Licence](https://img.shields.io/github/license/DanGill/cli-essentials)](https://github.com/DanGill/scprint/blob/master/LICENSE) [![PyPi Version](https://img.shields.io/pypi/v/cli-essentials)](https://pypi.org/project/cli-essentials/) [![Python Version](https://img.shields.io/pypi/pyversions/cli-essentials)](https://www.python.org/) [![Downloads](https://img.shields.io/pypi/dm/cli-essentials)](https://pypi.org/project/cli-essentials/)




### **Installation**
```
$ python -m pip install cli-essentials
```

### **Usage**

```python
from CLI import <feature> # This will import only one feature of your choosing
# --or--
from CLI import <feature1>, <feature2>, ... # This will import as many features as you would like
# --or--
from CLI import * # This will import all CLI features
```

### **Feature List**
 - **Clear**

   ```python
   from CLI import clear

   print("Hello World!") # "Hello World!" is printed to the console
   clear() # The console is clear again
   ```

- **Print**

   ```python
   from CLI import print # This will not effect existing print functions in your program

   print("Apple", color="red") # "Apple" is printed to the console with a Red foreground color
   print("Sky", color="blue", bcolor="white") # "Sky" is printed in Blue with a White background
   ```
