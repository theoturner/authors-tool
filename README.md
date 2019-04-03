# Botanic/SEED Author's Tool (BAT)

GUI for conversational graph editing/testing and Bot configuration

# Introduction


This project is part of the SEED token project. This is a sneak preview - there is more to come.
See [the Wiki](https://github.com/SeedVault/SEEDtoken-IP/wiki) for more information.

# How to contribute - how to get involved
Go to our **[Developers Garden](https://developers.seedtoken.io)** to see all featured projects, pick one and fill out the **[Developer Interest Form](https://developers.seedtoken.io/#Developer-Interest-Form)**.


# Disclaimer
These files are made available to you on an as-is and restricted basis, and may only be redistributed or sold to any third party as expressly indicated in the Terms of Use for Seed Vault. Seed Vault Code (c) Botanic Technologies, Inc. Used under license.

# Build Development Setup 

## Backend Python code

The Python  backend of the Author's tool is part of Rhizome project [dot_repository folder](https://github.com/SeedVault/rhizome/tree/master/dot_repository) .

A full working version of the backend is available on [Botanic's repository](https://github.com/botanicinc/authors-tool-php) build with PHP language.

## Frontend 

Frontend is bundled with Webpack. It has it's own webserver to provide features like Hot-loading.
This builds and run the application as a development instance and sets the test Hadron web channel's URI

```bash
# To make webpack build dev files and start webpack webserver. 
# This will start listening by default to http://localhost:8080
npm ci
BOTANIC_ENV=local HADRON_URI="https://domain/dev_author/hadron.php" npm run dev
```

### Connect
Feel free to throw general questions regarding SEED and what to expect in the following months here on GitHub (or GitLab) at  @consiliera (gaby@seedtoken.io) :sunny: 

**Connect with us elsewhere** 
- [Follow us on Twitter](https://twitter.com/SEED_token)
- Always here the latest news first on [Telegram](https://t.me/seedtoken) and [Discord](https://discord.gg/Suv5bFT)

Seed Vault Code (c) Botanic Technologies, Inc. Used under license.

