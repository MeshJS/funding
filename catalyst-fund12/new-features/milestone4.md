## Finalised Modular CSL lib: Refactor to dependency injection pattern and integrate with new pattern

Both [CSLSerializer](https://github.com/MeshJS/mesh/blob/main/packages/mesh-core-csl/src/core/serializer.ts) and [CardanoSDKSerializer](https://github.com/MeshJS/mesh/blob/main/packages/mesh-core-cst/src/serializer/index.ts) has been implemented with dependency injection pattern. CSLSerializer is feature complete and CardanoSDKSerializer is currently undergoing beta testing.

## Finalised Mesh Wallet: Yaci support development

Yaci Provider is completed and its documentation can be found on [MeshJS website](https://meshjs.dev/providers/yaci) which includes all the methods, their descriptions and live demos.

## Finalised Mesh Wallet: Documentation

Full documentation can be found on [MeshJS website](https://meshjs.dev/apis/wallets/meshwallet) which includes all the methods, their descriptions and live demos.

## Finalised Modular CSL lib: Documentation

Documentation can be found on [MeshJS website](https://meshjs.dev/apis/txbuilder/basics#initializeTxbuilder) where users can specify either [CSLSerializer](https://github.com/MeshJS/mesh/blob/main/packages/mesh-core-csl/src/core/serializer.ts) or [CardanoSDKSerializer](https://github.com/MeshJS/mesh/blob/main/packages/mesh-core-cst/src/serializer/index.ts) or their own custom serializer.
