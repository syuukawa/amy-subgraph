

### graph

0. npm install -g @graphprotocol/graph-cli

0. yarn global add @graphprotocol/graph-cli 

1. graph init --product hosted-service syuukawa/amygraph

2. npm install

3. npm run codegen

1. graph auth --product hosted-service  https://api.thegraph.com/deploy/ access_token

2. graph deploy --node https://api.thegraph.com/deploy/ --ipfs https://api.thegraph.com/ipfs/ syuukawa/amy-subgraph
