# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`aa212c89`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`99a621a6`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`99a621a6`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`a368983e`)
  
