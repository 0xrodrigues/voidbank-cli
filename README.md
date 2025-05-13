# VOIDBANK CLI [🚧 EM CONSTRUÇÃO]

> Um sistema de pagamentos descentralizado com stablecoins, via terminal. Sem custódia, sem bancos, sem servidores — você no controle total.

---

## ✨ Visão

A VOIDBANK é uma ferramenta de pagamentos peer-to-peer que usa stablecoins (como USDT e BRZ) sobre blockchains EVM (Polygon, BSC, etc), focada em:

- **Privacidade e soberania** do usuário
- **Execução real de transações** on-chain
- **Uso local e offline-first** com histórico próprio
- **Interface em linha de comando (CLI)** para controle direto

---

## 🔧 MVP em desenvolvimento

### Funcionalidades previstas:
- Criação/importação de wallet local (seed phrase ou JSON wallet)
- Consulta de saldo de tokens ERC-20
- Geração e assinatura de transações
- Envio de transações via RPC
- Ledger local com recibos e histórico

---

## 📦 Tecnologias

- Rust
- [`ethers-rs`](https://docs.rs/ethers/latest/ethers/) – integração com EVM
- `bip39` – derivação de seed phrase
- `serde_json` – leitura de wallets JSON
- `tokio`, `dotenv`, `clap` – CLI assíncrona e interativa

---

## 📁 Estrutura (inicial)

```
voidbank-cli/
├── src/
│   ├── main.rs
│   ├── wallet.rs         // keypair e integração com carteira
│   ├── transaction.rs    // criação e envio de transações
│   ├── ledger.rs         // histórico local
│   └── cli.rs            // interface de terminal
├── /data                 // arquivos locais (wallet, ledger)
├── Cargo.toml
└── README.md
```

---

## 📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para explorar, modificar e contribuir.

---

## 🚀 Status

Este projeto está em fase de desenvolvimento ativo e em estágio `pre-alpha`.  
Funcionalidades estão sendo definidas e iteradas com base em feedback técnico e testes reais.

---

## 🤝 Contribuição

Contribuições serão bem-vindas assim que a base estiver estável.  
Por enquanto, acompanhe o progresso e abra *issues* se quiser discutir ideias.

---

> Feito com sangue, suor e uma linha de comando.
