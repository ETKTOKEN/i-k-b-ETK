<h1 align="center">
<img src="https://e-talk.xyz/wp-content/uploads/2023/01/img_1687-1.png" alt="ikọbọ (ETK)" width="300"/>
<br/><br/>
ikọbọ (ETK) [IKB, ETK]  
</h1>

<div align="center">

[![ikọbọ E-TALK](https://e-talk.xyz/wp-content/uploads/2023/02/Safeimagekit-resized-img.png)](https://E-talk.xyz)
[![LET'S CONNECT](https://img.shields.io/badge/LET'S-CONNECT-yellow.svg)](https://E-talk.xyz)

</div>

Select language: EN | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md)

I-k-B- (ETK)
ERC20 Token The public interface of ikọbọ (ETK) is the ERC20 interface specified by EIP-20.

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
 Whitepaper

## ikọbọ ETK

# The future of commerce
A decentralized network for online payment 
February 14, 2022
## CONTENT 
# 1 Executive summary 
# 2 The platform 
# 3 The ecosystem 
# 3.1 The Core layer
# 3.2 The Extensions layer 
# 4 Use cases
# 5 B2B payments
# 6 Online Payment 
# 7 Accounting
# 8 Business Logic and Trade Laws 
# Government and Tax 
# 9 Transparency of institutions
# 10 IoT and smartcontracts
# 11 Token
# 12 Incentive for a secure ecosystem of  applications 
# 13 Governance  
# 14 Make cross currency exchanges easier.
# Roadmap draft
# Team
#  Core-team
# Thanks 
# Bibliography


## (1) ikọbọ is a open-source peer-to-peer digital currency, powering E-TALK. 
ikọbọ is the crypto movement that makes people smile! It is also an open source peer-to-peer cryptocurrency that utilises blockchain technology, a highly secure decentralised system of storing information as a public ledger that is maintained by a network of computers called nodes. ikọbọ is the native cryptocurrency used in E-TALK ecosystem and E-TALK online shop. ikọbọ (ETK) is a decentralized network that allows anyone to request a payment (a Request Invoice)for which the recipient can pay in a secure way. All of the information is stored in a decentralized authentic ledger. This results in cheaper, easier, and more secure payments, and it allows for a wide range of automation possibilities.
To become the backbone of world trade, ikọbọ integrates a general ledger (in the accounting sense of the term), which is:
- Universal because it is designed to support 100% of global transactions, regardless of currency, legislation or language. ikọbọ is built to last.
- Smart because unlike an existing standard accounting book, ikọbọ is at the origin of the exchanges and integrates a computerized trade code, as well as the management of a multitude of payment terms.
Today, their absence makes the whole system inefficient and absolutely unready for the digital and IoT (Internet Of Things) revolution that is taking place.
ikọbọ can be seen as a layer on top of Ethereum, which allows requests for payments for goods and services that satisfy a legal framework.It is also possible to see currencies as tools to complete ETK transactions. In this sense, ETK is more global than any currency.
## (2) E-TALK is The platform
Anyone can access and create a Request for Payment For goods and services with ikọbọ (ETk) . And The payment can be detected by the recipient monitoring the network (via a wallet or via a financial application). If the trade is approved by the user, it can be paid with a single click. Then the trade is completed and the network is updated.
When a trade is created, the trade laws that are applicable to its specific case are taken into account, and taxes are applied. When necessary, advanced payment terms may be selected. 
Let’s make an example with bob and Alice 

Bob is requesting an apple from Alice

Bob asks Alice for a crypto payment option , then he creates an (invoice) and relays it to the blockchain; Alice’s wallet detects the Request and and Alice processes the payment.
In the case where Bob was on E-talk and Alice was making a purchase, E-talk creates a Request with ETK on the blockchain, Alices analyzes the blockchain and detects the request, sends a notification, and she agrees to pay in ETK Since the E-talk global market accepts ETK as the Native cryptocurrency payment.
Request completed. 
• Security: it is not necessary to share banking information 
• Simplicity: it requires only to click a button
• Savings: purchases dont require a third party (eg. Paypal or stripe )

## (3) The ecosystem 
Many developments will be possible on top of E-TALK once the Core protocol is finished by the team. Our Tech mind map gives a full picture of the E-TALk Network and the upcoming roadmap.
We believe the E-TALK ecosystem is the key to success, and we very much would like to nurture it. In order to drive this decentralization forward and help  
E-TALK to scale, here is an introduction to E-talk Hub. What we call E-Talk Hub is the community outside the E-talk foundation that is willing to work on top of E-talk , create teams and projects around E-talk , and help with its decentralization.

## (3.1) The Core layer
The bottom layer is the Core, which manages the consensus over the ledger and the states transitions. It consists of the most fundamental smart contracts, allowing the creation of different entities and requests for payments. It also detects when payments have been completed. It is based on immutability (ie. no one can change the information), the openness of its system (everyone can access information that concerns them) and an intelligence that allows it to know when an invoice is paid according to the rules in the invoice.
This layer takes place on the Ethereum blockchain, which brings endogenous benefits for Ethereum and ERC20-labeled invoices, such as automatic detection. Other currencies are also covered via automatic pay- ment detection through the use of Oracles.
This layer is free to encourage the greatest number to use it and to discourage the development of other systems. The only costs transmitted are the use of Ethereum gas and the storage of information.


## (3.2)The Extensions layer
The second layer is the Extensions layer. Most payment created today are not as basic as the one proposed by the Core layer. If the payment comes from an enterprise, then it includes rules for calculating taxes, payment terms, escrows or advances. All of these conditions take the form of available extensions that can be added to payment . This layer is the gateway to incredible features that do not yet exist, such as ”continuous bills”. For example, someone could choose this module to break down their rent into 30x24 payments to the landlord, leaving this person with a fluid bank account without large end-of-month expenses. Taxes would be rerouted in real time to government agencies. With each payment, 20% of VAT would go to taxes and 80% to the recipient company. The same example would allow everyone to give 1% of all payments to NGOs (Non Governmental Organizations), or to deposit them into ones own retirement account.
This layer is chargeable, in that each extension will take a fee that will be partially burned and partially transferred to the extension developers, with the extensions accrued on the same invoice. Costs decrease over time to remain competitive and discourage alternative systems. The costs of these extensions is estimated to be between 0.1% and 0.5% initially, though as the system grows, the costs will be reduced. More than 5,000 billion dollars in payments are made each day, and in the end it will be enough to finance the network by less than 0.1%. Nonetheless, the costs will continue to support the security of applications and their development. This layer is completely open, whereupon anyone can create their own extensions, with the fees also being distributed in a way that will interest and encourage the developer and the community

## (4) Use cases
The use cases of this technology are extremely wide. This system automates real-time global accounting, replaces an entire branch of the audit, eliminates manual tax collection, simplifies international payments, allows machines to communicate on the same financial field, replaces payment systems such as Paypal, and makes the most advanced payment terms available to everyone.


## (5) B2B invoicing
Billions of invoices are shared each year between companies, with most of them still being sent in paper and email format, which have to be copied. This results in a large number of errors, particularly when advanced payment or tax rules are applied.
With blockchain , companies can share these bills directly via the ledger; there will be no more duplication, as accounting systems will be immediately plugged in and updated.




## (6) Online payments
For example, shopping on Amazon requires payment by credit/debit card, thereby exposing sensitive infor- mation. But on E-Talk  selecting the option to pay via ETK , the users data remain protected. E-talk will post a Request on the network, the user’s account will detect it and request a confirmation of payment from the user on their wallet . This will trigger a transfer at the lowest cost, without exposing the payment information.
It becomes possible to avoid unforeseen credit/debit card payments that services charge in a hidden way, because it provides a way to validate payments before they happen. E-talk empowers people.
The advantages of E-TAlk , compared to current systems, are:
• Security: Payment information is never shared, there is no risk that someone intercepts and reuses banking information.
• Simplicity: One click to pay, and no manual input error possible.

## (7) accounting statements.
In the computer consulting industry, the cost of the accounting officer’s time to process an invoice is be- tween $5 and $20. To this amount can be added the time necessary for monthly checkings and corrections. The automation of the entire system is slow.
The use of blockchain for accounting is an opportunity to simplify compliance, and improves double-entry accounting. Double-entry accounting dates back to the Renaissance, where it allowed managers to have confidence in their own reports. Nowadays, to justify trust, independent auditors verify the information of the major groups in a process that is costly in both time and money. The audit firm then becomes a trusted third party guaranteeing the veracity of the information established by the financial statements. However, the auditors maintain responsibility over the companies, which generates mistrust. Do the auditors work for the managers of the companies that mandate them, or for the service of the third parties who consult the information for free?
Thus, instead of holding internal accounts and publishing them after the annual audit, companies can keep accounts in a decentralized, confidential and shared database with blockchain technology. All account- ing entries are then entered into the register, without the possibility of backdating, which means there is no opportunity for falsification. Therefore, it would become more difficult to make questionable year-end adjustments, and most importantly, the company benefits from this system in real time. Shareholders and external parties have access to real-time information. The cost of auditing becomes insignificant, and ac- counting entries no longer require duplicate manual checks. Finally, the integrity of the financial statements can no longer be called into question when customers and suppliers are interconnected with this system, at least by their cryptographic addresses.
ETK is a distributed registry that acts as a source of confidence, ultimately allowing these ”smart audits” in real-time. It includes all purchases and sales of the company. Instead of having double-entry accounts, where the information regarding a purchase appears in the purchase account and in the bank ac- count separately, one can see within the blockchain a purchase account, linked to the supplier.



## (8) Business Logic and Trade Laws: Government and Tax
Governments requiring companies to report all transactions could again be creating errors and duplications. ETK allows governments to specifically view the real-time transactions that they have access to. Furthermore, the development of a module to levy VAT, or, for example, a transatlantic tax, will redirect the money automatically.
Whether one is pro-government or not, the possibility, for the first time, to simplify and make transparent the levies of taxes is a real improvement.
Blockchain technology allows government agencies to have the ability to detect financial instabilities, fraud, money laundering and financial crime in advance, and operate based on these observations.
The UK government’s scientific wing has recently identified a number of ways that the blockchain can ”revolutionize citizen-state relations.” For example: helping the government collect taxes and distribute aid



## (9) Trust: 
We are in the era of open source projects and collaboration, transparency fosters trust in a society where peoples opinions and interests are respected and where public money is used appropriately.
• Quality: Budget review, as code review, allows to detect waste, misuse and gives insights on how to improve the outcome for more responsivity and impact.
E-TALK  proposes a framework which allows these institutions to adopt transparency conveniently, to publish their account in real time and to anyone to audit and use these data.


## (10) IoT and smart contracts
An exciting challenge of the coming years will surely be to imagine how objects, machines and artificial intelligences will interact with each others, and how they will automatically negotiate and define payment terms. They will need a payment framework which specifies the payment and help to define the reasons and conditions of the transaction.
One can imagine a self-contained car order a new wheel to a virtual garage, make a down payment and pay the remaining 90% only at delivery.
## (11) Token
While it is built on the blockchain ledger of Ethereum, ETK aims to be independent from other currencies, monetary policies, or technological choices so that we build the most robust system possible. We believe this is the key to evolve through time with a growing community and develop an ecosystem around our framework where more DAPP (Decentralized applications) are created.

## (12) Incentive for a secure ecosystem of applications
ETK  tokens are ERC20 tokens which are necessary to participate in the network, create advanced payment and reward with various parties who will help build the E-talk ecosystem.
When using the network, the participants will need to pay a network fee in ETH which is know has gas .

## (13) Governance
We have a strong desire to build E-TALK ecosystem that lasts tens or even hundreds of years. A system that can not only be used by historians to see what commerce looked like in the 21st century, but also a system that will take us into the future, with the power and structure to be used when artificial machines and intelligence will account for the majority of transactions.
For this reason, EKT will have to remain flexible and scalable,
The ETK token will bring the community together and make all smile, allow for discussions and votes on future deci- sions. The community will be a board and we will create the necessary tools for this administration: A voting system, but also probably a chat system with conversation not restricted to only members of this board.because we believe that everyone has something to say or offer  
Using ETk token is the most flexible and independent way to conceptualize a system that will need consensus and security to evolve in the long term and

## (14) Make cross currency exchanges easier
We will propose a model where loops of payment can be identified automatically by the system and settled without requiring a fund shift. For example, if Alice owes money to Bob who owes money to Charlie who himself receives a request for payment from Alice, the system can offer compensation for these bills and the ETK  will settle offsetting differences.
and making crypto and fiat accessable to everyone without borders or retractions  


## Roadmap 

# ETK Pyramid: Q3 2022
-Release final draft of white paper

-Launch the E-talk website

## Request Colossus: Q4 2022
-Token Launch
-First version of ETK working with Ethereum on Test Net
--First version of ETK working with BNB  on Test Net
-Deploy the website to Create/Visualize and interact with ETK 

## Request Great Wall: Q1 2023
-First version of ETK working with Ethereum on a main net 
-ETK on BNB Chain 
-Deploy management of Crypto-currencies on ETK (ERC20 tokens)
-Proof of concept : Request Core working with a Bitcoin Oracle
-Work on partnerships with Accounting, Payment and Audit firms
-Deploy Inter-currency settlement through ETK to facilitate international payments
-Deploy the governance system (Vote/Token Chat)
-launch our mobile app on iOS and android 
-Deploy the Tax extension to automatically pay taxes in real time










## Team
Core team
Our team is our strongest asset for the ETK project. All of its members have worked together in the past, for terms ranging from 6 months to 6 years. We are doers. Our experiences in finance, blockchain and entrepreneurship are combined to rethink the international trade organization of tomorrow.






## Who are we?
To name but a few of the roles held by our team, we have practiced as: financial director, IT manager, financial auditor, accountant, management controller, treasurer, data analyst, front end developer, back end developer, lead developer, and blockchain developer. These roles have spanned industries including consul- tancy, finance, pharmaceutical, music, research, and fintech.
We think in blockchain, fintech and finance terms, and we believe that there are far more transparent and healthy alternatives to the way that banks operate today.

E-talk Digital is the first and world leader in web3 shows and information on the space, we seeks to inform, engage and empower the world. Service 24 hours, seven days a week by a dedicated team in E-talk around the world, E-talk digital platforms deliver everything about web3, nfts, crypto,news, entertainment, truth


and beyond let’s talk let’s connect let’s get to know what’s happening around the globe.


## Our mission


We are storytellers and truth-seekers.


We are entertainers, designers, and technologists who are committed to educating, energizing, and empowering the global community.


We observe history being made and then explain not just what happened but also why and what it means to you.


By delivering information and services that improve your life, those of your families, and those of your communities, our products and platforms transport you to the furthest reaches of the globe and bring the globe to you.


e-talk is a socially-minded tech company striving to bridge the gap between those in need and those who can help. We believe that with the right technology and a connected global community, we can create positive social change. Our platform is designed to facilitate conversations and connections between people and causes, helping them to communicate more effectively and efficiently. We believe that everyone has something to offer and we’re here to make sure that everyone’s voice is heard. By harnessing the power of technology, we’re building a platform that can help to create real and lasting change. E-talk.xyz and E-talkshow media offer 24/7 coverage of all the latest shows/entertainment through web3 and web2 with E-talk Truth show/E-talk live radio and global online markets.


## Why ETALK?







## When did it start?







## Presentation of the members of the team:
