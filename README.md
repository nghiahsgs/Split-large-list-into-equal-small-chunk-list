# Split-large-list-into-equal-small-chunk-list
Split large list into equal small chunk list

```
from peewee import chunked
L = list(range(100))
for batch in chunked(L,11):
    print(batch)
```
