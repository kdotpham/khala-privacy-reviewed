# Privacy: Who Captures the Value?

Authors: 0xSammy; Jack Ai-Leung
Publication date: 2026-11-02
Market-cap snapshot: 2026-10-15
Canonical report: https://kdotpham.github.io/khala-privacy-reviewed/

Slide 17: SAMPLE DATA · NOT FOR POSTING. Its monthly chart contains placeholders. Slide 23 scenarios are illustrative assumptions. Nullmask market values were observed 2026-10-19; other peer market caps retain the 2026-10-15 snapshot.

## Slide 1: Privacy products are growing, but token value capture remains uneven


Executive summary
1 Companies now need confidentiality to transact on-chain With $306B of stablecoins on public ledgers, payroll and OTC deployments are testing how companies can settle transactions confidentially. $306B stablecoins on public ledgers 2 Privacy tokens use different routes to value capture Zcash is held as money and Venice funds VVV buybacks from revenue, while Nym and UR (SN25) together account for $30.6M in market value. $30.6M Nym and UR (SN25) combined market cap 3 Most privacy tokens do not yet connect usage to value Aztec secures $58K in user funds, while Umbra directs fees to its DAO and UR (SN25) keeps its operator-deposit rate at zero. $58K user funds secured on Aztec 4 UR (SN25) has users, with token demand still conditional URnetwork reports 350K monthly users, but usage-linked demand for UR (SN25) depends on a non-zero operator-deposit rate. 350K monthly users (team-reported)
Catalysts to watch First operator deposit on UR (SN25) Aztec v6 and the 13 November unlock Umbra’s Nimbus network launch Storm retrial, 26 April 2027

