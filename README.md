# Nexo.io To BitcoinTax

Download transactions .csv from nexo.io to use with this script.
Not tested much, use at your own risk.  

Filters out USD and provides a yearly total of USD interest.

## Prerequisites
*   NodeJs (v14.x)
*   Npm

## Getting Started
*   ```npm install```
*   ```npm run build```
*   ```npm run start -- <nexo_transactions.csv file> <nexo-output.csv> <year>```

# Example
```bash
npm run build && npm run start -- nexo_transactions.csv nexo-output.csv 2020
```
