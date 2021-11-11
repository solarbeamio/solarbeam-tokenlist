# solarbeam-tokenlist
Solarbeam DEX - Token list

### Whitelisting

- Fork this repo
  ```
  gh repo clone solarbeamio/solarbeam-tokenlist
  ```
Make a Pull Request to this repo including:
- Create a folder under *community/* folder with token's address as name
- Add token's icon (.png) under the folder created in the previous step (*community/[TOKEN_ADDRESS]*)
- Add token's info in the *community/community.tokenlist.json* file, in this format:
  ```
  {
      "name": [token_name],
      "address": [token_address],
      "symbol": [token_symbol],
      "decimals": [token_decimals],
      "chainId": 1285
  }
  ```

<br>

More info about pull requests:
- [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)