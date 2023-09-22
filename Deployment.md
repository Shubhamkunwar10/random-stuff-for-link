# Smart Wallet Auth

[GitHub Repository](https://github.com/C3I-blockchain/Smart-Authentication)

1. Fill environment variables from `env.example`.
2. Run `npm start`.

---

# Frontend

[GitHub Repository](https://github.com/C3I-blockchain/Client)

1. Fill environment variables from `env.example`.
2. Run `npm start`.
3. Register -> Login -> Get your wallet address.

---

# Smart Contract

[GitHub Repository](https://github.com/C3I-blockchain/evoting-contract/tree/Relayer-Nodejs)

1. Add your wallet address as the first whitelist user (or deploy from its private key).
2. Run `truffle test .\test\deployer.js` inside Smart-Contract (Provide a deployer Script).
3. Collect Gasless Relayer Address, User Manager Address, Voter Manager Address.

---

# Backend

[GitHub Repository](https://github.com/C3I-blockchain/Evoting_backend-nodejs)

1. Fill environment variables from `env.example`.
2. Run `npm start`.

---

# Relayer

[GitHub Repository](https://github.com/C3I-blockchain/Relayer-Nodejs-Server.git)

1. Fill environment variables from `env.example`.
2. Run `npm start`.

Login with your whitelisted wallet. To add users to the whitelist who can relay transactions.

---

## Frontend Flow

(These users' wallets should be added to the whitelist by any whitelist user)

1. Login as SystemAdmin (AddUniversity) Currently not implemented. Constant value of universityID=”1” [skip this step].

2. Login as Admin:
   - Add OfficerMember
   - Add User -> Add Voter
   - Add Election -> Add Position.

3. Login as Student Or Alumni:
   - Can Apply For upcoming Election
   - Can Vote on Ongoing Election.

**Note:** Users always need to be whitelisted before performing any transaction on the blockchain.
