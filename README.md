# solarbeam-tokenlist
Solarbeam DEX - Token list

### Whitelisting

- Fork this repo
  ```
  gh repo clone solarbeamio/solarbeam-tokenlist
  ```

- Create a folder under *assets/{blockchainName}/{tokenAddress}*
- Add token's icon (logo.png) under the folder created in the previous step
- Add token's info in the *community.tokenlist.json* file, in this format:
  ```
  {
      "name": [token_name],
      "address": [token_address],
      "symbol": [token_symbol],
      "decimals": [token_decimals],
      "chainId": [chain_id]
  }
  ```
- Make a Pull Request to this repo including all of the above.
- The token address must be checksum formatted (the one that includes uppercase letters) for the folder name and for the .json file.

<br>

More info about pull requests:
- [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
