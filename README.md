# solana-rpc
python notebook for calling solana rpc and parsing data

## Setup

```bash
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```
## Download a block to file using bash

'''bash
curl https://api.mainnet-beta.solana.com -X POST -H "Content-Type: application/json" -d '
  {"jsonrpc": "2.0","id":1,"method":"getBlock","params":[100356971, {"encoding": "json","transactionDetails":"full","rewards":false}]}
' -o block.json
'''

## Do some analysis with python

'''
jupyter notebook
'''
