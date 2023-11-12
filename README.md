Based by ISBN 978-3-319-13071-2

| Operation | Complexity | Usage | Method |
|-----------|------------|-------|--------|
| list creation| O(n) or O(1) | x = list(y) | calls `__init__(y)` |
| indexed get| O(1) | a = x[i] | `x.__getitem__(i)` |
| indexed set| O(1) | x[i] = a | `x.__setitem__(i,a)` |
| concatenate| O(n) | z = x + y | `x.__add__(y)`|
| append| O(1) | x.append(a) | `x.append(a)` |
| insert| O(n) | x.insert(i,e) | `x.insert(i,e)` |
| delete| O(n) | del x[i] | `x.__delitem__(i)` |
| equality| O(n) | x == y | `x.__eq__(y)` |
| iterate| O(n) | for a in x: | `x.__iter__()` |
| length| O(1) | len(x) | `x.__len__()` |
| membership| O(n) | a in x | `x.__contains__(a)` |
| sort| O(n log n) | x.sort() | `x.sort()` |

