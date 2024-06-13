# Update_splsp_script (Sanctum) for Ubuntu

1. [Sanctum cli](https://github.com/igneous-labs/sanctum-spl-stake-pool-cli) and [Solana cli](https://docs.solanalabs.com/cli/install) must be pre-installed.
2. Set solana cluster to mainnet:
```solana config set --url https://api.mainnet-beta.solana.com```
4. Update your solana wallet id.json (If root is used keypair path is: /root/.config/solana/id.json) and fund the address with SOL.
5. Telegram bot token and chat id should be updated in the script.
6. Path to solana (/root/.local/share/solana/install/active_release/bin/solana) and splsp (/root/.local/share/solana/install/active_release/bin/solana) should be updated in the script.
7. Make the script executable with command:
'chmod +x script.sh'
