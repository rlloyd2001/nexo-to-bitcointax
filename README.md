# Nexo.io To BitcoinTax

This script has saved me many hours of data entry for interest earned.
What this script does is take a .csv file from nexo.io and create a .csv file that can be
uploaded into the Income section of bitcoin.tax.

Download transactions .csv from nexo.io to use with this script.
Not tested much. Review your generated .csv before uploading to bitcoin.tax to make sure this is what you are needing.

Filters out USD and prints a yearly total in the console of USD interest.

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

## Donate with PayPal

Did you find this helpful? Leave a tip.

### PayPal
https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=rlloyd2001%40gmail.com&currency_code=USD
