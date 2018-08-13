# Tokens in bitpie

ETH ERC20 and EOS tokens in this repository will be listed in bitpie wallet. New pull request about new tokens will be reviewed and merged.

## How to submit a new token

1. Fork this repository.

2. Clone your forked repository to your own computer.

3. Copy the json template file for your token type `ETH-ERC20/template.json` or `EOS/template.json`, and fill the template with your token infomation.

4. ETH-ERC20 tokens need to be named as `{{ contract_address }}.json`. EOS tokens need to be named as `{{ coin_code }}_{{ account_name }}.json`.

5. A logo named `logo-{{ json_file_name }}.png` is required in the images directory. We need at least `100px x 100px` squared image.

6. Create a pull request with detailed information of the token.

7. Your pull request will be merged after we review it and everything is OK. In short time after the merge, the token will be listed in bitpie wallet.
