# bit_bind
Custom API bindings for bittrex

## Installation
```
$ pip install bit_bind
```

### Install from source
```
$ git clone  https://github.com/hthompson6/bit_bind.git
$ cd bit_bind
$ python setup.py install
```

## Usage
```python
api_key = `xxxxxxxxxxxxxxxxx`
api_secret = `zzzzzzzzzzzzzz`

bit_bound = BittrexAPIBinder(api_key, api_secret)
bit_bound.get_current_balances()
bit_bound.get_current_value('BTC', 'VOX')
```