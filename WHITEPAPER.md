## TPC Toilet-Paper-Coin

#### ( Whitepaper Revision 1.0.0 )

#### TPC: The Future of Digital Currency for Hard Times
-------------------------------

### Abstract
As we've seen during times of economic uncertainty, toilet paper becomes a global safe-haven commodity. This whitepaper not only describes the brilliance of a cryptocurrency backed by, well... white paper but also explains the technical and economic reasoning behind its creation.

### Background
TPC is the implementation of a cryptocurrency in Solidity and is the first decentralized ERC20 token for Ethereum.  It is an open source community project, not led by an official team or corporation, and therefore does not have ICO capital or other vast amounts of currency/capital that a centralized token project would have.  We believe as a community that decentralization is the true flavor of the blockchain and that is the architecture that provides open and transparent trust for users.   We also believe that Ethereum and ERC20 tokens are a significant segment of the future of blockchain technology.

TPC is designed to be used as a decentralized ‘bitcoin-like’ token within the Ethereum ecosystem and beyond. It avoids problems related to centralization and security because it is powered by the Ethereum Network and by globally distributed anonymous miners.  Since it follows a standard protocol (ERC20), it is stored in a traditional Ethereum wallet and it is transferred using standard software which supports EIP20/ERC20 tokens.   Since every TPC token has been mined in a completely decentralized manner, there is no central body or central organization which controls or enforces any aspect of TPC.  The community owns and operates the token in a flat structure and every individual has the same power over the smart contract as any other individual.  This is on purpose in order to follow the same model of a cryptocurrency and to establish TPC as a commodity.

One of the most effective side effects of Satoshi Nakamoto's desire to secure the original a cryptocurrency network with Proof of Work hash mining was tethering and bootstrapping the coin to computing power, thereby removing centralized actor jurisdiction. Transitioning the responsibility of work back onto individual miners, government organizations would have no jurisdiction, and indeed visibility, of mined TPC. Government oversight is removed from an equation whereby miners are providing economic effort in direct exchange of a cryptographic commodity.  This facilitates relatively decentralized distribution and establishes all involved parties as stakeholders.  TPC is a first in class token that allows projects to be funded not by centralized, direct-fiat conversion, but through decentralized computing power.

### Account System

As an ERC20 token, TPC uses a traditional Ethereum account. These accounts are free and are impossible to hack or to steal from, given that the private key has not been exposed.  TPC can be stored in a Ledger Nano, Trezor or any other wallet that supports ERC20 tokens.


## TPC Manufacturers

Anyone with the proper facilities to produce new toilet paper, may become a TPC manufacturer. Manufacturers are voted in by the TPC holder community and they have the ability to create new TPC tokens by staking physical toilet paper. Manufacturers also process and monitor new toilet paper deposits, and take care of TPC token airdrops to addresses written on each 3-ply sheet.

## Smart Contract

Typically, ERC20 tokens will grant all tokens to the owner or will have an ICO which demands that amounts of Ether be sent to the owner for an initial offering of tokens.  Instead of granting tokens to the 'contract owner', all TPC tokens are locked within the smart contract initially. These tokens are dispensed, 50 at a time, by calling the function 'mint' and using Proof of Work, similar to mining bitcoin classic. The TPC smart contract is the first token to adhere to the ERC541 Draft Specification. As such the following Smart Contract methods are explicitly supported:

## Token
### ERC-20 Interface
#### name

Returns the name of the token - e.g. `"TPC Token"`.

OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

``` js
function name() constant returns (string name)
```

#### symbol

Returns the symbol of the token. e.g. `"0xBTC"`.

OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

``` js
function symbol() constant returns (string symbol)
```

#### totalSupply

Returns the total token supply.

``` js
function totalSupply() constant returns (uint256 totalSupply)
```

#### balanceOf

Returns the account balance of another account with address `_owner`.

``` js
function balanceOf(address _owner) constant returns (uint256 balance)
```

### Operations


#### withdraw

Withdraw physical toilet paper to a shipping address.

``` js
function deposit(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

#### deposit (manufacturer only)

Create a TPC token by staking physical 3-ply.

``` js
function deposit(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

### Frequently Asked Questions

#### Does TPC have its own Blockchain?

No. TPC exists on the Ethereum Blockchain as a Smart Contract. This allows it to leverage a faster, more secure and modern crypto environment.

#### Will there be a reward halvening event and when?

No. TPC can only be deposited and withdrawn.

#### Is it bad for the environment.

As long as cryptocurrencies exists, mining will always exist.  Even though mining expends energy, it ultimately reduces corruption in society by providing humanity with decentralized and transparent transactional ledgers.  Therefore the idea similar to humanity having to pay for a gigantic decentralized accounting system or police network which is reducing the widespread financial corruption across the globe.  Just as we pay police officers and accountants for their service, we pay blockchain for its service in the form of energy and computation.

So yeah, probably.

### References

Satoshi Nakamoto. a cryptocurrency: A Peer-to-Peer Electronic Cash System, 2009. http://www.bitcoin.org/bitcoin.pdf.

Logelin J and TPC communitiy members. ERC 541 - Mineable Token Standard Draft, 2018. https://github.com/ethereum/EIPs/pull/918

Fabian Vogelsteller and Vitalik Buterin. ERC-20 Token Standard, 2015. URL https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20-token-standard.md.

TrustNodes. The First PoW a cryptocurrency Like Token Launches on Ethereum, February 16, 2018. https://www.trustnodes.com/2018/02/16/first-pow-bitcoin-like-token-launches-ethereum

Vitalik Buterin. Ethereum White Paper, 2014. https://github.com/ethereum/wiki/wiki/White-Paper

Epstien J. Why Proof of Work in a cryptocurrency Means Proof of Value in the Real World, December 20, 2017. https://www.neverstopmarketing.com/proof-work-bitcoin-means-proof-value-real-world/

Bitfury Group Limited. "Proof of Stake versus Proof of Work", 2015. http://bitfury.com/content/5-white-papers-research/pos-vs-pow-1.0.2.pdf

https://en.bitcoin.it/wiki/Controlled_supply

Dai W. "b-money", 1998. http://www.weidai.com/bmoney.txt

Back A. "Hashcash - a denial of service counter-measure", 2002. http://www.hashcash.org/papers/hashcash.pdf

Cunningham A, Ethereum Co-Founder Announces DAICO, a new ICO Fundraising Model (January 15, 2018). https://discover.coinsquare.io/investing/daico-new-ico-fundraising-model/

Infernal_toast (contract deployer)

Jay Logelin (jlogelin@fas.harvard.edu)
