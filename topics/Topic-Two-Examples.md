# Library Installation and Importing - Examples

##### Importing
1. Importing the entire Library and all of the included functionality
```Python
import math
print(math.sqrt(16))
```
2. Importing only a specific function (In this case the function for square rooting)  
```Python
from math import sqrt 
print(sqrt(16))
```
3. Importing the library under a different label  
```Python
import math as mt 
print(mt.sqrt(16))
```
4. Combining the label and specific function
```Python
from math import sqrt as st 
print(st(16))
```