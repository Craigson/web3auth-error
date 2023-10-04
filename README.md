# web3auth-error

## Installation

```bash
npm install
```

## Error

```
file:///location/web3auth-error/index.js:2
import { EthereumPrivateKeyProvider } from "@web3auth/ethereum-provider";
         ^^^^^^^^^^^^^^^^^^^^^^^^^^
SyntaxError: Named export 'EthereumPrivateKeyProvider' not found. The requested module '@web3auth/ethereum-provider' is a CommonJS module, which may not support all module.exports as named exports.
CommonJS modules can always be imported via the default export, for example using:

import pkg from '@web3auth/ethereum-provider';
const { EthereumPrivateKeyProvider } = pkg;

    at ModuleJob._instantiate (node:internal/modules/esm/module_job:124:21)
    at async ModuleJob.run (node:internal/modules/esm/module_job:190:5)

Node.js v18.17.0
```
