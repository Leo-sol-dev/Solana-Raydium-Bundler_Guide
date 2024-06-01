# Solana Raydium Bundler - Jito Bundling

#### Solana Raydium Bundler that creates token, creates market ID, creates pool and bundle buy from that pool using jito bundling.

## 🏆 Principle

Solana has jito bundling function that puts number of transactions into the bundle ensuring all transactions in the bundle gets confirmed in turn and atomically, also letting no other transcations get intercepted into middle, which is well known as MEV transactions.

This bot can launch Raydium AMM Pool on the Raydium using jito bundle transactions, so that the pool creator can get the initial supply of the token at launch time as first sniper. (Somtimes it is called **self-sniping** 😊)

### Then, why in the hell they try to snipe their token? 😂😂😂

If you get the token in the first place, by self-sniping, you can make pool status up to better, and also those token purchased at first will be used to RUG 👹👿 users.  

*Joking...*

Anyway, It's up to you to use this or not


## Manual
- Clone the git repository

```
https://github.com/Leo-sol-dev/Solana-Raydium-Bundler_Guide.git
```

- Set the **.env** parameters

```
CLUSTER=devnet
MAINNET_RPC_URL=
DEVNET_RPC_URL=
PINATA_API_KEY=aaaaaaaaaaaaaaaaaaa
PINATA_SECRET_API_KEY=afdasfasdfasdfsdavcfdfdsfsadfasdfasdfasdfasdfasdfasdfdsfdsfasdfasdfsdaf

# jito setting
JITO_KEY=
BLOCKENGINE_URL=tokyo.mainnet.block-engine.jito.wtf
JITO_FEE=0.001

....
```

Set the mainnet rpc and devnet rpc, pinata key is for uploading token metadata and image to IPFS.
Jito key can be omitted in this bot, since jito is updated to higher version.

There are volume bot added to the bundler that can be used after token launch and bundling process, you can use them after you get the bot.

If you need bot, please contact me with twitter or telegram.

**Contact Info**
-  **Telegram** :  [Leo_sol_dev](https://t.me/Leo_sol_dev)
- **Twitter** :  [Leo_sol_dev](https://x.com/Leo_sol_dev)
