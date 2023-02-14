<img src="https://e-talk.xyz/wp-content/uploads/2023/02/a54cc409-6123-43d5-9bb2-1a55a6ac93fb.png" alt="ikọbọ (ETK)" width="300"/>
<br/><br/>
ikọbọ (ETK) [ikọbọ, ETK]  
</h1>

<div align="center">

[![ikọbọBadge](https://img.shields.io/ikọbọbadge/-Coin-yellow.svg)](https://E-talk.xyz)
[![LET'S CONNECT](https://img.shields.io/badge/LET'S-CONNECT-yellow.svg)](https://E-talk.xyz)

</div>
# i-k-b-ETK
ERC20 Token
The public interface of ikọbọ (ETK) is the ERC20 interface specified by EIP-20.

name()
symbol()
decimals()
totalSupply()
balanceOf(address who)
transfer(address to, uint256 value)
approve(address spender, uint256 value)
allowance(address owner, address spender)
transferFrom(address from, address to, uint256 value)  And the usual events.

event Transfer(address indexed from, address indexed to, uint256 value)
event Approval(address indexed owner, address indexed spender, uint256 value)
Typical interaction with the contract will use transfer to move the token as payment. Additionally, a pattern involving approve and transferFrom can be used to allow another address to move tokens from your address to a third party without the need for the middleperson to custody the tokens, such as in the 0x protocol.

Warning about ERC20 approve front-running
There is a well known gotcha involving the ERC20 approve method. The problem occurs when the owner decides to change the allowance of a spender that already has an allowance. If the spender sends a transferFrom transaction at a similar time that the owner sends the new approve transaction and the transferFrom by the spender goes through first, then the spender gets to use the original allowance, and also get approved for the intended new allowance.

The recommended mitigation in cases where the owner does not trust the spender is to first set the allowance to zero before setting it to a new amount, checking that the allowance was not spent before sending the new approval transaction. Note, however, that any allowance change is subject to front-running, which is as simple as watching the mempool for certain transactions and then offering a higher gas price to get another transaction mined onto the blockchain more quickly.
License - Much license ⚖️
ikọbọ (ETK) is released under the terms of the MIT license
