# assertshape

Python library for asserting n-dim array shapes using Einstein notations.

Examples: 

```python
from assertshape import assertshape

assertshape("nmk,mkn", [(1,2,3), (2,3,1)])
assertshape("nmk,m_n", [(1,2,3), (2,42,1)])
assertshape("nmk,mkn...", [(1,2,3), (2,3,1,4,5,6)])
```
