# saucenaopy
SauceNAO API wrapper for Python

[![PyPI](https://img.shields.io/pypi/v/nine.svg)]()

## Example
### Default
```python
from saucenaopy import SauceNAO

sn = SauceNAO(api_key)
sn.get_sauce(img_url)
```
### Custom Arguments
```python
from saucenaopy import SauceNAO

sn = SauceNAO(api_key, dbmask=8191, numres=12)
sn.get_sauce(img_url)
```

