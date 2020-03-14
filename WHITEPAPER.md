## TPC Toilet-Paper-Coin

#### ( Whitepaper Revision 1.0.2 )

#### TPC: The Future of Digital Currency for Hard Times
-------------------------------

### Abstract
As we've seen during times of economic uncertainty, toilet paper becomes a global safe-haven commodity. This whitepaper not only describes the brilliance of a cryptocurrency backed by, well... white paper, but also explains the technical and economic reasoning behind its creation.

### Background
TPC is designed to be used as a decentralized store of toilet paper. TPC users can withdraw and deposit physical 3-ply in the blockchain as reliable digital assets. As a decentralised store of a real world valuable asset with 100% guaranteed liquidity, TPC will be very hard to wipe off the crypto market flooded with shitcoins.

TPC users consist of *consumers* and *manufacturers*. Both roles may call the `withdraw()` function, where as manufacturers are voted every 30 days using the `vote()` function. Voting happens by staking or locking TPC for a 30-day period.

Users voted to be *manufacturer*, can call the `deposit()` function to store physical toilet paper and create new TPC. Manufacturers are expected to accept and process physical toilet paper deposits from new users.

### Account System

As an ERC20 token, TPC uses a traditional Ethereum account. These accounts are free and are impossible to hack or to steal from, given that the private key has not been exposed.  TPC can be stored in a Ledger Nano, Trezor or any other wallet that supports ERC20 tokens.

## TPC Manufacturers

Anyone with the proper facilities to produce new toilet paper, may become a TPC manufacturer. Manufacturers are voted in by the TPC holder community and they have the ability to create new TPC tokens by staking physical toilet paper. Manufacturers also process and monitor new toilet paper deposits, and take care of TPC token airdrops to addresses written on each 3-ply sheet.

## Smart Contract

Typically, ERC20 tokens will grant all tokens to the owner or will have an ICO which demands that amounts of Ether be sent to the owner for an initial offering of tokens. Instead TPC works 100% backed by real, physical 3-ply toiled paper you can count on. The smart contract handles TPO transactions as well as creates / destroys tokens when they are converted to physical toilet paper. The smart contract can utilise funds from TPC manufacturers' Amazon accounts to purchase and ship toilet paper to its owner.

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

Returns the symbol of the token. e.g. `"TPC"`.

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
function withdraw(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

#### vote

Vote for new manufacturers by staking TPC for 30 days.

``` js
function vote(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

#### deposit (manufacturer only)

Create a TPC token by staking physical 3-ply.

``` js
function deposit(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

### Frequently Asked Questions

#### How do I get my toilet paper?

Just call the withdraw function with your shipping address. The smart contract will automatically ship the toilet paper to you within 2 business days.

#### Does TPC have its own Blockchain?

No. TPC exists on the Ethereum Blockchain as a Smart Contract. This allows it to leverage a faster, more secure and modern crypto environment.

#### Will there be a reward halvening event and when?

No. TPC can only be deposited and withdrawn.

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

Infernal_toast

Jay Logelin
