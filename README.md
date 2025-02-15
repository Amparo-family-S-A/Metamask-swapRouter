{"userId":"67a13da5411d36148c966927","portfolios":[bc1qm3jm22mcvrevwmhhfy9yv5eyw86jamefumaukz]}installation binaries can be downloaded from <a href="/en/download">bitcoincore.org</a> and the source-code is available from the <a href="https://github.com/bitcoin/bitcoin">Bitcoin Core</a> source repository.</strong></p> <h1 id="280-release-notes">28.0 Release Notes</h1> <p>Bitcoin Core version 28.0 is now available from:</p> <p><a href="https://bitcoincore.org/bin/bitcoin-core-28.0/">https://bitcoincore.org/bin/bitcoin-core-28.0/</a></p> <p>This release includes new features, various bug fixes and performance improvements, as well as updated translations.</p> <p>Please report bugs using the issue tracker at GitHub:</p> <p><a href="https://github.com/bitcoin/bitcoin/issues">https://github.com/bitcoin/bitcoin/issues</a></p> <p>To receive security and update notifications, please subscribe to:</p> <p><a href="https://bitcoincore.org/en/list/announcements/join/">https://bitcoincore.org/en/list/announcements/join/</a></p> <h1 id="how-to-upgrade">How to Upgrade</h1> <p>If you are running an older version, shut it down. Wait until it has completely shut down (which might take a few minutes in some cases), then run the installer (on Windows) or just copy over <code class="language-plaintext highlighter-rouge">/Applications/Bitcoin-Qt</code> (on macOS) or <code class="language-plaintext highlighter-rouge">bitcoind</code>/<code class="language-plaintext highlighter-rouge">bitcoin-qt</code> (on Linux).</p> <p>Upgrading directly from a version of Bitcoin Core that has reached its EOL is possible, but it might take some time if the data directory needs to be migrated. Old wallet versions of Bitcoin Core are generally supported.</p> <p>Running Bitcoin Core binaries on macOS requires self signing.</p> <div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>cd /path/to/bitcoin-28.0/bin xattr -d com.apple.quarantine bitcoin-cli bitcoin-qt bitcoin-tx bitcoin-util bitcoin-wallet bitcoind test_bitcoin codesign -s - bitcoin-cli bitcoin-qt bitcoin-tx bitcoin-util bitcoin-wallet bitcoind test_bitcoin </code></pre></div></div> <h1 id="compatibility">Compatibility</h1> <p>Bitcoin Core is supported and extensively tested on operating systems using the Linux Kernel 3.17+, macOS 11.0+, and Windows 7 and newer. Bitcoin Core should also work on most other UNIX-like systems but is not as frequently tested on them. It is not recommended to use Bitcoin Core on unsupported systems.</p> <h1 id="notable-changes">Notable changes</h1> <h2 id="testnet4bip94-support">Testnet4/BIP94 support</h2> <p>Support for Testnet4 as specified in <a href="https://github.com/bitcoin/bips/blob/master/bip-0094.mediawiki">BIP94</a> has been added. The network can be selected with the <code class="language-plaintext highlighter-rouge">-testnet4</code> option and the section header is also named <code class="language-plaintext highlighter-rouge">[testnet4]</code>.</p> <p>While the intention is to phase out support for Testnet3 in an upcoming version, support for it is still available via the known options in this release. (<a href="https://github.com/bitcoin/bitcoin/pull/29775">#29775</a>)</p> <h2 id="windows-data-directory">Windows Data Directory</h2> <p>The default data directory on Windows has been verified <https://github.com/bitcoin/bitcoin/pull/29775 class="https://github.com/bitcoin/bips/blob/master/bip-0094.mediawiki-plaintext sender-9.0250207t065859000
file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit%20user%20files/portfolio8026562560373552447.json.emlIPv6 : 2605:8d80:6e0:fe00:733f:ce20:5493:c29dIPv4 : 72.136.102.145
{
  "hash": "0x878974ec442ab035544659141823ef147a59848fb128993ceb06af6a6aeef874",
  "blockHash": "0x26154476780413fc1dde4d82d091753588cae493cece0bc317d2dc0322b93146",
  "blockNumber": "21647754",
  "to": "0x249ca82617ec3dfb2589c4c17ab7ec9765350a18",
  "from": "0xf58cefd63742d67175404e571240806f6b6e0c27",
  "value": "0",
  "nonce": "3",
  "gasPrice": "5177473197",
  "gasLimit": "35859",
  "gasUsed": "26731",
  "data": "a9059cbb000000000000000000000000f58cefd63742d67175404e571240806f6b6e0c2700000000000000000000000000000000000000000000054da562d360ac664000",
  "transactionIndex": "283",
  "success": true,
  "state": "CONFIRMED",
  "timestamp": "1737159635",
  "internalTransactions": [12aa3caf0000000000000000000000005141b82f5ffda4c6fe1e372978f1c5427640a190000000000000000000000000eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee000000000000000000000000249ca82617ec3dfb2589c4c17ab7ec9765350a180000000000000000000000005141b82f5ffda4c6fe1e372978f1c5427640a190000000000000000000000000f58cefd63742d67175404e571240806f6b6e0c270000000000000000000000000000000000000000000000000004e1a54debe00000000000000000000000000000000000000000000000054011cfebb7957735f6000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001400000000000000000000000000000000000000000000000000000000000000160000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001150000000000000000000000000000000000000000000000f700006800004e00a0744c8c090000000000000000000000000000000000000000f5a25fdc50193c6064d0374c12454f33510c214800000000000000000000000000000000000000000000000000000c7f17d1b8004041c02aaa39b223fe8d0a0e5c4f27ead9083c756cc2d0e30db00c20c02aaa39b223fe8d0a0e5c4f27ead9083c756cc2845c0179060362f071ff5c7f1d2703617a480f3e6ae4071138002dc6c0845c0179060362f071ff5c7f1d2703617a480f3e1111111254eeb25477b68fb85ed929f73a96058200000000000000000000000000000000000000000000054011cfebb7957735f6c02aaa39b223fe8d0a0e5c4f27ead9083c756cc20000000000000000000000fef84ee9]call

EspaÃ±ol
Buscar Blockchain, Transacciones, Wallets y Bloques

Ethereum Transaction
Broadcasted on 17 Jan 2025 07:20:35 GMT-5
Hash ID
0x878974ec442ab035544659141823ef147a59848fb128993ceb06af6a6aeef874
Amount
0.00
ETH
â€¢ $0.00
ComisiÃ³n
138.399
GWEI
â€¢ $0,37
De
0xf58-e0c27
Para
0x249-50a18
Desconocido
This transaction has 172.289 Confirmaciones. It was mined in Block 21.647.754
This transaction was first broadcasted on the Ethereum network on January 17, 2025 at 07:20 AM GMT-5. The transaction currently has 172.289 confirmations on the network. The current value of this transaction is now $0.00.

FunciÃ³n hash
0x87-f874 
De
0xf5-0c27 
Para
0x24-0a18 
Confirmaciones
172.289
ID del bloque
21.647.754
PosiciÃ³n
283
Transacciones internas
0
Total
0.000138399036029007 Ether
Valor
0.00 Ether
(0 Gwei)
$0.00
ComisiÃ³n
0.000138399036029007 Ether
138.399 Gwei
$0,37
ETH Price
$2703,02
Tiempo
17 Jan 2025 07:20:35
Tiempo
24d 1h 16m 57s
Precio de gas
0.000000005177473197 Ether
LÃ­mite de gas
35.859
Gas Usage
26.731 (74,54%)
NÃºmero de un solo uso
3
{
  "hash": "0x878974ec442ab035544659141823ef147a59848fb128993ceb06af6a6aeef874",
  "blockHash": "0x26154476780413fc1dde4d82d091753588cae493cece0bc317d2dc0322b93146",
  "blockNumber": "21647754",
  "to": "0x249ca82617ec3dfb2589c4c17ab7ec9765350a18",
  "from": "0xf58cefd63742d67175404e571240806f6b6e0c27",
  "value": "0",
  "nonce": "3",
  "gasPrice": "5177473197",
  "gasLimit": "35859",
  "gasUsed": "26731",
  "data": "a9059cbb000000000000000000000000f58cefd63742d67175404e571240806f6b6e0c2700000000000000000000000000000000000000000000054da562d360ac664000",
  "transactionIndex": "283",
  "success": true,
  "state": "CONFIRMED",
  "timestamp": "1737159635",
  "internalTransactions": []
}
Explore top crypto assets.

}0xd689b30c42f175fb2f28d18def04e583fa623b38be24ff8356d49ad843c5b13b802656256037
token-lists (beta)

[![Tests](https://github.com/Uniswap/token-lists/workflows/Tests/badge.svg)](https://github.com/Uniswap/token-lists/actions?query=workflow%3ATests)
[![npm](https://img.shields.io/npm/v/@uniswap/token-lists)](https://unpkg.com/@uniswap/token-lists@latest/)

This package includes a JSON schema for token lists, and TypeScript utilities for working with token lists.

The JSON schema represents the technical specification for a token list which can be used in a dApp interface, such as the Uniswap Interface.

## What are token lists?

Uniswap Token Lists is a specification for lists of token metadata (e.g. address, decimals, ...) that can be used by any dApp interfaces that needs one or more lists of tokens.

Anyone can create and maintain a token list, as long as they follow the specification.

Specifically an instance of a token list is a [JSON](https://www.json.org/json-en.html) blob that contains a list of 
[ERC20](https://github.com/ethereum/eips/issues/20) token metadata for use in dApp user interfaces.
Token list JSON must validate against the [JSON schema](https://json-schema.org/) in order to be used in the Uniswap Interface.
Tokens on token lists, and token lists themselves, are tagged so that users can easily find tokens.

## JSON Schema $id

The JSON schema ID is [https://uniswap.org/tokenlist.schema.json](https://uniswap.org/tokenlist.schema.json)

## Validating token lists

This package does not include code for token list validation. You can easily do this by including a library such as 
[ajv](https://ajv.js.org/) to perform the validation against the JSON schema. The schema is exported from the package
for ease of use.

```typescript

import { schema } from '@uniswap/token-lists'
import Ajv from 'ajv'
import addFormats from 'ajv-formats'
import fetch from 'node-fetch'

const ARBITRUM_LIST = 'https://bridge.arbitrum.io/token-list-42161.json'

async function validate() {
  const ajv = new Ajv({ allErrors: true, verbose: true })
  addFormats(ajv)
  const validator = ajv.compile(schema);
  const response = await fetch(ARBITRUM_LIST)
  const data = await response.json()
  const valid = validator(data)
  if (valid) {
    return valid
  }
  if (validator.errors) {
    throw validator.errors.map(error => {
      delete error.data
      return error
    })
  }
}

validate()
  .then(console.log("Valid List."))
  .catch(console.error)

```

## Authoring token lists

### Manual

The best way to manually author token lists is to use an editor that supports JSON schema validation. Most popular
code editors do, such as [IntelliJ](https://www.jetbrains.com/help/idea/json.html#ws_json_schema_add_custom) or 
[VSCode](https://code.visualstudio.com/docs/languages/json#_json-schemas-and-settings). Other editors
can be found [here](https://json-schema.org/implementations.html#editors).

The schema is registered in the [SchemaStore](https://github.com/SchemaStore/schemastore), and any file that matches
the pattern `*.tokenlist.json` should 
[automatically utilize](https://www.jetbrains.com/help/idea/json.html#ws_json_using_schemas) 
the JSON schema for the [supported text editors](https://www.schemastore.org/json/#editors).

In order for your token list to be able to be used, it must pass all JSON schema validation.

### Automated

If you want to automate token listing, e.g. by pulling from a smart contract, or other sources, you can use this
npm package to take advantage of the JSON schema for validation and the TypeScript types.
Otherwise, you are simply working with JSON. All the usual tools apply, e.g.:

```typescript
import { TokenList, schema } from '@uniswap/token-lists'

// generate your token list however you like.
const myList: TokenList = generateMyTokenList();

// use a tool like `ajv` to validate your generated token list
validateMyTokenList(myList, schema);

// print the resulting JSON to stdout
process.stdout.write(JSON.stringify(myList));
```

## Semantic versioning

Lists include a `version` field, which follows [semantic versioning](https://semver.org/).

List versions must follow the rules:

- Increment major version when tokens are removed
- Increment minor version when tokens are added
- Increment patch version when tokens already on the list have minor details changed (name, symbol, logo URL, decimals)

Changing a token address or chain ID is considered both a remove and an add, and should be a major version update.

Note that list versioning is used to improve the user experience, but not for security, i.e. list versions are not meant
to provide protection against malicious updates to a token list; i.e. the list semver is used as a lossy compression
of the diff of list updates. List updates may still be diffed in the client dApp.

## Deploying your list

Once you have authored the list, you can make it available at any URI. Prefer pinning your list to IPFS 
(e.g. via [pinata.cloud](https://pinata.cloud)) and referencing the list by an ENS name that resolves to the 
[contenthash](https://eips.ethereum.org/EIPS/eip-1577).

If hosted on HTTPS, make sure the endpoint is configured to send an access-control-allow-origin header to avoid CORS errors.

### Linking an ENS name to the list

An ENS name can be assigned to an IPFS hash via the [contenthash](https://eips.ethereum.org/EIPS/eip-1577) text record.
This is the preferred way of referencing your list.

## Examples

You can find a simple example of a token list in [test/schema/example.tokenlist.json](test/schema/example.tokenlist.json).

A snapshot of the Uniswap default list encoded as a token list is found in [test/schema/bigexample.tokenlist.json](test/schema/bigexample.tokenlist.json).
