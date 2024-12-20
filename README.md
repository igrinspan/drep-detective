# Usage

To run a demo of this project, follow these steps:

- Clone this repository:
    ```sh
    git clone https://github.com/igrinspan/drep-detective.git
    ```

- Install modules:
    ```sh
    cd drep-detective
    npm install
    ```

- Run on localhost:
    ```sh
    npm run dev
    ```

The team created Blockfrost and CardanoScan API keys for this project and they are hardcoded in the code to facilitate usage. Also, to test some use cases, you should have a mainnet Cardano wallet in your browser.

The data referring to the suggested vote for each delegator was generated by us. The proposal transaction hashes, the drep addresses, the delegators of each drep and the votes of each drep are obtained from Cardano via APIs.

We used a TypeScript file called `data.ts` to mock the database behavior.

---

## Resources related to governance in Cardano

### Conceptual
- [CIP-1694](https://github.com/cardano-foundation/CIPs/tree/master/CIP-1694#delegated-representatives-dreps)
- [Formal Specification of the Cardano Ledger for the Conway era](https://intersectmbo.github.io/formal-ledger-specifications/pdfs/conway-ledger.pdf)
- [Voting purpose](https://plutus.cardano.intersectmbo.org/docs/working-with-scripts/script-purposes/#voting)

### Practical
- [Governance on Aiken stdlib](https://aiken-lang.github.io/stdlib/cardano/governance.html)
- [Plinth Haddock ScriptContext](https://plutus.cardano.intersectmbo.org/haddock/latest/plutus-ledger-api/PlutusLedgerApi-V3-Contexts.html#t:ScriptPurpose)
- [Governance TXs with Cardano CLI](https://developers.cardano.org/docs/get-started/cardano-cli/governance/)
- [Governance TXs with MeshJS](https://meshjs.dev/apis/txbuilder/governance)
