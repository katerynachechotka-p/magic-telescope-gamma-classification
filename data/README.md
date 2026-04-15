# Data

No data file is included in this repository.

Data is fetched automatically via the `ucimlrepo` package:

```python
from ucimlrepo import fetch_ucirepo
magic_gamma_telescope = fetch_ucirepo(id=159)
```

Original source: https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope