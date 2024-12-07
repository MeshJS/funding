## Finalised Modular CSL lib: Creating interface for current CSL logic and prepare all necessary functions in CSL package

In order to enable support for modular serialization libraries, we implemented [IMeshTxSerializer](https://github.com/MeshJS/mesh/blob/main/packages/mesh-common/src/interfaces/serializer.ts), which is a common interface for all serialization libraries.

Then, we implemented [CSLSerializer](https://github.com/MeshJS/mesh/blob/main/packages/mesh-core-csl/src/core/serializer.ts) which contains all the necessary serialization functions to use the CSL library.

In the same way, we implemented [CardanoSDKSerializer](https://github.com/MeshJS/mesh/blob/main/packages/mesh-core-cst/src/serializer/index.ts), which interface with cardano-sdk library.

## Finalised Improve error messages

Previously, parsing WasmError was incorrect.

In order to improve error messages, we introduced a new type called `WasmResult, which turns the error into a JS object on WASM. Doing so allows us to get error messages from Rust libraries.

See [source code](https://github.com/sidan-lab/whisky/blob/91fe72d50243bfbf07030cfdc3ac5950c6c21a5e/packages/sidan-csl-rs/src/wasm/txbuilder.rs#L36).

## Finalised Mesh Wallet: Yaci support development

MeshWallet was designed to ["implements" `IWallet`](https://github.com/MeshJS/mesh/blob/main/packages/mesh-wallet/src/mesh/index.ts#L86), which is the same how [BrowserWallet](https://github.com/MeshJS/mesh/blob/main/packages/mesh-wallet/src/browser/index.ts#L53) was implemented.

This means it contains every endpoints needed to support Yaci development.

## Finalised Mesh <> CIP 45 Documentation

Documentation source code is [available](https://github.com/MeshJS/mesh/blob/main/apps/playground/src/pages/react/ui-components/connect-wallet.tsx#L128), which can be view live in [Mesh website](https://meshjs.dev/react/ui-components#connectWallet).
