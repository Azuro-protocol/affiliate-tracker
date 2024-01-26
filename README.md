# Affiliate-Tracker

Welcome to Azuro! To participate, please add your frontend name and affiliate wallet address to the `config.json` file. This enables us to provide tailored information on stats and resolve any issues more efficiently.

Please use the following format for your entries:

```json
{
  "wallet": "your_wallet_address",
  "frontendName": "your_frontend_name"
}
```json

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
```json

Thank you for your contribution!
