# 🚀 Bot Setup Instructions

Welcome to the bot setup guide! Follow the steps below to install and configure the bot correctly. This guide is designed to be beginner-friendly, with clear explanations for each step.

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)

---

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Configuration Files](#configuration-files)
   - [`configs.json`](#1-configsjson)
   - [`tokens.txt`](#2-tokenstxt)
   - [`wallets.txt`](#3-walletstxt)
   - [`proxies.txt`](#4-proxiestxt)
4. [Running the Bot](#running-the-bot)
5. [Contact and Support](#contact-and-support)

---

## Prerequisites

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on setup.bat or setup.sh if you want to run automatically, remember to fill all the necessary data.

---

## Installation Steps

1. **Download and Extract the Bot Files:**

   - Extract the bot package into a folder on your computer.

2. **Install Dependencies:**
   Open your terminal or command prompt, navigate to the folder where the bot files are located, and run:

   ```bash
   npm install user-agents axios colors https-proxy-agent socks-proxy-agent 
   ```

3. **Prepare Configuration Files:**
   - Ensure all configuration files are set up correctly before running the bot (see [Configuration Files](#configuration-files) section).

---

## Configuration Files

### 1. `configs.json` - 📜 Adjust Bot Settings

This file controls the bot’s behavior. Below is an example configuration:

```json
{
  "rotateProxy": false,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [1, 1],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 10,
  "doTasks": true,
  "referralCode": "A_6713068747_inviteEarn"
}
```

- **Fields Explained:**
  - `rotateProxy`: Enable or disable proxy rotation.
  - `skipInvalidProxy`: Skip invalid proxies if `true`.
  - `proxyRotationInterval`: Time interval (in minutes) for rotating proxies.
  - `delayEachAccount`: Random delay range (in seconds) between accounts.
  - `timeToRestartAllAccounts`: Time (in seconds) to restart all accounts.
  - `howManyAccountsRunInOneTime`: Number of accounts to run simultaneously.
  - `doTasks`: Enable task completion.
  - `referralCode`: Add your referral code (optional). Do not change it if you want to support me ^^

### 2. `tokens.txt` - 🗂️ User Data

Fill the data for `datas.txt` file from [here](https://t.me/KeoAirDropFreeNee/1609). This file contains user data in the following format:

```txt
ey...
ey...
ey...
```

_Note: Each row for each account_

### 3. `wallets.txt` - 💼 Wallet Addresses

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

Add your wallet addresses in the following format:

```txt
abc...xyz
abc...xyz
abc...xyz
```

_Note: Wallet updates are currently not supported._

### 4. `proxies.txt` - 🌐 Proxy List (Optional)

If you are using proxies, add them here. Leave the file blank if you are not using proxies. Supported formats:
- [Get it from here](https://www.webshare.io/?referral_code=4l5kb3glsce7)

```txt
[http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port](http://host:port
https://host:port
socks4://host:port
socks5://host:port
http://user:pass@host:port
https://user:pass@host:port
socks4://user:pass@host:port
socks5://user:pass@host:port)
```

_Note: each row for each account_

---

## Running the Bot

1. Navigate to the folder containing the bot files:

   ```bash
   cd /path/to/bot-folder
   ```

2. Run the bot using the following command:
   ```bash
   node meomundep
   ```

---

## Contact and Support

- **Help me with your referral** [Referral Link](https://t.me/UXUYbot/app?startapp=A_6713068747_inviteEarn)
- **Buy me a telegram account** [Here](https://t.me/KeoAirDropFreeNe/312/27801) or [Here](https://github.com/MeoMunDep/MeoMunDep)

If you encounter any issues or have questions, feel free to reach out:

- **Contact:** [Contact Me](https://t.me/MeoMunDep)
- **Group:** [Join the Group](https://t.me/KeoAirDropFreeNe)
- **Channel:** [Visit the Channel](https://t.me/KeoAirDropFreeNee)

Your support is greatly appreciated! 🐱

---

Enjoy using the bot! 🚀