[View slide 1](https://kdotpham.github.io/khala-privacy-reviewed/#summary)

## Slide 2: Privacy is becoming necessary for corporate payments


As corporate payments move onto public ledgers, Buterin and Durov argue for privacy in the networks people already use.
In this section
Stablecoins on public ledgers 3
Buterin and Durov 4
Policy has turned 5
Payroll and trading 6
Where markets pay for privacy 7

[View slide 2](https://kdotpham.github.io/khala-privacy-reviewed/#act1)

## Slide 3: Public ledgers expose the activity behind $306B of stablecoins


Stablecoin supply exceeds crypto ETFs, DeFi and tokenised assets combined, exposing payment flows and counterparty relationships on public ledgers.
Public payments can reveal a company’s counterparties, payment amounts and treasury balances.
Tether and Circle account for 84% of supply; their public transfers can be monitored.
Public payroll and supplier payments can expose information companies normally keep confidential.
“For users that prioritize privacy, this could become a ‘must-have’ feature.” Zach Pandl, Head of Research, Grayscale, on AI and financial privacy, September 2026

### Capital in selected onchain financial products, by component

Chart labels in display order: Stablecoin supply · USDT 60% · USDC 24% · Others 16% · USDT $184.0B · USDC $73.1B · Others $49.0B · $306B Mid-Oct 2026 · ETFs, DeFi and tokenised assets combined, $254B · US spot crypto ETFs · Bitcoin 86% · Bitcoin $105.8B · Ether $15.7B · Solana $1.7B · $123B Oct 2026 · Value locked in DeFi · Others 41% · Lido $24.3B · Aave $18.6B · Morpho $11.2B · Others $37.3B · $91B Mid-Oct 2026 · Tokenised real-world assets · Treasuries $14.9B · Credit $8.2B · Gold and commodities $5.2B · Other $10.9B · $39B 14 Oct 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| USDT: $184.0B | Tether. 60% of stablecoin supply. | DefiLlama, 15 October 2026 |
| USDC: $73.1B | Circle. 24% of stablecoin supply. | DefiLlama, 15 October 2026 |
| Others: $49.0B | USDS, USDe, DAI, USD1 and others. 16% of stablecoin supply. | DefiLlama, 15 October 2026 |
| Bitcoin: $105.8B | US spot bitcoin ETFs. 86% of us spot crypto etfs. | The Block, 10 October 2026 |
| Ether: $15.7B | US spot ether ETFs. 13% of us spot crypto etfs. | The Block, 10 October 2026 |
| Solana: $1.7B | US spot Solana ETFs. 1% of us spot crypto etfs. | The Block, 10 October 2026 |
| Lido: $24.3B | Liquid staking. 27% of value locked in defi. | DefiLlama, 15 October 2026 |
| Aave: $18.6B | Lending. 20% of value locked in defi. | DefiLlama, 15 October 2026 |
| Morpho: $11.2B | Lending. 12% of value locked in defi. | DefiLlama, 15 October 2026 |
| Others: $37.3B | All other protocols. 41% of value locked in defi. | DefiLlama, 15 October 2026 |
| Treasuries: $14.9B | Tokenised US Treasury funds. 38% of tokenised real-world assets. | rwa.xyz, distributed value, 14 October 2026 |
| Credit: $8.2B | Private credit and other non-sovereign debt. 21% of tokenised real-world assets. | rwa.xyz, distributed value, 14 October 2026 |
| Gold and commodities: $5.2B | Mostly XAUT and PAXG. 13% of tokenised real-world assets. | rwa.xyz, distributed value, 14 October 2026 |
| Other: $10.9B | Equities, funds, real estate and alternatives. 28% of tokenised real-world assets. | rwa.xyz, distributed value, 14 October 2026 |

[View slide 3](https://kdotpham.github.io/khala-privacy-reviewed/#capital)

## Slide 4: Buterin and Durov both place privacy in core infrastructure


The founders of Ethereum and of a messaging app with over a billion users reach the same conclusion from different starting points.
Vitalik Buterin
Co-founder
Ethereum
“Privacy is not about standing apart. It’s about standing together.” Why I support privacy, 14 April 2025
Why it matters
Control over information is power, so privacy protects decentralisation, personal freedom and institutions such as the secret ballot.
Where it belongs
Privacy belongs in the protocol, covering payments, application activity, chain reads and network-level anonymity.
Current gap
Much of the proposal remains a roadmap that wallets and applications would need to implement.
Pavel Durov
Founder and CEO
Telegram, over 1B monthly users
“Telegram would rather exit a market than undermine encryption with backdoors and violate basic human rights.” Telegram channel, 21 April 2025
Why it matters
Encryption protects everyday communication and personal safety, and any access built for authorities is also available to attackers.
Where it belongs
The product should exclude backdoors, even if that means withdrawing from a market.
Current gap
Telegram’s default Cloud Chats are not end-to-end encrypted; only Secret Chats are.
Implication Both argue for privacy in systems people already use, making wallet and application adoption central to how widely it reaches users.

[View slide 4](https://kdotpham.github.io/khala-privacy-reviewed/#founders)

## Slide 5: US policy has shifted toward privacy, while developer liability remains open


Sanctions were lifted, builders returned and institutional capital followed, although developer liability remains unresolved.

### From enforcement to infrastructure

Chart labels in display order: 2023 · 2024 · 2025 · 2026 · Tornado Cash under sanctions for 31 months · the 19 months since, in detail below · Aug 2022 · US Treasury sanctions Tornado Cash · Nov 2024 · Fifth Circuit rules its immutable contracts are not property · Mar 2025 · Treasury lifts the sanctions · Apr 2025 · Buterin publishes an L1 privacy · roadmap; Durov pledges no backdoors · Jul 2025 · GENIUS Act sets a federal stablecoin · framework · Oct 2025 · Paxos Labs and Aleo announce USAD; · Ethereum Foundation forms a Privacy · Cluster · Jan 2026 · a16z names privacy crypto's most · important moat · Aug 2026 · Grayscale's Zcash ETF lists, $463M · in two weeks · Policy · Builders and capital

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| 31 months under sanctions | From 8 August 2022 to March 2025, Tornado Cash was on the OFAC sanctions list. | US Treasury |
| Aug 2022 | OFAC added Tornado Cash's smart contracts to the sanctions list on 8 August 2022. |  |
| Nov 2024 | Van Loon v. Department of the Treasury, decided 26 November 2024. |  |
| Mar 2025 | Treasury removed Tornado Cash from the sanctions list in March 2025. |  |
| Apr 2025 | Buterin's roadmap was posted on 11 April 2025; Durov's statement followed on 21 April 2025. |  |
| Jul 2025 | Federal framework for payment stablecoins, July 2025. |  |
| Oct 2025 | USAD was announced on 1 October 2025; the Privacy Cluster in October 2025. |  |
| Jan 2026 | Ali Yahya, a16z crypto: “bridging tokens is easy, bridging secrets is hard”. |  |
| Aug 2026 | ZCSH began trading on NYSE Arca on 25 August 2026 and held $463.2M by 7 September 2026. |  |

[View slide 5](https://kdotpham.github.io/khala-privacy-reviewed/#policy)

## Slide 6: Payroll and trading are the first commercial tests of confidentiality


Encrypting amounts is not sufficient on its own, because the network connection can still reveal who is transacting.

| Use case | What must stay private | Evidence so far | Who is building or backing it |
| --- | --- | --- | --- |
| Payments and payroll Company-reported deployments | Salaries, supplier invoices and treasury movements | Bron paid salaries in confidential USDT on Ethereum mainnet through Zama, January 2026 | Zcash Monero Umbra Zama Bron Aleo |
| Trading and tokenised assets Company-reported deployments | Orders, positions and holdings | GSR executed a confidential OTC trade on the Zama protocol, March 2026; Dfns added confidential tokens to its wallet platform | Zama Dfns Pantera investor |
| Private computation and AI NEAR AI live; others building | Customer data and model inputs | NEAR AI Cloud runs confidential inference with an attestation per request; secure-hardware and MPC networks are building | Venice NEAR AI Seismic a16z investor Nillion Hack VC investor |
| Private connectivity URnetwork live; others building | IP addresses and who is talking to whom | URnetwork’s VPN reports about 350K monthly users (team-reported); NymVPN runs on the Nym mixnet | UR (SN25) Nym Orchid Sentinel Mysterium |
| Programmable privacy Building | Hidden inputs for sealed-bid auctions, private ballots and strategy games | Reusable tools, so each application does not need its own cryptography | Fhenix Zama Multicoin investor Aztec Noir |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Payments and payroll | Bron paid salaries in confidential USDT on Ethereum mainnet through Zama, January 2026 | Zama and Bron, 16 January 2026 |
| Trading and tokenised assets | GSR executed a confidential OTC trade on the Zama protocol, March 2026; Dfns added confidential tokens to its wallet platform | GSR, 12 March 2026 |
| Private computation and AI | NEAR AI Cloud runs confidential inference with an attestation per request; secure-hardware and MPC networks are building | NEAR AI, 3 December 2025 |
| Private connectivity | URnetwork’s VPN reports about 350K monthly users (team-reported); NymVPN runs on the Nym mixnet | URnetwork; Nym |
| Programmable privacy | Reusable tools, so each application does not need its own cryptography | a16z; Multicoin |

[View slide 6](https://kdotpham.github.io/khala-privacy-reviewed/#usecases)

## Slide 7: Privacy demand alone does not set token value


Zcash and Venice show different routes to token demand, with network-capacity peers adding context to the 15 October 2026 market-cap comparison on a logarithmic USD scale.
Although Grass and Helium provide benchmarks for networks that sell capacity, their valuations do not establish a fair value for UR (SN25).
The network-privacy comparison includes Nym and UR (SN25).

### Market capitalisation by privacy category, logarithmic USD scale. Network privacy includes Nym and UR (SN25) only.

Chart labels in display order: 1M · 10M · 100M · 1B · 10B · 100B · Transaction privacy · Zcash · $20.8B · Monero · $10.2B · Private AI · Venice · $1.1B · Paid network capacity · Grass · $486M · Helium · $85.0M · Network privacy · Nym · $22.2M · UR (SN25) · $8.4M

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| ZEC: ~$20.8B | Zcash. | CoinGecko and MEXC, 15 October 2026 |
| XMR: ~$10.2B | Monero. | CoinGecko and MEXC, 15 October 2026 |
| Venice: ~$1.1B | Private AI inference; revenue funds VVV buybacks and burns. CoinGecko, mid-October 2026. | CoinGecko and MEXC, 15 October 2026 |
| Grass: ~$486M | Sells residential bandwidth to AI firms; about $17M of 2025 revenue (team-reported). | CoinGecko and MEXC, 15 October 2026 |
| Helium: ~$85.0M | Carriers and subscribers pay for coverage; about $50K of data credits burned a day (Blockworks, June 2026). | CoinGecko and MEXC, 15 October 2026 |
| NYM: ~$22.2M | Nym mixnet. | CoinGecko and MEXC, 15 October 2026 |
| UR (SN25): ~$8.4M | Bittensor subnet 25; market cap from MEXC. | CoinGecko and MEXC, 15 October 2026 |

[View slide 7](https://kdotpham.github.io/khala-privacy-reviewed/#priced)

## Slide 8: Token designs differ in how usage reaches holders


Each privacy network sells a different service, so what users pay does not necessarily become value for tokenholders.
In this section
Privacy token comparison 9
Zcash 10
Nullmask ($MASK) 11
Aztec 12
Umbra 13
Venice 14

[View slide 8](https://kdotpham.github.io/khala-privacy-reviewed/#act2)

## Slide 9: Privacy tokens capture value differently


Nullmask, Aztec and Umbra address private onchain activity, while Venice offers private AI access and UR (SN25) supplies connectivity.
Adoption figures cover live products, historical wallets, account counts and reported monthly users, so they are not directly comparable.

|  | Nullmask Wallets | Aztec Wallet Azguard | Umbra Wallet Phantom | Venice Token access | UR (SN25) Access URnetwork app |
| --- | --- | --- | --- | --- | --- |
| What it produces | Private transfers and swaps. Deposits and withdrawals are public. | Ethereum L2 for private contracts, balances and execution. | Private Solana balances, transfers and swaps. Deposits and withdrawals stay public. | Private AI chat, images and APIs. Prompts are not stored on its servers. | Bandwidth and routing. Providers carry traffic and validators measure performance. |
| Reported adoption | Live pools Ethereum and Base; supported assets only | 100K+ legacy Connect wallets; retired product | 3,428 existing encrypted accounts on Solana | ~21.9K wallet profiles indexed by VeniceStats | 350K+ monthly app users; team-reported, off-chain |
| Who pays for it | Users pay 0.5% on deposits and withdrawals, plus network fees. | Users or apps pay fees. Emissions also pay operators. | Users pay fees and tips. Protocol fees reach the DAO. | Subscriptions, API credits or VVV staked for inference. | Customers pay operators. Subnet revenue is separate. |
| Does value reach the token | Reported rewards Dashboard lists MASK burns and ZEC rewards separately from service fees. | Fee + stake AZTEC pays fees and supports staking. Congestion fees burn. | Governance UMBRA governs its treasury. There is no automatic buyback or dividend. | Stake + burn VVV enables inference. Part of credit revenue buys and burns VVV. | Conditional Deposits can lock tokens. The launch rate is zero; new buying is not guaranteed. |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Wallet access | Nullmask names MetaMask and Rabby as supported wallet examples. Compatibility does not imply a commercial partnership or wallet-wide privacy. Checked 19 October 2026. | https://nullmask.io/docs/getting-started |
| Wallet access | Aztec documents Azguard as the available browser extension wallet for Aztec apps. The Aztec CLI wallet is also documented for advanced users. Do not confuse legacy Aztec Connect support with current private-wallet compatibility. Checked 19 October 2026. | https://docs.aztec.network/participate/basics/wallets |
| Wallet access | Phantom is advertised in Umbra’s live Connect wallet chooser. This is a verified example, not an exhaustive compatibility list. No wallet was connected and no registration or transaction was performed. Checked 19 October 2026. | https://v2.umbraprivacy.com/ |
| Wallet access | Venice’s official DIEM guide names MetaMask and Coinbase Wallet on Base for acquiring VVV/DIEM and using token access. These are access/payment wallets, not a claim of private wallet transactions. Checked 19 October 2026. | https://learn.venice.ai/guides/how-to-use-venices-diem-token-for-daily-ai-credits |
| App access | URnetwork is the consumer VPN app supplied by UR (SN25). Wallet integrations are not interchangeable with network privacy. No external-wallet compatibility claim is made here. Checked 19 October 2026. | https://ur.io/ |
| Nullmask ($MASK) | Private balances and transfers inside shielded pools; swaps conceal the user, but assets and amounts stay public. Nullmask can read account history. | https://nullmask.io/docs/privacy |
| Aztec | Ethereum L2 for private smart contracts: confidential balances, state and execution |  |
| Umbra | Private balances, transfers and swaps for Solana assets; deposits and withdrawals stay public |  |
| Venice | Private AI chat, images and API access on open-source models; prompts are not stored on its servers |  |
| UR (SN25) | Bandwidth and routing marketplace: independent providers carry traffic, validators score performance |  |
| Nullmask ($MASK) | Official documentation lists ETH and USDT on Ethereum, and ETH and USDC on Base. This cell describes product availability, not a monthly user count. Checked 20 October 2026. | https://nullmask.io/docs/networks |
| Aztec | Aztec reports over 100,000 active wallets for the retired Aztec Connect product. This historical count is not current-network adoption. |  |
| Umbra | 3,428 encrypted user accounts on Solana |  |
| Venice | ~21.9K wallets indexed by VeniceStats |  |
| UR (SN25) | 350K+ monthly URnetwork app users (team-reported, off-chain) |  |
| Nullmask ($MASK) | Deposit and withdrawal fees are 0.5%; swaps have no Nullmask protocol fee, although DEX and network fees still apply. Fees checked 19 October 2026. | https://nullmask.io/docs/fees |
| Aztec | Users pay fees or apps sponsor them; operator rewards are partly token emissions |  |
| Umbra | Users pay protocol fees and relayer tips; protocol revenue accrues to the DAO treasury |  |
| Venice | Users pay subscriptions or API credits, or stake $VVV for a daily share of inference |  |
| UR (SN25) | Customers pay operators; URnetwork's UR Pro subscription is operator revenue, not automatically subnet revenue |  |
| Nullmask ($MASK) | The pool contract collects product fees. The dashboard adds those fees to developer-wallet ZEC rewards in its revenue total; MASK holder rewards and burns are separate metrics. These disclosures do not establish an automatic product-fee payout to holders. | https://app.nullmask.io/analytics |
| Aztec | $AZTEC funds fees, staking and governance; congestion fees burn, the rest pays operators |  |
| Umbra | $UMBRA governs the treasury via MetaDAO markets; no automatic buyback or dividend |  |
| Venice | $VVV is staked for inference capacity, and a share of credit purchases buys back and burns it |  |
| UR (SN25) | UR (SN25) alpha funds emissions and locked operator deposits, which can be zero; buys not enforced |  |

[View slide 9](https://kdotpham.github.io/khala-privacy-reviewed/#tokens)

## Slide 10: Zcash prices in future private use


The shielded share of ZEC supply rose through 2025, then fell in the first half of 2026.
Although ZEC’s market value is roughly twice Monero’s at the mid-October snapshot, most activity still settles transparently.
The valuation assumes wider private use than the current activity demonstrates.
Q2 2026 network fees
Transparent ~$92K Shielded ~$18K

### Share of ZEC supply held in shielded pools

Chart labels in display order: ~8% · Start of 2025 · ~23% · Dec 2025 · 31.0% · End Q1 2026 · 26.3% · End Q2 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Q2 2026 network fees | About $92K of about $110K came from transparent transfers. | Blockworks Advisory, funded by GenZcash |
| Start of 2025 | About 8% of supply | The Block, 26 December 2025 |
| Dec 2025 | About 23% of supply | The Block, 26 December 2025 |
| End Q1 2026 | 31.0%, about 5.16M ZEC | Blockworks Advisory, funded by GenZcash |
| End Q2 2026 | 26.3%, or 4.42M ZEC | Blockworks Advisory, funded by GenZcash |

[View slide 10](https://kdotpham.github.io/khala-privacy-reviewed/#zcash)

## Slide 11: Nullmask brings private transfers and swaps to existing wallets

**Nullmask product documentation and reward-accounting disclosures checked 2026-10-20. Deposits and withdrawals are public; the operator can read private balances and history. Market cap/FDV retain the 2026-10-19 observation date. Product fees and token rewards are separate reported metrics, not proof of automatic fee sharing. Solana and private perpetuals remain roadmap targets.**

Nullmask lets users hide transfers from public observers through their existing wallets, but the operator can read their activity and reports MASK rewards separately from service fees.
What it sells Private transfers and swaps through shielded pools, using your existing wallet. Ethereum Base
MASK rewards and burns The dashboard reports ZEC holder payouts and MASK burns separately from service fees, without documenting an automatic distribution of those fees to holders.
Evidence of demand Nullmask’s 0.5% deposit and withdrawal fees are one part of reported revenue, which also includes ZEC rewards paid to the developer wallet.
What has to be true The product needs repeat paying usage to grow, with Solana and private perpetuals still on the roadmap and operator visibility remaining a trust assumption.

### Nullmask product flow: existing wallet, shielded pool, relayed actions and public withdrawal; valuation snapshot 19 October 2026

Chart labels in display order: Deposits and withdrawals remain public · Existing wallet · MetaMask · Rabby · Same wallet signs each action · Shielded pool · 0.5% deposit fee · deposit · Transfer or swap · Relayer submits the action · Swap assets and amounts visible · act · Withdraw · 0.5% withdrawal fee · Destination and amount public · exit · Private from chain watchers · The operator can still read private balances and history. · $27.7M · Market cap · 19 Oct 2026 · $45.8M · FDV · 19 Oct 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Supported wallets | Nullmask’s getting-started documentation explicitly names MetaMask and Rabby. These are supported wallet examples, not a claim of a commercial partnership or privacy for all activity in those wallets. Checked 19 October 2026. | https://nullmask.io/docs/getting-started |
| Shielded pool | Balances and private transfers are hidden from chain observers. Deposits publish the source, asset and amount. | https://nullmask.io/docs/privacy |
| Relayed transfers and swaps | Private transfers conceal the sender, recipient and amount. A swap publishes its assets and amounts, but not who made it. | https://nullmask.io/docs/swap |
| Withdrawal | The recipient, asset, amount, fee and timing are public. Amount and timing can still link pool entry and exit. | https://nullmask.io/docs/privacy |
| Who can see the history? | Nullmask servers can read private balances and history. The privacy claim protects against outside blockchain observers, not the operator. | https://nullmask.io/docs/privacy |
| MASK market cap: $27.7M | Circulating market cap $27.74M; observed 19 October 2026. This is a newer snapshot than the existing 15 October peer comparisons. | https://defillama.com/protocol/nullmask |
| MASK fully diluted value: $45.8M | Fully diluted value $45.83M; observed 19 October 2026. Market cap and FDV are not interchangeable. | https://defillama.com/protocol/nullmask |
| What it sells | Private transfers and swaps through shielded pools. Official documentation names MetaMask and Rabby as wallet examples and Ethereum and Base as networks. Compatibility does not mean a wallet partnership. | https://nullmask.io/docs/getting-started; https://nullmask.io/docs/networks |
| MASK rewards and burns | The dashboard reports ZEC holder payouts and MASK burns separately from service fees, without documenting an automatic distribution of those fees to holders. | https://app.nullmask.io/analytics |
| Evidence of demand | Nullmask’s 0.5% deposit and withdrawal fees are one part of reported revenue, which also includes ZEC rewards paid to the developer wallet. | https://app.nullmask.io/analytics |
| What has to be true | The product needs repeat paying usage to grow, with Solana and private perpetuals still on the roadmap and operator visibility remaining a trust assumption. | https://nullmask.io/docs/project-roadmap |

[View slide 11](https://kdotpham.github.io/khala-privacy-reviewed/#nullmask)

## Slide 12: Aztec has $12M staked against $58K in user funds


User funds remain small relative to staking and valuation on the logarithmic USD chart, while Aztec’s 7 August proving-bug disclosure adds a security concern.
What it sells Private smart contracts on Ethereum: confidential balances, state and execution, written in Noir.
How value reaches the token Fees are paid in AZTEC, congestion fees burn, and sequencers must stake 200,000 AZTEC to produce blocks.
What has to be true v6 closes the proving bug disclosed on 7 August, and apps bring user funds well above today’s $58K.
Supply risk Only 29% is circulating, the Foundation unlocks on 13 November, and governance can mint up to 20% of supply a year.

### Aztec value staked versus value secured

Chart labels in display order: $10K · $100K · $1M · $10M · $100M · $1B · Fully diluted value · $207M · Market cap · $60M · Staked by sequencers · $12M · User funds secured · $58K

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Fully diluted value: $207M | All 10.35B AZTEC at $0.020 | CoinDesk, Tokenomist, L2BEAT; 14 to 16 October 2026 |
| Market cap: $60M | 2.99B AZTEC circulating (29%) | CoinDesk, Tokenomist, L2BEAT; 14 to 16 October 2026 |
| Staked by sequencers: $12M | 586.9M AZTEC staked by 3,136 sequencers | CoinDesk, Tokenomist, L2BEAT; 14 to 16 October 2026 |
| User funds secured: $58K | Value secured on the rollup, per L2BEAT | CoinDesk, Tokenomist, L2BEAT; 14 to 16 October 2026 |
| What it sells | Private smart contracts on Ethereum: confidential balances, state and execution, written in Noir. |  |
| How value reaches the token | Fees are paid in AZTEC, congestion fees burn, and sequencers must stake 200,000 AZTEC to produce blocks. |  |
| What has to be true | v6 closes the proving bug disclosed on 7 August, and apps bring user funds well above today’s $58K. |  |
| Supply risk | Only 29% is circulating, the Foundation unlocks on 13 November, and governance can mint up to 20% of supply a year. |  |

[View slide 12](https://kdotpham.github.io/khala-privacy-reviewed/#aztec)

## Slide 13: Umbra’s fees reach its treasury, with no automatic payout to holders


Umbra sells private balances, transfers and swaps on Solana, and its token governs a treasury rather than collecting fees.
What it sells A private wallet for Solana assets with screening and viewing keys; Nimbus, its network for other apps, is coming soon.
How value reaches the token Fees go to a DAO treasury that UMBRA holders steer through MetaDAO markets, giving them governance control without an automatic buyback or dividend.
Why the vesting matters Team and adviser tokens unlock only when fully diluted value reaches 2×, 4×, 8×, 16× and 32× the $0.30 sale price.
What has to be true Nimbus brings other apps onto Umbra and deposits grow well beyond today’s $187K.

### Umbra price against its sale price

Chart labels in display order: $0.30 · Sale price · $2.48 · Peak · $0.17 · Low · $0.37 · 15 Oct 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Sale price: $0.30 | MetaDAO sale, October 2025: $3M accepted from $155M committed | DefiLlama; MetaDAO |
| Peak: $2.48 | All-time high, 12 October 2025 | DefiLlama; MetaDAO |
| Low: $0.17 | All-time low | DefiLlama; MetaDAO |
| Today: $0.37 | 15 October 2026 | DefiLlama; MetaDAO |
| What it sells | A private wallet for Solana assets with screening and viewing keys; Nimbus, its network for other apps, is coming soon. |  |
| How value reaches the token | Fees go to a DAO treasury that UMBRA holders steer through MetaDAO markets, giving them governance control without an automatic buyback or dividend. |  |
| Why the vesting matters | Team and adviser tokens unlock only when fully diluted value reaches 2x, 4x, 8x, 16x and 32x the $0.30 sale price. |  |
| What has to be true | Nimbus brings other apps onto Umbra and deposits grow well beyond today’s $187K. |  |

[View slide 13](https://kdotpham.github.io/khala-privacy-reviewed/#umbra)

## Slide 14: Venice converts part of customer revenue into VVV buybacks


Venice uses revenue from private AI chat and API access to fund VVV buybacks, alongside a reduction in annual issuance from 14M to 2M tokens.
New VVV issued per year
What it sells Venice offers private AI chat, images and API access through open-source models, with prompts encrypted on the device and kept off its servers.
How value reaches the token Staking VVV enables inference access and DIEM minting, with each staked DIEM providing $1 in daily API credits and $5 of every $100 in credit purchases funding VVV buybacks and burns.
Evidence of demand 3.5M registered users and a $100M annualised revenue run rate (company-reported, August 2026), after a $65M Series A at a $1B valuation led by Dragonfly.
What has to be true Revenue keeps growing so buybacks outpace the remaining issuance, and holdings become less concentrated than today’s top wallets.

### VVV annual issuance

Chart labels in display order: 14M · At launch · 3M · Before Sep 2026 · 2.5M · From 1 Sep 2026 · 2M · From 1 Oct 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| At launch: 14M VVV a year | January 2025 | Decrypt, 21 September 2026; Phemex, 19 August 2026 |
| Before Sep 2026: 3M VVV a year | Annual issuance before 1 September 2026 | Decrypt, 21 September 2026; Phemex, 19 August 2026 |
| From 1 Sep 2026: 2.5M VVV a year | Annual issuance from 1 September 2026 | Decrypt, 21 September 2026; Phemex, 19 August 2026 |
| From 1 Oct 2026: 2M VVV a year | Annual issuance from 1 October 2026 | Decrypt, 21 September 2026; Phemex, 19 August 2026 |
| What it sells | Venice offers private AI chat, images and API access through open-source models, with prompts encrypted on the device and kept off its servers. |  |
| How value reaches the token | Staking VVV enables inference access and DIEM minting, with each staked DIEM providing $1 in daily API credits and $5 of every $100 in credit purchases funding VVV buybacks and burns. |  |
| Evidence of demand | 3.5M registered users and a $100M annualised revenue run rate (company-reported, August 2026), after a $65M Series A at a $1B valuation led by Dragonfly. |  |
| What has to be true | Revenue keeps growing so buybacks outpace the remaining issuance, and holdings become less concentrated than today’s top wallets. |  |

[View slide 14](https://kdotpham.github.io/khala-privacy-reviewed/#venice)

## Slide 15: UR (SN25) has users, but priced deposits have yet to begin


URnetwork has an established user base, but converting its traffic into token demand depends on introducing priced operator deposits.
In this section
Where privacy leaks 16
URnetwork users 17
How UR (SN25) works 18
Operators as UR (SN25) buyers 19
The bull case 20
How value reaches UR (SN25) 21
UR (SN25) can host operators in billion-dollar enterprise and AI-agent markets 22
What to watch 23
Catalysts across the coverage universe 24

[View slide 15](https://kdotpham.github.io/khala-privacy-reviewed/#act3)

## Slide 16: Wallet privacy can fail at network connections and cross-chain swaps

**Primary paper checked on 2026-10-18: address-to-IP linking under controlled router observations; Ethereum mainnet and testnet are separate. Not a population-wide exposure estimate; UR (SN25) was not tested.**

In a 2025 controlled experiment, researchers linked wallet addresses to IPs with 95–98% success after 3–4 observations, a result specific to the study’s setup.
Swap boundaries: reused refund addresses can link activity
RPC traffic: address-to-IP linking in controlled tests
Because researchers observed encrypted RPC traffic through controlled routers and did not test UR (SN25), the study does not establish UR’s protection.

### Swap route into shielded ZEC and where it leaked

Chart labels in display order: Wallet elsewhere · SOL, ETH or USDC · NEAR Intents · Solvers fill the swap · Shielded ZEC · Private balance · Refund · A reused transparent refund address · can link amounts and timing · $1.5B+ · ZEC swap volume through · NEAR Intents by March 2026 · (sponsored research)

### Controlled TRAP experiments: wallet-address-to-IP linking success, by blockchain and network

Chart labels in display order: 0% · 50% · 100% · Ethereum mainnet · MetaMask · 3 observations · 95.3% · Ethereum testnet · MetaMask · 3 observations · 96.8% · Bitcoin testnet · Electrum · 4 observations · 97.7% · Solana testnet · Torus · 4 observations · 96.6%

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Wallet elsewhere | SOL, ETH or USDC |  |
| NEAR Intents | Solvers fill the swap |  |
| Shielded ZEC | Private balance |  |
| Refund address reuse | Reusing a transparent refund address can link activity. ECC’s Q4 2025 roadmap proposed ephemeral addresses. Zashi iOS release 2.4.7 (5 November 2025) added ephemeral-address recovery; 2.4.8 (17 November 2025) updated NEAR swaps to unified addresses. This diagram illustrates address-reuse risk, not a current Zodl vulnerability. | https://zodl.com/ecc-roadmap-q4-2025/; https://github.com/zodl-inc/zodl-ios/blob/main/CHANGELOG.md |
| $1.5B+ through NEAR Intents | Cumulative ZEC swap volume by the end of March 2026. | CoinDesk Research, sponsored by GenZcash |
| Ethereum mainnet: 95.33% | MetaMask · 3 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8–10; https://arxiv.org/html/2508.21440v1 |
| Ethereum testnet: 96.80% | MetaMask · 3 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8–10; https://arxiv.org/html/2508.21440v1 |
| Bitcoin testnet: 97.70% | Electrum · 4 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8–10; https://arxiv.org/html/2508.21440v1 |
| Solana testnet: 96.58% | Torus · 4 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8–10; https://arxiv.org/html/2508.21440v1 |

[View slide 16](https://kdotpham.github.io/khala-privacy-reviewed/#edges)

## Slide 17: UR (SN25) reports 350K monthly users

**SAMPLE DATA · NOT FOR POSTING. Monthly chart values are placeholders, not observed history. The 350K headline is separately team-reported.**

The monthly series is illustrative and ends at the team-reported figure of 350K monthly users.
126,717 providers across 103 countries
Although URnetwork reports an existing user base, its zero launch deposit rate means app usage does not yet require operators to buy UR (SN25).
The bars show the chart layout, not measured monthly growth.
SAMPLE DATA · NOT FOR POSTING

### Placeholder monthly active users chart. Sample data, not for posting.

Chart labels in display order: 120K · 1 APR 2026 · 150K · 1 MAY 2026 · 185K · 1 JUN 2026 · 220K · 1 JUL 2026 · 265K · 1 AUG 2026 · UR (SN25) launches on Bittensor UR (SN25) · 300K · 1 SEP 2026 · 330K · 1 OCT 2026 · 350K · 15 OCT 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Apr 1 | 120K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |
| May 1 | 150K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |
| Jun 1 | 185K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |
| Jul 1 | 220K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |
| Aug 1 | 265K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |
| Sep 1 | 300K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |
| Oct 1 | 330K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |
| Oct 15 | 350K monthly active users | SAMPLE DATA — NOT FOR POSTING. Placeholder monthly series. |

[View slide 17](https://kdotpham.github.io/khala-privacy-reviewed/#mau)

## Slide 18: UR (SN25) uses validator scores to reward routing capacity

**Design is distinct from launch: the documented launch has a UR-run operator and sole validator. The 200-fleet figure is a design cap.**

Launch documentation describes one UR-run operator and validator, with provider allocation starting at 10% of the native miner share.
126,717 Providers on URnetwork (team-reported)
103 Countries covered (team-reported)
Up to 200 Top-level fleet capacity in the design; not a live count
$8.4M UR (SN25) market cap, mid-October 2026

### How UR (SN25) works

Chart labels in display order: Customers · Privacy apps and VPN users · Network operators · Sell privacy, co-sign paths · Miners · Route encrypted traffic · Subnet reserve · Operator deposits held here · UR (SN25) emissions · Miners 41% · validators 41% Owner 18% · Validators · Re-measure paths, score pools · pay · route · measure · weights · pay for measured capacity · operators deposit UR (SN25) against expected traffic

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Customers | Customers buy privacy and connectivity from operators such as URnetwork's consumer VPN. | UR (SN25) litepaper |
| Network operators | Operators run privacy servers and a verification endpoint and decide how rewards split among their miners. | UR (SN25) litepaper |
| Miners | Pool providers and up to 200 top-level fleets are design tiers; 200 is a capacity limit, not a verified count of live fleets. | https://github.com/urfoundation/sn#two-miner-tiers-in-parallel |
| Subnet reserve | Deposits are sized to measured traffic at a published rate. The launch price schedule sets the rate to zero. | UR (SN25) litepaper |
| UR (SN25) emissions | 18% owner / 41% native miner allocation / 41% validators describes the standard design. Launch provider weights start at 10% of the native miner allocation, with the remainder directed to the reserve; this is not a current 41% direct-provider payout. | https://github.com/urfoundation/sn#emission--yuma-consensus |
| Validators | Independent validation is a design assumption. Launch documentation states that UR runs the sole operator and validator and scores its own pool. | https://github.com/urfoundation/sn/blob/main/VALIDATOR.md |

[View slide 18](https://kdotpham.github.io/khala-privacy-reviewed/#sn25)

## Slide 19: Priced deposits could create demand for UR (SN25)


Although the launch rate is zero, priced deposits would lock UR (SN25) against traffic, with revenue-funded purchases expected in the design but not enforced.
The illustrative bars show deposits exceeding miner emissions above the dotted line, without assigning a calibrated deposit rate.
Deposits lock UR (SN25) in a reserve with no outbound transfer path, but operators can fund them from existing holdings rather than new market purchases.

### UR (SN25) demand by number of operators

Chart labels in display order: MINER EMISSIONS · ur.io · 1 operator · ONCE PRICED · ur.io alone · ur.io · vpn.dev · ww.dev · 3 operators · NEXT · adds vpn.dev and ww.dev · ur.io · vpn.dev · ww.dev · Operator 4 · Operator 5 · Operator N · N operators · AT SCALE · additional operators

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| ur.io | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| ur.io | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| vpn.dev | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| ww.dev | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| ur.io | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| vpn.dev | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| ww.dev | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| Operator 4 | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| Operator 5 | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |
| Operator N | Illustrative priced-deposit case: locks tokens against usage. Funding from new market purchases is expected, not enforced; existing inventory can be used. | Illustrative design; https://github.com/urfoundation/sn#deposits--the-demand-signal-conviction-stake-and-a-buyback |

[View slide 19](https://kdotpham.github.io/khala-privacy-reviewed/#operators)

## Slide 20: UR (SN25) would be worth 10× at Helium’s market cap and 58× at Grass’s


The 15 October 2026 comparison places UR (SN25) at $8.4M, Helium at $85M and Grass at $486M on a logarithmic USD scale, illustrating relative size rather than a modelled valuation.
A wide valuation gap Transaction-privacy assets are valued at about $31B, against $30.6M for Nym and UR (SN25), a gap of around 1,000 times.
A product already in market URnetwork, the VPN that UR (SN25) supplies, reports about 350K monthly users and 126,717 providers across 103 countries, so the thesis does not depend on a product launch.
Demand linked to usage If a non-zero rate is adopted, usage-based deposits would lock tokens, although growing traffic would not guarantee new market buying because revenue-funded purchases are not enforced.
What UR (SN25) would be worth at its peers’ market caps

### UR (SN25) market cap against peers

Chart labels in display order: $1M · $10M · $100M · $1B · UR (SN25) · $8.4M · Nym · $22.2M · 2.6x · Helium · $85M · 10x · Grass · $486M · 58x

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| A wide valuation gap | Transaction-privacy assets are valued at about $31B, against $30.6M for Nym and UR (SN25), a gap of around 1,000 times. |  |
| A product already in market | URnetwork, the VPN that UR (SN25) supplies, reports about 350K monthly users and 126,717 providers across 103 countries, so the thesis does not depend on a product launch. |  |
| Demand linked to usage | If a non-zero rate is adopted, usage-based deposits would lock tokens, although growing traffic would not guarantee new market buying because revenue-funded purchases are not enforced. | https://github.com/urfoundation/sn |
| UR (SN25) today: ~$8.4M | UR (SN25) market cap, mid-October 2026. | CoinGecko and MEXC, 15 October 2026 |
| Nym: ~$22.2M | Mixnet with its own VPN; rewards moving to gateways that serve users. | CoinGecko and MEXC, 15 October 2026 |
| Helium: ~$85M | Carriers and subscribers pay for coverage; about $50K a day of data credits burned. | CoinGecko and MEXC, 15 October 2026 |
| Grass: ~$486M | Sells residential bandwidth to AI firms; about $17M of 2025 revenue (team-reported). | CoinGecko and MEXC, 15 October 2026 |

[View slide 20](https://kdotpham.github.io/khala-privacy-reviewed/#bull)

## Slide 21: Operator deposits could link UR (SN25) demand to usage


While TAO inflows and sector interest support UR (SN25) today, priced operator deposits would add demand by locking tokens against network traffic.
How value can reach UR (SN25)
1
TAO inflows Bittensor sets each subnet's emissions by its net TAO inflows over about three months, so staking into UR (SN25) lifts emissions and alpha demand.
Live since November 2025
2
Sector re-rating UR (SN25) trades as Bittensor's privacy exposure while capital rotates into the category.
Live
3
Operator deposits Priced deposits lock tokens against traffic; fresh market purchases are expected, not enforced.
Rate set to zero at launch
4
Reserve governance The current reserve has no outbound transfer path; a different future architecture is not a present holder right.
Current reserve design

### Who pays and where value accrues

Chart labels in display order: paid by token issuance · paid by customers · network · token · issuer · or app · Emissions subsidy · durable only if demand arrives · Customer-paid fees · durable: Zama, Railgun · Weakest · neither side captures it · Issuer economics · captured by issuers: USAD, Bron · UR (SN25) today · operator deposits · UR (SN25) if operators pay

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Emissions subsidy | Supply is paid in newly issued tokens. Value holds only if paying demand follows. |  |
| Customer-paid fees | Customers pay per transfer or computation, and the fees reach the network token. |  |
| Weakest | Issuance pays for supply and the value accrues to apps or issuers. |  |
| Issuer economics | Customers pay, but reserve yield and fees accrue to issuers and distributors. |  |
| UR (SN25) today | Bittensor emissions pay for supply and value reaches UR (SN25) through TAO inflows; no customer fees reach the token yet. |  |
| UR (SN25) if operators pay | Priced deposits would lock tokens against traffic; new market buying is expected, not enforced. |  |
| TAO inflows | Bittensor sets each subnet's emissions by its net TAO inflows over about three months, so staking into UR (SN25) lifts emissions and alpha demand. | UR (SN25) litepaper; FalconX |
| Sector re-rating | UR (SN25) trades as Bittensor's privacy exposure while capital rotates into the category. | UR (SN25) litepaper; FalconX |
| Operator deposits | Priced deposits lock tokens against traffic; purchases from revenue are expected off-chain, not enforced. The current reserve has no outbound transfer path. | https://github.com/urfoundation/sn |
| Reserve governance | The existing reserve has no outbound transfer function. Any different future reserve model would require a separate architecture; it is not a present spending right. | https://github.com/urfoundation/sn |

[View slide 21](https://kdotpham.github.io/khala-privacy-reviewed/#value)

## Slide 22: UR (SN25)’s operator roadmap extends from consumer VPNs into enterprise and AI


With ur.io already live and enterprise and AI programmes still in research, the peer figures illustrate market scale rather than forecast UR (SN25) revenue.
Operators can share the miner fleet, although additional traffic still creates operating costs.
AI agents are routinely blocked by bot controls and data-centre IP detection, and residential routes are what let them reach the open web.
If these programmes become paying operators, their traffic could create UR (SN25) demand once deposits are priced.

| Operator | Market | What it does on UR (SN25) | Market reference and metric |
| --- | --- | --- | --- |
| ur.io | Consumer VPN Live | 350K+ monthly users today (team-reported) | Consumer app adoption, not operator-deposit revenue |
| Project Bastion | Enterprise network access Research | Secure access for companies, their staff and their devices | Zscaler $3.77B ARR, FY2026 |
| Project Meridian | Identity and private access for AI agents Research | Gives agents their own credentials and private routes to company systems | Tailscale $1.5B valuation, 2025 |
| Project Stargate | Open web access for AI agents Research | Residential routes that let agents browse, retrieve and index the open web | Browserbase $300M valuation, 2025 |
| + Third-party operators | White-label VPN, encrypted mail, private search Open to build | Any business can bill users and data on the same network | Bright Data $300M ARR in residential data access |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| ur.io | 350K+ monthly users today (team-reported) |  |
| Project Bastion | Secure access for companies, their staff and their devices |  |
| Project Meridian | Gives agents their own credentials and private routes to company systems |  |
| Project Stargate | Residential routes that let agents browse, retrieve and index the open web |  |
| Third-party operators | Any business can bill users and data on the same network |  |

[View slide 22](https://kdotpham.github.io/khala-privacy-reviewed/#pipeline)

## Slide 23: Operator deposits distinguish the illustrative UR (SN25) scenarios

**End-2027 scenario ranges are illustrative assumptions, not forecasts or outputs from a valuation model.**

The end-2027 market-cap ranges illustrate scenarios on a logarithmic USD scale rather than outputs from a cash-flow or deposit valuation model.
The number to watch Track monthly operator deposits against miner emissions: a first non-zero deposit would show that the mechanism is active, while the scenario ranges would remain assumptions.

| Scenario | What has to happen | $1M $10M $100M $1B 15 Oct 2026 $8.4M | Market-cap multiple |
| --- | --- | --- | --- |
| Bull | Wallets and privacy apps buy capacity, and operator deposits reach a quarter of miner emissions. | $100M to $250M | 12× to 30× |
| Base | Deposits switch on in 2027, and two to four operators pay small amounts. | $15M to $30M | 1.8× to 3.6× |
| Bear | The deposit rate stays at zero, there is still one operator, and TAO flows out of UR (SN25). | $2M to $5M | 0.24× to 0.60× |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Bull: $100M to $250M market cap | Wallets and privacy apps buy capacity, and operator deposits reach a quarter of miner emissions. Signal to watch: monthly deposits as a share of miner emissions. | Khala Research, illustrative |
| Base: $15M to $30M market cap | Deposits switch on in 2027, and two to four operators pay small amounts. Signal to watch: number of operators with non-zero deposits. | Khala Research, illustrative |
| Bear: $2M to $5M market cap | The deposit rate stays at zero, there is still one operator, and TAO flows out of UR (SN25). Signal to watch: net tao flow into sn25, negative three months running. | Khala Research, illustrative |

[View slide 23](https://kdotpham.github.io/khala-privacy-reviewed/#watch)

## Slide 24: Dated events and operating signals will test the privacy thesis


Scheduled milestones test delivery, while deposits and burns show whether adoption reaches the token.

| Timing or trigger | Token | Event | Why it matters |
| --- | --- | --- | --- |
| 13 Nov 2026 | Aztec | Foundation token unlock | Adds supply while user funds secured are still under $100K |
| Late 2026 | Aztec | Version 6 proving-system update | Aztec asked teams to pause new deployments pending guidance |
| 26 Apr 2027 | Coverage universe | Roman Storm retrial on laundering and sanctions counts | Could clarify liability for developers of privacy tools |
| Coming soon | Umbra | Nimbus developer network and SDK | First sign that other apps will route fees to Umbra |
| When priced | UR (SN25) | First operator deposit | Links traffic to token locking; the launch rate is zero |
| Quarterly | Zcash | Shielded share and US ETF holdings | Shows whether demand to hold is turning into private use |
| Ongoing | Venice | Burn volumes and the Venice V2 video rollout | Shows whether revenue growth is reaching VVV holders |
| Q4 targets / ongoing | Nullmask | Wallet distribution, product fees and MASK burns | Tests repeat usage, token value capture and delivered integrations |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Aztec: Foundation token unlock | Adds supply while user funds secured are still under $100K |  |
| Aztec: Version 6 proving-system update | Aztec asked teams to pause new deployments pending guidance |  |
| Coverage universe: Roman Storm retrial on laundering and sanctions counts | Could clarify liability for developers of privacy tools |  |
| Umbra: Nimbus developer network and SDK | First sign that other apps will route fees to Umbra |  |
| UR (SN25): First operator deposit | Links traffic to token locking; the launch rate is zero |  |
| Zcash: Shielded share and US ETF holdings | Shows whether demand to hold is turning into private use |  |
| Venice: Burn volumes and the Venice V2 video rollout | Shows whether revenue growth is reaching VVV holders |  |
| Nullmask: Product fees, MASK burns and delivery | The dashboard reports service fees, developer-wallet ZEC rewards, holder payouts and burns as distinct metrics. Solana and private perpetuals remain roadmap targets. | https://app.nullmask.io/analytics; https://nullmask.io/docs/project-roadmap |

[View slide 24](https://kdotpham.github.io/khala-privacy-reviewed/#catalysts)

