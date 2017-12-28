# saucenaopy
---
SauceNAO API wrapper for Python

## Setup
1. run ```pip install -r requirements.txt``` to install dependencies
2. from saucenaopy import SauceNAO

## Example
### Default
```python
sn = SauceNAO(api_key)
sn.get_sauce(img_url)
```
### Custom Arguments
```python
sn = SauceNAO(api_key, dbmask=8191, numres=12)
sn.get_sauce(img_url)
```

