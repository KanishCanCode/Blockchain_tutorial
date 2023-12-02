Contract description:

This contract includes the following methods:

totalSupply(): Returns the total supply of tokens.
balanceOf(address account): Returns the balance of tokens for a specific account.
allowance(address owner, address spender): Returns the amount of tokens that an owner has allowed a spender to spend.
transfer(address recipient, uint256 amount): Transfers a specified amount of tokens to a recipient.
approve(address spender, uint256 amount): Approves a spender to spend a specified amount of tokens.
transferFrom(address sender, address recipient, uint256 amount): Transfers a specified amount of tokens from a sender to a recipient.
The contract also includes the following events:

Transfer(address indexed from, address indexed to, uint256 value): Emitted when tokens are transferred.
Approval(address indexed owner, address indexed spender, uint256 value): Emitted when tokens are approved for spending.
