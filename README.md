curl -i -X POST \
  --data '{"id": 1, "jsonrpc": "2.0", "method": "eth_blockNumber"}' \
  -H "Content-Type: application/json" \
  "https://rpc.minato.soneium.org/"
