# TokeniZK Finance

<div align="center">
<img align='center' src="./docs/img/tokenizk-brand3.png" height="60%" width="60%">
</div>

NOTE: under development currently, cannot used at production.

## Description

Please go to [doc](./docs/README.md) for more details.

## Quick start

```bash

git clone https://github.com/tokenizk/tokenizk-network.git

cd tokenizk-network

npm install

npm run`coreService:dev`

npm run`apiGateway:dev`

npm run`proofGen:dev`

npm run`chainTracker:dev`

npm run`webUI:dev`

```

## Top-Level Scripts

- `webUI:dev`: run front-end api-gateway with hot reload
- `coreService:dev`: run back-end-coreService api-gateway with hot reload
- `apiGateway:dev`: run back-end-apiGateway api-gateway with hot reload
- `proofGen:dev`: run back-end-proofGen api-gateway with hot reload
- `chainTracker:dev`: run back-end-chainTracker api-gateway with hot reload
- `libs:build` - build packages in `libs` folder
- `build` - build all packages
- `clean` - clean all packages
- `lint` - lint all packages

## License

MIT