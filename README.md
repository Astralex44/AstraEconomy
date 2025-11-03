# Astra's Economy (Fabric Mod, WIP)

A Minecraft Fabric mod for **1.21.x** that introduces a fully item‑based economy system. Players trade, bank, and manage physical currency — not virtual numbers. Every coin, wallet, and key is a real in‑game item with tangible risk and ownership.

---

## 🎯 Core Concept

Astra's Economy transforms Minecraft's abstract money systems (as we probably all know it from several servers with diamonds or other valuable items) into something physical and immersive. Coins, wallets, and vault keys are real in-game items that can be dropped, stolen, or secured. This makes trade, banking, and risk management meaningful again.

---

## 🪙 Planned Features

* **Coins** – Multiple denominations of real currency items.
* **Wallets** – Portable containers that hold money and financial documents.
* **Bank System** – On‑site bank stations where players can deposit, withdraw, or transfer funds.
* **Vaults** – Player‑assigned bank lockers accessible only with physical keys.
* **Invoices** – Paper documents representing debts or pending payments, enforceable via the bank.
* **Shops** – Buy and sell items for real coins or create credit‑based transactions.
* **SQLite Persistence** – All economic data is stored locally for reliability and easy backups.

---

## ⚙️ Technical Overview

* **Platform:** Fabric 1.21.x
* **Language:** Java 21+
* **Database:** SQLite (via JDBC)
* **Dependencies:** Fabric API, Cloth Config (planned)
* **Future Compatibility:** Architectury support for NeoForge optional.

---

## 🧩 Structure (Planned)

```
📁 src/main/java/com/yourmodid/
 ├─ YourMod.java
 ├─ registry/ModItems.java
 ├─ registry/ModBlocks.java
 ├─ wallet/WalletItem.java
 ├─ coin/CoinItem.java
 ├─ bank/BankStationBlock.java
 └─ database/SQLiteManager.java

📁 resources/assets/yourmodid/
 ├─ models/item/coin.json
 ├─ models/item/wallet.json
 └─ textures/item/...
```

---

## 🧠 Design Philosophy

* **Physical over virtual** – Every currency unit is an item you can hold, drop, or lose.
* **Player‑driven trust** – Credit and debt exist through tangible invoices, not commands.
* **Immersive realism** – Banking requires being physically present at a station.
* **Extendability** – Easily add new currencies, documents, or permissioned keys.

---

## 🛠️ Development Roadmap

1. **Core Item System** – Coins, wallets, NBT‑based verification.
2. **Bank Stations** – Deposit/withdraw logic & proximity checks.
3. **Vault Keys** – Owner‑created, signed key items for secure lockers.
4. **Invoices & Enforcement** – Debts, payment enforcement, auto‑settlement.
5. **Shops & Trading** – Chest/NPC/GUI shops with cash or invoice options.
6. **Polish & Balance** – Configs, GUIs, security & anti‑dupe systems.

---

## 📜 License & Contribution

This project is currently **Work‑In‑Progress**.
Contributions, ideas, and pull requests are welcome once the base structure is stable.
Stay tuned for detailed contribution guidelines and roadmap updates.

---

## 🧰 Author

Created by **Astralex** – Aiming to build a realistic, item‑driven economy for Minecraft Fabric servers.
