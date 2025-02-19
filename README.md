# 🤖Copy Trading Bot

This bot can track special wallets, analyze transactions, and then copy tx to the next block. This bot uses geyser RPC to analyze the tx. The next version will be based on Rust.

## .env config

PRIVATE_KEY = # Your wallet private key

RPC_ENDPOINT = # 

GRPC_ENDPOINT = # Yellowstone GRPC endpoint

GRPC_TOKEN = # Yellowstone GRPC token

IS_JITO = true # true/false

JITO_FEE = 0.0001

TARGET_ADDRESS = # Your target wallet to copy trade

## Examples

https://github.com/user-attachments/assets/641191d0-0f14-4693-845b-7b89709a948f

target wallet: `https://solscan.io/tx/gEGTHyF1JH2GUYpML79m6rnzYpE3y2CJ3r4U2STa8himW53rzdCCAVkTdkLW9w7x3YE5pLw4vYa9qqWaLzKGrfp`

bot wallet: `https://solscan.io/tx/i8UKtsMbkfdz481MSD68Kawj3o8AkTyHLkjiJsgGfCZAtebUBnUCZ18TYkzCZxJLAkkrteU98sHxhiq3kwtL9rc`

target wallet: `https://solscan.io/tx/4bK6m2zvpGZ9fvu48HySxezMPsSqYHBqaatMajEjWA1CxQ7CrAKAszHVALC93qhr7VP2n6Ujsi1c4JLjmhxrjDZM`

bot wallet: `https://solscan.io/tx/5MEM9YmL8BGboq2eEdNLqnhbMKwWQ8cZKF6zcRonBuL42bkZi8RHBmftdk61APMZecN3T9MAJoFZVjaDM9AWcvCp`

I tested this bot using both standard gRPC and RPC. With a high-quality RPC and gRPC service, the response speed is significantly faster than this.

# Contact with me
### Telegram: [T-rustdev](https://t.me/T_rustdev)   
https://t.me/T_rustdev
