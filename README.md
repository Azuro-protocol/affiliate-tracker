# Affiliate-Tracker

Welcome to [Azuro](https://azuro.org/)! 

Please add your frontend name and affiliate wallet address to the `config.json` file. This helps us provide you with tailored information on statistics and resolve any issues more efficiently.

Please use the following format for your entries:

```json
{
  "wallet": "your_wallet_address",
  "frontendName": "your_frontend_name"
}
```

The overall structure of the `config.json` file should be an array of such entries, as shown below:

```json

[
  // existing entries
  {
    "wallet": "existing_wallet_address",
    "frontendName": "existing_frontend_name"
  },
  // your new entry
  {
    "wallet": "your_wallet_address",
    "frontendName": "your_frontend_name"
  }
]
```

Thank you for your contribution! 
If you have questions or need assistance with anything concerning Azuro, find us on [Discord](https://discord.gg/5jzdjCYk).
