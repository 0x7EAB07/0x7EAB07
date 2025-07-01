# <img src="https://em-content.zobj.net/thumbs/120/apple/354/teapot_1fad6.png" width="40" height="40"/> Teapot in Wonderland

<div align="center">

**[@0x7EAB07](https://github.com/0x7EAB07)** — Breaking the web (in a good way) | Blockchain, AI, Web Architect

[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/0x7EAB07)
[![Profile views](https://komarev.com/ghpvc/?username=0x7EAB07&color=blueviolet&style=for-the-badge)](https://twitter.com/0x7EAB07)

</div>

---

## 🧩 Blockchain Odyssey

I craft decentralized dreams across multiple ecosystems:

- **Solana** ecosystem with Anchor framework, Pinocchio and native Rust development
- **SUI** network leveraging the MOVE language for secure assets
- **Ethereum** smart contracts with Solidity and EVM optimization
- **Frontend Mastery** with React and React Native for seamless cross-platform experiences

Each blockchain is a different rabbit hole, yet they all lead to innovation.

```rust
#[program]
pub mod wonderland {
    use super::*;

    pub fn enter_realm(ctx: Context<Enter>, message: String) -> Result<()> {
        msg!("Welcome to Wonderland: {}", message);
        Ok(())
    }
}
```

```rust
module welcome::welcome;

public struct WelcomeObject has key, store {
    id: UID,
    message: String,
}

public entry fun create_welcome(ctx: &mut TxContext) {
    let welcome_obj = WelcomeObject {
        id: object::new(ctx),
        message: std::string::utf8(b"Welcome to Wonderland!"),
    };
    transfer::public_transfer(welcome_obj, tx_context::sender(ctx));
}

```

---

## 🧰 Technical Arsenal

<div align="center">

[![Solana](https://img.shields.io/badge/Solana-black?style=for-the-badge&logo=solana)](https://solana.com)
[![Anchor](https://img.shields.io/badge/Anchor-black?style=for-the-badge&logo=anchor&logoColor=white)](https://book.anchor-lang.com/)
[![Rust](https://img.shields.io/badge/Rust-black?style=for-the-badge&logo=rust&logoColor=#E57324)](https://www.rust-lang.org/)
[![SUI](https://img.shields.io/badge/SUI-black?style=for-the-badge&logo=sui)](https://sui.io/)
[![MOVE](https://img.shields.io/badge/MOVE-black?style=for-the-badge)](https://github.com/move-language/move)
[![Ethereum](https://img.shields.io/badge/Ethereum-black?style=for-the-badge&logo=ethereum)](https://ethereum.org)
[![Solidity](https://img.shields.io/badge/Solidity-black?style=for-the-badge&logo=solidity)](https://soliditylang.org/)
[![React](https://img.shields.io/badge/React-black?style=for-the-badge&logo=react)](https://reactjs.org/)
[![React Native](https://img.shields.io/badge/React_Native-black?style=for-the-badge&logo=react)](https://reactnative.dev/)

</div>

---

## 📊 Developer Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=0x7EAB07&layout=compact&theme=radical" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=0x7EAB07&theme=react-dark" alt="GitHub Activity Graph" />
</div>
