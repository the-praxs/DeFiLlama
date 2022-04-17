# DeFiLlama

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

-------

### Unofficial [DeFi Llama API](https://defillama.com/home) client in Python

For detailed information about the API endpoints, see [DeFi Llama API Documentation](https://docs.llama.fi/api)

### Installation:

use pip to install:

``` 
pip install DeFiLlama
```

-----------

### Authentication:

Endpoints are accessible without an API key.

-----------

### Documentation:

To import the package and initialize API client
```
from defillama import defillama
llama = DefiLlama()
```

# TVL : Retrieve TVL data -->

GET/protocols : List all protocols on defillama along with their TVL
llama.get

# Get a protocol data
response = llama.get_protocol(name='uniswap')

# Get historical values of total TVL
response = llama.get_historical_tvl()

# Get protocol TVL
response = llama.get_protocol_tvl(name='uniswap')
```