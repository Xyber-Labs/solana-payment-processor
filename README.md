# solana-payment-processor

`solana-payment-processor` is a Solana smart contract that facilitates token-based payments for agent-based services. It allows administrators to register operations with predefined costs and enables users to pay using a specified SPL token. This contract can be used to process prompt payments and associate them with unique identifiers for tracking and attribution.

## 🔧 Commands

### Switch between networks

```sh
# Localnet
solana config set --url http://127.0.0.1:8899

# Devnet
solana config set --url https://api.devnet.solana.com
```

### Generate and use a custom keypair for deployment

```sh
solana-keygen new --outfile deploy-keypair.json
solana-keygen pubkey deploy-keypair.json
```

---

## 📬 Feedback

We welcome issues, contributions, and feature suggestions — let's build the future of web3 together!
