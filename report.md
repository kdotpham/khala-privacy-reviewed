# Privacy: Who Captures the Value?

Authors: 0xSammy; Jack Ai-Leung
Publication date: 2026-11-02
Market-cap snapshot: 2026-10-15
Canonical report: https://kdotpham.github.io/khala-privacy-reviewed/

Slide 15: SAMPLE DATA · NOT FOR POSTING. Its monthly chart contains placeholders. Slide 21 scenarios are illustrative assumptions. Nullmask market values were observed 2026-10-19; other peer market caps retain the 2026-10-15 snapshot.

## Slide 1: Privacy now has paying customers, but few tokens capture that value


Executive summary
1 Companies now need confidentiality to transact on-chain Stablecoins hold $306B on public ledgers, more than ETFs, DeFi and tokenised assets combined, so payroll and supplier payments expose who was paid and how much. Bron’s private payroll and GSR’s private OTC trade show companies paying to hide it. $306B stablecoins on public ledgers 2 Network privacy has not been priced yet Zcash and Monero, which hide payments, are worth about $31B. Nym and UR (SN25), which route traffic so websites and networks cannot see a user’s IP address, are worth $30.6M combined, yet a private wallet still exposes that IP address every time it connects. $30.6M Nym and UR (SN25) combined market cap 3 Most privacy tokens do not yet turn usage into holder value Venice burns VVV with 5% of credit purchases, but Umbra’s fees sit in a DAO treasury with no payout, Nullmask reports token rewards apart from fees, and NOCK and Pearl are priced on privacy plans rather than fees. 5% of Venice credit purchases buys and burns VVV 4 UR (SN25) has users, but its deposits are not yet priced URnetwork reports 350K monthly app users and 126,717 providers (team-reported), while UR (SN25) is valued at $8.4M. Operator deposits launched at a zero rate, and pricing them would make operators lock tokens against expected traffic. 350K monthly app users (team-reported)
Catalysts to watch First operator deposit on UR (SN25) NOCK privacy pool, Q2 2027 Umbra’s Nimbus network launch Storm retrial, 26 April 2027

[View slide 1](https://kdotpham.github.io/khala-privacy-reviewed/#summary)

## Slide 2: Buterin and Durov both place privacy in core infrastructure


The founders of Ethereum and Telegram, a messaging app with over a billion monthly users, reach the same conclusion from different starting points.
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

[View slide 2](https://kdotpham.github.io/khala-privacy-reviewed/#founders)

## Slide 3: US policy has shifted toward privacy, while developer liability remains open


Sanctions were lifted and capital followed, but it is still unsettled whether developers can be prosecuted for how others use their privacy code: Tornado Cash developer Roman Storm was convicted in August 2025 and faces retrial on laundering and sanctions charges in April 2027.

### From enforcement to infrastructure

Chart labels in display order: 2023 · 2024 · 2025 · 2026 · Tornado Cash under sanctions for 31 months · the 19 months since, in detail below · Aug 2022 · US Treasury sanctions Tornado Cash · Nov 2024 · Fifth Circuit rules its immutable contracts are not property · Mar 2025 · US Treasury lifts the sanctions · Apr 2025 · Buterin publishes an L1 privacy · roadmap; Durov pledges no backdoors · Jul 2025 · GENIUS Act sets a federal stablecoin · framework · Oct 2025 · Paxos Labs and Aleo announce USAD; · Ethereum Foundation forms a Privacy · Cluster · Jan 2026 · a16z names privacy crypto's most · important moat · Aug 2026 · Grayscale's Zcash ETF lists, $463M · in two weeks · Policy · Builders and capital

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| 31 months under sanctions | Tornado Cash stayed on the US sanctions list from 8 August 2022 until 21 March 2025. For that period any US person who used it risked breaking sanctions law, which pushed developers and companies away from on-chain privacy tools. | US Treasury; Van Loon v. Treasury |
| US Treasury sanctions Tornado Cash | Tornado Cash is an Ethereum mixer: users deposit into a shared pool and withdraw to a fresh address, breaking the public link between sender and recipient. On 8 August 2022 the US Treasury’s sanctions office (OFAC) blacklisted its smart contracts, saying it had laundered more than $7B since 2019, including $455M stolen by North Korea’s Lazarus Group. | US Treasury OFAC, 8 August 2022 |
| Court rules code is not property | In Van Loon v. Department of the Treasury, decided 26 November 2024, the Fifth Circuit appeals court held that Tornado Cash’s immutable smart contracts are not property that can be sanctioned, because nobody owns or controls them. It was the first appellate ruling to put ownerless privacy code outside sanctions law. | US Court of Appeals for the Fifth Circuit, 26 November 2024 |
| US Treasury lifts the sanctions | The US Treasury removed Tornado Cash from the sanctions list on 21 March 2025, so US users could interact with it again. Developer liability is still open: in August 2025 a jury convicted developer Roman Storm of conspiring to run an unlicensed money-transmitting business and deadlocked on laundering and sanctions charges, which face retrial on 26 April 2027. | US Treasury, 21 March 2025; Cointelegraph |
| Buterin and Durov | On 11 April 2025 Buterin proposed making privacy part of Ethereum’s core design, covering payments, app activity, chain reads and network-level anonymity. On 21 April Durov said Telegram would leave a market rather than build encryption backdoors for authorities. Two founders with very large user bases put privacy at the centre of their products. | Buterin, 11 April 2025; Durov’s Telegram channel, 21 April 2025 |
| GENIUS Act | The Guiding and Establishing National Innovation for US Stablecoins Act, signed on 18 July 2025, is the first US federal law for payment stablecoins, setting rules for reserves, licensing and redemption. It gives banks and payment companies a legal route onto public chains, bringing payroll and supplier flows that companies normally keep confidential. | GENIUS Act, signed 18 July 2025 |
| USAD and the Privacy Cluster | On 1 October 2025 Paxos Labs and Aleo announced USAD, a US dollar stablecoin whose balances and transfers are private by default. On 9 October the Ethereum Foundation formed a Privacy Cluster of 47 researchers, engineers and cryptographers to make privacy a first-class property of Ethereum. | Paxos Labs and Aleo, 1 October 2025; The Block, 9 October 2025 |
| a16z: privacy is crypto’s moat | a16z crypto’s Ali Yahya argued that privacy will be the strongest moat for blockchains: “bridging tokens is easy, bridging secrets is hard”. A chain that holds users’ private state is harder to leave than one that holds only public balances, which favours privacy networks that gain users early. | a16z crypto, January 2026 |
| Grayscale’s Zcash ETF lists | Grayscale’s Zcash ETF (ZCSH) began trading on NYSE Arca on 25 August 2026 and held $463.2M by 7 September, giving investors with ordinary brokerage accounts regulated exposure to a privacy coin. | Grayscale; NYSE Arca, 25 August to 7 September 2026 |

[View slide 3](https://kdotpham.github.io/khala-privacy-reviewed/#policy)

## Slide 4: Business stablecoin payments could pay up to ~$1.1B a year for privacy


Only about 1% of the ~$35T moved by stablecoins each year is genuine payments, but 58% of those payments are business-to-business, the payroll and supplier flows companies most need to hide from competitors.
At 10% adoption, business payments would pay about $110M a year in privacy fees, the revenue pool that fee-based protocols such as Nullmask and Umbra compete for.
Zcash and Monero are priced as private money, not on fees, so their $31B is a separate bet from this payments market.
Stablecoin supply reached $306B in October 2026.
“For users that prioritize privacy, this could become a ‘must-have’ feature.” Zach Pandl, Head of Research, Grayscale, on AI and financial privacy, September 2026

### Stablecoin payments sizing: raw volume, genuine payments, business payments and the implied privacy fee pool, log scale

Chart labels in display order: $10M · $1B · $100B · $10T · Raw stablecoin transfer volume · Everything moved on-chain in a year · ~$35T · Genuine end-user payments · About 1% of raw volume · ~$390B · Business-to-business payments · 58% of payments, up 733% a year · ~$226B · Privacy fee pool, full adoption · Every business payment pays 0.5% · ~$1.1B · Privacy fee pool, 10% adoption · One in ten business payments · ~$110M

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Raw stablecoin volume: about $35T a year | Annualised on-chain stablecoin transfer volume, which is dominated by trading, exchange transfers and automated activity. | Source: McKinsey and Artemis stablecoin payments report, February 2026, using December 2025 data (as reported by KuCoin News, 7 April 2026) |
| Genuine payments: about $390B a year | The share of stablecoin volume that represents real end-user payments after removing trading, bots and exchange rebalancing, roughly 1% of the total. Allium separately reports $482B of payments in January to September 2026, up 45%. | Source: McKinsey and Artemis stablecoin payments report, February 2026, using December 2025 data (as reported by KuCoin News, 7 April 2026); Allium, State of Stablecoins and Payments, Q3 2026 |
| Business payments: about $226B a year | Business-to-business transactions are about 58% of genuine stablecoin payments and grew 733% year on year. These are the payroll, supplier and treasury flows companies normally keep confidential. | Source: McKinsey and Artemis stablecoin payments report, February 2026, using December 2025 data (as reported by KuCoin News, 7 April 2026) |
| Fee pool at full adoption: about $1.1B a year | Khala calculation: $226B of business payments multiplied by a 0.5% privacy fee, the rate Nullmask charges on deposits and withdrawals. An upper bound, not a forecast. | Source: Khala calculation from the McKinsey and Artemis business-payments figure; fee rate from Nullmask’s published fee schedule (nullmask.io/docs/fees) |
| Fee pool at 10% adoption: about $110M a year | Khala calculation: one in ten business payments paying a 0.5% privacy fee. Illustrative. | Source: Khala calculation, illustrative adoption assumption |

[View slide 4](https://kdotpham.github.io/khala-privacy-reviewed/#capital)

## Slide 5: Payroll and trading are the first commercial tests of confidentiality


Payroll and OTC trading have the first live company deployments, while private AI and private connectivity already have the most users.

| Use case | What must stay private | Evidence so far | Who is building or backing it |
| --- | --- | --- | --- |
| Payments and payroll Company-reported deployments | Salaries, supplier invoices and treasury movements | Bron paid salaries in confidential USDT on Ethereum mainnet through Zama, January 2026 | Nullmask Umbra Zama Bron |
| Trading and tokenised assets Company-reported deployments | Orders, positions and holdings | GSR executed a confidential OTC trade on the Zama protocol, March 2026; Dfns added confidential tokens to its wallet platform | Zama Dfns Pantera investor |
| Private computation and AI Venice and NEAR AI live | Customer data and model inputs | Venice reports 3.5M registered users and a $100M revenue run rate (company-reported); NEAR AI Cloud attests each confidential inference request | Venice Pearl NEAR AI Nillion |
| Private connectivity URnetwork live; others building | IP addresses and browsing traffic | URnetwork reports about 350K monthly users and 126,717 IP providers (team-reported); NymVPN runs on the Nym mixnet | UR (SN25) Nym Mysterium |
| Programmable privacy Building | Hidden inputs for sealed-bid auctions, private ballots and strategy games | Reusable tools, so each application does not need its own cryptography | Fhenix Zama Multicoin investor |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Payments and payroll | Bron paid salaries in confidential USDT on Ethereum mainnet through Zama, January 2026 | Zama and Bron, 16 January 2026 |
| Trading and tokenised assets | GSR executed a confidential OTC trade on the Zama protocol, March 2026; Dfns added confidential tokens to its wallet platform | GSR, 12 March 2026 |
| Private computation and AI | Venice reports 3.5M registered users and a $100M annualised revenue run rate (company-reported, August 2026). NEAR AI Cloud runs confidential inference with an attestation per request. Pearl verifies AI computation with zero-knowledge proofs. | Erik Voorhees via Phemex, August 2026; NEAR AI, 3 December 2025; Pearl whitepaper |
| Private connectivity | URnetwork’s VPN reports about 350K monthly users and 126,717 IP providers (team-reported). NymVPN runs on the Nym mixnet. | URnetwork; Nym |
| Programmable privacy | Reusable tools, so each application does not need its own cryptography | a16z; Multicoin |

[View slide 5](https://kdotpham.github.io/khala-privacy-reviewed/#usecases)

## Slide 6: Investors pay for private money, not yet for private infrastructure


Zcash and Monero are worth about $31B as private money, and Venice reaches $1.1B because customer revenue buys back its token.
Grass and Helium, at $486M and $85M, show what networks that sell bandwidth and coverage can be worth once customers pay, which makes them reference points for UR (SN25) without setting its fair value.
Nym and UR (SN25), which hide users’ IP addresses and internet traffic, are worth $30.6M combined, about 0.1% of the value of Zcash and Monero.

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

[View slide 6](https://kdotpham.github.io/khala-privacy-reviewed/#priced)

## Slide 7: Privacy tokens capture value differently


Direct Venice burns VVV with 5% of every credit purchase.
Indirect Umbra’s fees fund a DAO treasury, and NOCK and Pearl pay miners, not holders.
Not yet linked Nullmask pays holders from MASK trading, not product fees, and UR (SN25) deposits launched at a zero rate.
UR (SN25) is the gap to watch: the most users here, 350K a month, behind a deposit link that is built but unpriced.

|  | Venice | Umbra | NOCK | Pearl | Nullmask | UR (SN25) |
| --- | --- | --- | --- | --- | --- | --- |
| What it produces | Private AI chat, images, video and audio, on self-hosted and third-party models. | Private Solana balances, transfers and swaps. | Money on a zero-knowledge chain. Private transfers are planned for 2027. | Private AI compute: ZK proofs verify GPU work without revealing models or data. | Private transfers and swaps. Deposits and withdrawals are public. | Bandwidth and routing, measured by validators. |
| Reported adoption | ~21.9K wallets indexed by VeniceStats | 3.4K encrypted accounts on Solana | 9.5K wrapped NOCK holders on Base | ~320K GPU-equivalents mining; study, June 2026 | Live pools Ethereum and Base | 350K+ monthly app users; team-reported |
| Who pays for it | Subscriptions, API credits or staked DIEM. | Users pay fees and tips. Protocol fees reach the DAO. | Users pay size-based fees, all to miners. | Inference customers pay credits, not PRL. | Users pay 0.5% on deposits and withdrawals. | Customers pay operators. Subnet revenue is separate. |
| Does value reach the token | Stake + burn Part of credit revenue buys and burns VVV. | Governance UMBRA governs the treasury. No buyback or dividend. | Fixed supply Miners take 80% of issuance and all fees; supply is capped at 4.29B. | Mining reward No mechanism links inference revenue to PRL. | Trading rewards Holders earn ZEC from MASK trading fees, not from product fees. | Operator deposits Operators lock tokens against traffic; the launch rate is zero. |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Venice | A full-stack private AI aggregator: chat, image, video, audio and music generation plus an API. Its Private tier runs self-hosted open-source models with zero data retention; its Anonymised tier routes to third-party models such as Claude, OpenAI and Google with identifying metadata removed. | venice.ai, checked 21 October 2026 |
| Umbra | Private balances, transfers and swaps for Solana assets; deposits and withdrawals stay public |  |
| NOCK | Nockchain miners produce zero-knowledge proofs instead of hashes. Its own FAQ says the mining proof does not hide transaction values or chain state, and its roadmap plans a privacy pool app for Q2 2027 and private DeFi foundations for Q3 2027. | https://docs.nockchain.org/start-here/faq; https://www.nockchain.org/roadmap |
| Pearl (PRL) | Pearl miners run the matrix maths used in AI inference, so the same GPU work can serve a customer and compete for PRL block rewards. Its zero-knowledge mining proofs are designed to verify the work without revealing the matrices, which can hold model weights or user data. PRL transfers themselves are not shielded, and private, verifiable inference for customers is being developed with Attestable. | Bankless, 16 October 2026; pearlresearch.ai; BTCC, Pearl guide |
| Nullmask ($MASK) | Private balances and transfers inside shielded pools; swaps conceal the user, but assets and amounts stay public. Nullmask can read account history. | https://nullmask.io/docs/privacy |
| UR (SN25) | Bandwidth and routing marketplace: independent providers carry traffic, validators score performance |  |
| Venice | ~21.9K wallets indexed by VeniceStats |  |
| Umbra | 3,428 encrypted user accounts on Solana |  |
| NOCK | 9,549 addresses hold wrapped NOCK on Base (Basescan, 20 October 2026). Nockchain’s own explorer does not publish a readable address or holder total, so native-chain holders are not included; this is a holder count, not monthly activity. | https://basescan.org/token/0x9b5e262cf9bb04869ab40b19af91d2dc85761722 |
| Pearl (PRL) | A June 2026 study estimated the mining network at the equivalent of 320,000 RTX 3090-class GPUs drawing 112 MW, and found the dominant mining software it examined was not serving customer inference. Pearl publishes no wallet, holder or user count. | Tom’s Hardware, June 2026; Datawallet, 2 October 2026 |
| Nullmask ($MASK) | Official documentation lists ETH and USDT on Ethereum, and ETH and USDC on Base. This cell describes product availability, not a monthly user count. Checked 20 October 2026. | https://nullmask.io/docs/networks |
| UR (SN25) | 350K+ monthly URnetwork app users (team-reported, off-chain) |  |
| Venice | Users pay subscriptions or API credits, or stake $VVV for a daily share of inference |  |
| Umbra | Users pay protocol fees and relayer tips; protocol revenue accrues to the DAO treasury |  |
| NOCK | Fees scale with the encoded size of a transaction and go entirely to the miner. Third-party analysis describes fee revenue as negligible next to issuance. | https://docs.nockchain.org/usdnock-asset/overview; Datawallet |
| Pearl (PRL) | Inference customers pay per token from prepaid credits. A PRL-based compute marketplace is described in the whitepaper, with no launch date announced. | https://platform.pearlresearch.ai/docs; Bankless, 16 October 2026 |
| Nullmask ($MASK) | Deposit and withdrawal fees are 0.5%; swaps have no Nullmask protocol fee, although DEX and network fees still apply. Fees checked 19 October 2026. | https://nullmask.io/docs/fees |
| UR (SN25) | Customers pay operators; URnetwork's UR Pro subscription is operator revenue, not automatically subnet revenue |  |
| Venice | $VVV is staked for inference capacity, and a share of credit purchases buys back and burns it |  |
| Umbra | $UMBRA governs the treasury via MetaDAO markets; no automatic buyback or dividend |  |
| NOCK | NOCK is valued as a capped monetary asset. Miners receive 80% of new issuance and all fees, and a protocol fund receives 20%; no mechanism routes revenue to holders. | https://docs.nockchain.org/usdnock-asset/overview |
| Pearl (PRL) | PRL pays block rewards and transfer fees. No mechanism links inference revenue to the token, so its value rests on demand to hold it. | BTCC, Pearl guide; Bankless, 16 October 2026 |
| Nullmask (MASK) | MASK launched on StonkFun, a Solana launchpad where reward tokens collect fees on trades of the token, convert them into the paired asset and pay holders pro rata. MASK holders, including the Nullmask team wallet, receive ZEC this way. Nullmask’s 0.5% deposit and withdrawal fees go to its protocol contract, and no source links them to the ZEC payouts or MASK burns, so holder income depends on trading in MASK rather than use of the product. | DefiLlama adapter PR 9855 (Nullmask team wallet and StonkFun rewards distributor); Datawallet and Blocmates, StonkFun explainers; app.nullmask.io/analytics |
| UR (SN25) | Operators that sell privacy on the network are designed to deposit UR (SN25) against the traffic they expect, locking tokens while usage grows. The deposit rate was set at zero for launch, and the documentation expects any market purchases for deposits to happen off-chain rather than being enforced, so the link from usage to token demand is designed but not yet active. | UR price.yml and README, checked 20 October 2026 |

[View slide 7](https://kdotpham.github.io/khala-privacy-reviewed/#tokens)

## Slide 8: Zcash prices in future private use


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

[View slide 8](https://kdotpham.github.io/khala-privacy-reviewed/#zcash)

## Slide 9: Nullmask brings private transfers and swaps to existing wallets

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

[View slide 9](https://kdotpham.github.io/khala-privacy-reviewed/#nullmask)

## Slide 10: NOCK is a bet on private money from a zero-knowledge chain, with privacy due in 2027


Nockchain already secures every block with zero-knowledge proofs and plans to use the same proving system to make NOCK transfers and apps private; until the privacy pool ships in 2027, every balance and transfer is public.
What it sells Private, programmable money on a chain built around zero-knowledge proofs. Mining already produces the proofs; the 2027 roadmap applies them to private transfers and apps.
How value reaches the token NOCK is capped money with no premine or sale. Miners take 80% of issuance and all fees, so holders own a monetary asset whose privacy premium depends on the roadmap.
Supply risk About 55% of the cap is mined, much of it in the first ten months. Zorp mined at launch, owing 35% of that capture to seed investors, and the code has no third-party audit.
What has to be true The ZK opcode, privacy pool and private apps must ship on schedule in 2027, and people must then hold and move NOCK privately rather than only mine and trade it.

### Nockchain today, where zero-knowledge proofs secure mining but transfers are public, and the 2027 roadmap that would make NOCK private

Chart labels in display order: Today: zero-knowledge proofs secure the chain · Miners · Produce a zero-knowledge · proof for every block · Block reward · 2,048 NOCK a block; · 80% miner, 20% fund · NOCK holders · Balances and transfers · are fully public · The thesis: the proving system that already secures mining becomes the engine for · private transfers and private apps. Nockchain calls NOCK “soon-to-be private”. · 2027: the same proofs are meant to make NOCK private · ZK verification · Native opcode to · verify proofs, Q1 2027 · Privacy pool · Private NOCK transfers, · planned for Q2 2027 · Private apps · Prove results without · revealing inputs · $45M · market cap, 19 Oct 2026 · 9,549 · wrapped NOCK holders on Base · Q2 2027 · first private NOCK transfers

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Miners | Instead of hashing, each miner runs a fixed Nock program and produces a compact STARK proof. Nockchain says this already makes it the largest proving network in operation, and the same proof format is meant to carry private application proofs later. | Nockchain documentation, checked 20 October 2026; nockchain.org |
| Block reward | Each block pays 2,048 NOCK under the current schedule, falling in steps to a 64 NOCK floor. New issuance is split 80% to the miner and 20% to a protocol fund; fees go entirely to the miner. | Nockchain documentation, tokenomics |
| Not private yet | Nockchain’s FAQ answers whether transfers are private with “Not currently”: the mining proof does not hide transaction values or public chain state. Wrapped NOCK also trades publicly on Base. | https://docs.nockchain.org/start-here/faq |
| The privacy thesis | Nockchain describes NOCK as “programmable gold, soon-to-be private”. The bet is that the proving system already running for mining becomes the engine for private transfers and private apps, so privacy arrives on a chain built for zero-knowledge proofs from day one. | Nockchain README and vision documents |
| ZK verification opcode | A native opcode for verifying zero-knowledge proofs, alongside the completed Nock ZKVM, is planned for Q1 2027 together with forced data availability, which Nockchain calls the foundation for client-side-validation privacy apps. | https://www.nockchain.org/roadmap |
| Privacy pool | Privacy is planned as a pool application following the ShieldedCSV specification, rather than as a base-layer transaction feature. It would be the first time NOCK can move privately. | https://www.nockchain.org/roadmap |
| Private NockApps | The proposed design lets an app prove a state change so nodes verify it without seeing its private inputs, with private DeFi foundations planned for Q3 2027. The current transaction engine does not yet verify these proofs. | Nockchain README; https://www.nockchain.org/roadmap |
| Market cap: $45.0M | Price $0.019; fully diluted value $81.9M; 24-hour volume about $0.7M | CoinGecko, 19 October 2026 |
| Holders: 9,549 | Addresses holding wrapped NOCK on Base; native Nockchain holders are not published in readable form | Basescan, 20 October 2026 |
| Privacy pool: Q2 2027 | Planned date on the Nockchain roadmap; not yet live | https://www.nockchain.org/roadmap |
| What it sells | Private, programmable money on a chain built around zero-knowledge proofs. Mining already produces the proofs; the 2027 roadmap applies them to private transfers and apps. | Nockchain README and roadmap |
| How value reaches the token | NOCK is capped money with no premine or sale. Miners take 80% of issuance and all fees, so holders own a monetary asset whose privacy premium depends on the roadmap. | Nockchain documentation, tokenomics |
| Supply risk | About 55% of the cap is mined, much of it in the first ten months. Zorp mined at launch, owing 35% of that capture to seed investors, and the code has no third-party audit. | Datawallet, citing Zorp disclosures |
| What has to be true | The ZK opcode, privacy pool and private apps must ship on schedule in 2027, and people must then hold and move NOCK privately rather than only mine and trade it. | Nockchain roadmap |

[View slide 10](https://kdotpham.github.io/khala-privacy-reviewed/#nock)

## Slide 11: Umbra’s fees reach a treasury that UMBRA holders govern, with no automatic payout


Umbra hides who paid whom, and how much, on Solana, and each private transaction pays a protocol fee into a treasury that only a governance vote can direct, so UMBRA holders decide how fee income is spent but receive none of it automatically.
What it sells A private wallet for Solana that hides sender, recipient and amount on transfers and the size of swaps. It opened to the public in March 2026 with viewing keys, risk screening and geo-blocking for compliance.
How value reaches the token Fees go to a treasury account that only a timelocked vote can set, and UMBRA holders steer it through MetaDAO markets. There is no automatic buyback or dividend, so value depends on how the DAO spends.
Why the vesting matters Team and adviser tokens unlock only when fully diluted value reaches 2×, 4×, 8×, 16× and 32× the $0.30 sale price, so insider supply arrives only after the price has multiplied.
What has to be true Nimbus, the shielded pool Umbra is building for other apps, has to launch and lift deposits well beyond $187K, because treasury income grows only with the value moving through the pool.

### How a private payment moves through Umbra on Solana, what stays public, and where protocol fees and control go

Chart labels in display order: How a private payment moves through Umbra · Solana wallet · Deposits SOL or · tokens into Umbra · Private balance · Encrypted on Solana · using Arcium · Recipient · Another Umbra user, · or any Solana address · deposit · send · Public · wallet, token, amount · Hidden · balances, senders, amounts · Public on withdrawal · destination and amount · Where fees and control go · Protocol fee · Paid on each private · transaction · DAO treasury · Payout account set · only by a vote · UMBRA holders · Steer the treasury via · MetaDAO markets · fees · govern · $187K · deposits, 15 Oct 2026 · 3,428 · encrypted accounts · $5.2M · market cap, 15 Oct 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Deposit | Moving tokens from a Solana wallet into Umbra is public: anyone can see the wallet, the token and the amount. | Umbra documentation, checked 20 October 2026 |
| Private balance | Inside Umbra, balances are held privately. The public record shows only the program’s total holdings. The wallet runs on Arcium’s encrypted execution network on Solana. | The Block, 27 March 2026; Umbra documentation, checked 20 October 2026 |
| Send or withdraw | A private send hides the sender, recipient, amount and token; a relayer submits it. A withdrawal to any Solana address shows the destination, token and amount, but not which balance paid for it. | Umbra documentation, checked 20 October 2026 |
| What stays private | Deposits are public and linked to the depositing wallet. Transfers inside Umbra hide sender, recipient, amount and token. Withdrawals show destination, token and amount, so withdrawing the exact amount just deposited can still link the two. | Umbra documentation, checked 20 October 2026 |
| Protocol fee | Each private transaction commits a protocol fee in the token used. Governance sets the rate per token, and Umbra’s protocol documentation caps any default at 5%. Relayers can also receive a public tip. | Umbra documentation, fee model and fee collection |
| Treasury | Protocol fees are paid to a treasury payout account that only a timelocked governance proposal can set. Nothing in the documentation buys back UMBRA or pays fees to holders. | Umbra documentation, fee collection |
| UMBRA holders | Umbra launched through MetaDAO, where proposals pass or fail according to markets that trade on their expected effect on the token price. Holders therefore control how the treasury is used, but receive no automatic share of fees. | MetaDAO; CoinDesk |
| Deposits: $187K | Value deposited in Umbra | DefiLlama, 15 October 2026 |
| Encrypted accounts: 3,428 | Existing encrypted user accounts on Solana, a cumulative count rather than monthly users | Solana chain data, 17 October 2026 |
| Market cap: $5.2M | Price $0.37 on 15 October 2026 against a $0.30 MetaDAO sale price in October 2025; range since $0.17 to $2.48; fully diluted value $10.2M | DefiLlama; MetaDAO; The Block, 10 October 2025 |
| What it sells | A private wallet for Solana that hides sender, recipient and amount on transfers and the size of swaps. It opened to the public in March 2026 with viewing keys, risk screening and geo-blocking for compliance. | The Block, 27 March 2026 |
| How value reaches the token | Fees go to a treasury account that only a timelocked vote can set, and UMBRA holders steer it through MetaDAO markets. There is no automatic buyback or dividend, so value depends on how the DAO spends. | Umbra documentation; MetaDAO |
| Why the vesting matters | Team and adviser tokens unlock only when fully diluted value reaches 2×, 4×, 8×, 16× and 32× the $0.30 sale price, so insider supply arrives only after the price has multiplied. | Blockworks token transparency filing, 29 September 2026 |
| What has to be true | Nimbus, the shielded pool Umbra is building for other apps, has to launch and lift deposits well beyond $187K, because treasury income grows only with the value moving through the pool. | Umbra documentation; DefiLlama |

[View slide 11](https://kdotpham.github.io/khala-privacy-reviewed/#umbra)

## Slide 12: Venice turns AI revenue into VVV burns while cutting issuance to 2M a year


Customers pay for private AI through subscriptions, purchased credits or staked DIEM, part of that spending buys and burns VVV, and holders stake VVV to earn emissions and mint DIEM for daily API credit.
What it sells Private AI chat, images and API access to open-source and third-party models. Venice says it does not store prompts or replies, and users pick per model between private, anonymised, TEE and encrypted modes.
How value reaches the token Staked VVV earns emissions and can be locked to mint DIEM, each worth $1 of API use a day when staked. Since 17 July 2026, $5 of every $100 of credits bought has bought and burned VVV, alongside subscription burns.
Evidence of demand 3.5M registered users and a $100M annualised revenue run rate (company-reported, August 2026), after a $65M Series A at a $1B valuation led by Dragonfly.
What has to be true Burns need to outpace the 2M VVV still issued each year. API calls paid with DIEM are not credit purchases, so the burn depends on paid credits and subscriptions continuing to grow.

### How Venice customers pay for private AI, how part of that revenue buys and burns VVV, and how VVV staking mints DIEM for API credit

Chart labels in display order: Customer side · Customers · Pro plans, credit · purchases or DIEM · Venice proxy · Routes each request; · does not log prompts · Model providers · Private, anonymised, · TEE or E2EE modes · Buy and burn · $5 of every $100 of credits bought, plus subscription burns, · buys VVV on the market and burns it · Holder side, on Base · Stake VVV · sVVV earns 2M VVV · a year in emissions · Lock sVVV · Mints DIEM; the rate · rises with supply · Stake DIEM · $1 of API credit · per DIEM, every day · 14M → 2M · new VVV a year, launch to Oct 2026 · $100M · revenue run rate (company) · $1.1B · market cap, mid-Oct 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Customers | Users pay through Pro, Pro+ and Max subscriptions, by buying API credits, or with staked DIEM, which covers $1 of API use per day. API keys spend DIEM first, then credits, then US dollars. | Venice documentation, VVV and DIEM |
| Venice proxy | Requests pass through Venice’s proxy over encrypted connections. Venice says it does not store or log prompt and response content for normal inference, though it keeps billing and account metadata. | Venice documentation, privacy |
| Model providers | Anonymised models hide the user from the provider, who can still read prompts. Private models keep no data after the request. TEE models run in attested hardware enclaves, and E2EE models receive only ciphertext that the enclave decrypts. | Venice documentation, privacy |
| Buy and burn | Since 17 July 2026, $5 of every $100 of credits bought through Venice has funded buying and burning VVV, shown separately from burns funded by Pro, Pro+ and Max subscriptions. DIEM-funded API calls are not credit purchases. | Venice, 17 July and 5 August 2026 |
| Stake VVV | Staking VVV returns sVVV, a receipt that earns emissions. Annual issuance fell to 2.5M VVV on 1 September and to 2M VVV on 1 October 2026. Unstaking has a seven-day cooldown. | Venice documentation; Venice, 17 July and 5 August 2026 |
| Mint DIEM | Locking sVVV at the current mint rate mints DIEM, a tradeable token on Base. The mint rate rises as DIEM supply approaches its target, which increased from 38,000 to 40,000 by 14 September 2026. Burning DIEM unlocks the sVVV. | Venice documentation; Venice, 17 July 2026 |
| Stake DIEM | Each staked DIEM provides $1 of Venice API credit that refreshes daily at 00:00 UTC and does not roll over. | Venice documentation, VVV and DIEM |
| Issuance: 14M to 2M VVV a year | 14M a year at launch in January 2025; 3M before September 2026; 2.5M from 1 September; 2M from 1 October 2026 | Decrypt, 21 September 2026; Venice, 5 August 2026 |
| Revenue: $100M annualised | Company-reported run rate and 3.5M registered users, August 2026 | Erik Voorhees via Phemex, August 2026 |
| Market cap: about $1.1B | Price about $23 | CoinGecko, mid-October 2026 |
| What it sells | Private AI chat, images and API access to open-source and third-party models. Venice says it does not store prompts or replies, and users pick per model between private, anonymised, TEE and encrypted modes. | Venice documentation, privacy |
| How value reaches the token | Staked VVV earns emissions and can be locked to mint DIEM, each worth $1 of API use a day when staked. Since 17 July 2026, $5 of every $100 of credits bought has bought and burned VVV, alongside subscription burns. | Venice documentation; Venice, 17 July and 5 August 2026 |
| Evidence of demand | 3.5M registered users and a $100M annualised revenue run rate (company-reported, August 2026), after a $65M Series A at a $1B valuation led by Dragonfly. | Erik Voorhees via Phemex, August 2026; TechCrunch via AI Weekly, 1 July 2026 |
| What has to be true | Burns need to outpace the 2M VVV still issued each year. API calls paid with DIEM are not credit purchases, so the burn depends on paid credits and subscriptions continuing to grow. | Venice, 17 July and 5 August 2026 |

[View slide 12](https://kdotpham.github.io/khala-privacy-reviewed/#venice)

## Slide 13: Pearl verifies AI work without exposing models or data, but PRL gets no revenue


Each winning piece of GPU work is wrapped in a zero-knowledge proof, so the network verifies AI computation without seeing the model weights or data inside it; customers still pay in credits rather than PRL, and PRL transfers are public.
What it sells Private AI compute: models can run on a decentralised GPU network while zero-knowledge proofs confirm the work without exposing weights or data. It is privacy for AI infrastructure, beside Venice’s privacy for users.
How value reaches the token PRL pays block rewards and fees. Customers pay for inference with prepaid credits and nothing routes that revenue to PRL, so its value rests on demand to hold it.
Supply and mining risk Only 13% of supply is mined and inflation stays near 30% in year three. Two pools reportedly find 75–80% of blocks, and three forks this summer patched mining exploits.
What has to be true Private, verifiable inference must reach paying customers, and paid demand must replace the unrequested work a June study found on most mining rigs.

### How Pearl verifies AI computation with zero-knowledge proofs without revealing models or data, and where the PRL token sits

Chart labels in display order: Private AI compute: verified without being seen · Model owner · Weights and data · stay confidential · GPU miner · Runs the matrix · maths of inference · ZK proof · Proves the work, · reveals no inputs · Pearl chain · Verifies the proof, · pays PRL rewards · Private: the models and data inside the work. Public: PRL transfers. Private prompts and · answers for paying customers, end to end, are still being built with Attestable. · Where PRL sits · Block rewards · About 1M PRL a day, · decaying, no halvings · Customers · Pay prepaid credits, · not PRL · Planned · Private, verifiable inference; · PRL compute market · $500M · market cap, 19 Oct 2026 · ~320K · GPU-equivalents mining · 13% · of the 2.1B cap mined

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Model owner | The matrices used in Pearl’s work can include “proprietary data, model weights, or sensitive user-derived information”, according to its whitepaper. The design aims to keep them confidential while the work is verified publicly. | Pearl whitepaper, pearlresearch.ai/research/int-whitepaper |
| GPU miner | Mining is matrix multiplication, the core of AI inference, so a miner can serve a customer’s request and use the same work as a mining attempt. Only NVIDIA GPUs are supported today. | Bankless, 16 October 2026; BTCC |
| Zero-knowledge proof | Winning work is wrapped in a zkSNARK so “the full protocol can be executed and verified without ever revealing the actual contents” of the input matrices. The proof does reveal matrix shapes, commitments and mining parameters. | Pearl whitepaper, pearlresearch.ai/research/int-whitepaper |
| Pearl chain | A Bitcoin-derived chain launched in April 2026. Each block carries a zero-knowledge certificate of the work and pays a block reward that decays smoothly instead of halving. | BTCC; Bankless, 16 October 2026 |
| What is and is not private | Private: the matrices used in the mining work, which can hold model weights or user data. Public: PRL balances and transfers, plus the proof’s shapes, commitments and parameters. End-to-end private inference for paying customers, including their prompts and answers, is still being built with Attestable. | Pearl whitepaper, pearlresearch.ai/research/int-whitepaper; Bankless, 16 October 2026 |
| Block rewards | Block rewards started near 3,230 PRL and decay smoothly; about half of the 2.1B cap is expected by the end of 2029. Inflation is very high in year one and falls to roughly 30% by year three. | BTCC; Bankless, 16 October 2026 |
| Customers | Inference customers pay per token from prepaid credits, so customer revenue does not reach PRL today. Launch prices were up to about 75% below a major provider’s standard rates. | https://platform.pearlresearch.ai/docs; Bankless, 16 October 2026 |
| Planned | A proof-of-inference layer is being built with Attestable to make customer inference private and verifiable, and the whitepaper describes a PRL-based compute marketplace with no launch date. Neither is live. | Bankless, 16 October 2026 |
| Market cap: $500.3M | Price $1.86; fully diluted value $3.90B; 24-hour volume $1.8M | CoinDesk, 19 October 2026 |
| Mining capacity: about 320K GPU-equivalents | A June 2026 study estimated the network at the equivalent of 320,000 RTX 3090-class GPUs drawing 112 MW, and found the dominant mining software it examined was not serving customer inference | Tom’s Hardware, June 2026 |
| Mined supply: 269M PRL | About 13% of the cap, all issued through block rewards since April 2026, with no presale or insider allocation | CoinDesk, 19 October 2026; BTCC |
| What it sells | Private AI compute: models can run on a decentralised GPU network while zero-knowledge proofs confirm the work without exposing weights or data. It is privacy for AI infrastructure, beside Venice’s privacy for users. | Pearl whitepaper; Bankless, 16 October 2026 |
| How value reaches the token | PRL pays block rewards and fees. Customers pay for inference with prepaid credits and nothing routes that revenue to PRL, so its value rests on demand to hold it. | BTCC; Bankless, 16 October 2026 |
| Supply and mining risk | Only 13% of supply is mined and inflation stays near 30% in year three. Two pools reportedly find 75–80% of blocks, and three forks this summer patched mining exploits. | CoinDesk; Bankless, 16 October 2026 |
| What has to be true | Private, verifiable inference must reach paying customers, and paid demand must replace the unrequested work a June study found on most mining rigs. | Bankless; Tom’s Hardware, June 2026 |

[View slide 13](https://kdotpham.github.io/khala-privacy-reviewed/#pearl)

## Slide 14: Wallet privacy can fail at network connections and cross-chain swaps

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

[View slide 14](https://kdotpham.github.io/khala-privacy-reviewed/#edges)

## Slide 15: UR (SN25) reports 350K monthly users

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

[View slide 15](https://kdotpham.github.io/khala-privacy-reviewed/#mau)

## Slide 16: UR (SN25) uses validator scores to reward routing capacity

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

[View slide 16](https://kdotpham.github.io/khala-privacy-reviewed/#sn25)

## Slide 17: Priced deposits could create demand for UR (SN25)


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

[View slide 17](https://kdotpham.github.io/khala-privacy-reviewed/#operators)

## Slide 18: UR (SN25) would be worth 10× at Helium’s market cap and 58× at Grass’s


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

[View slide 18](https://kdotpham.github.io/khala-privacy-reviewed/#bull)

## Slide 19: Operator deposits could link UR (SN25) demand to usage


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

[View slide 19](https://kdotpham.github.io/khala-privacy-reviewed/#value)

## Slide 20: UR (SN25)’s operator roadmap extends from consumer VPNs into enterprise and AI


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

[View slide 20](https://kdotpham.github.io/khala-privacy-reviewed/#pipeline)

## Slide 21: Operator deposits distinguish the illustrative UR (SN25) scenarios

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

[View slide 21](https://kdotpham.github.io/khala-privacy-reviewed/#watch)

## Slide 22: Dated events and operating signals will test the privacy thesis


Scheduled milestones test delivery, while deposits and burns show whether adoption reaches the token.

| Timing or trigger | Token | Event | Why it matters |
| --- | --- | --- | --- |
| 26 Apr 2027 | Coverage universe | Roman Storm retrial on laundering and sanctions counts | Could clarify liability for developers of privacy tools |
| Q2 2027 | NOCK | Privacy pool app | First private NOCK transfers; the privacy case depends on it |
| Coming soon | Umbra | Nimbus developer network and SDK | First sign that other apps will route fees to Umbra |
| When priced | UR (SN25) | First operator deposit | Links traffic to token locking; the launch rate is zero |
| Quarterly | Zcash | Shielded share and US ETF holdings | Shows whether demand to hold is turning into private use |
| Ongoing | Venice | Burn volumes and the Venice V2 video rollout | Shows whether revenue growth is reaching VVV holders |
| Q4 targets / ongoing | Nullmask | Wallet distribution, product fees and MASK burns | Tests repeat usage, token value capture and delivered integrations |
| Not dated | Pearl | PRL compute market and proof of inference | Would give inference revenue a route to PRL |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Coverage universe: Roman Storm retrial on laundering and sanctions counts | Could clarify liability for developers of privacy tools |  |
| Nockchain: Privacy pool app | Nockchain plans a ShieldedCSV-based privacy pool for Q2 2027, after forced data availability and bridge withdrawals in Q1 2027. It would be the first time NOCK transfers can be private. | https://www.nockchain.org/roadmap |
| Umbra: Nimbus developer network and SDK | First sign that other apps will route fees to Umbra |  |
| UR (SN25): First operator deposit | Links traffic to token locking; the launch rate is zero |  |
| Zcash: Shielded share and US ETF holdings | Shows whether demand to hold is turning into private use |  |
| Venice: Burn volumes and the Venice V2 video rollout | Shows whether revenue growth is reaching VVV holders |  |
| Nullmask: Product fees, MASK burns and delivery | The dashboard reports service fees, developer-wallet ZEC rewards, holder payouts and burns as distinct metrics. Solana and private perpetuals remain roadmap targets. | https://app.nullmask.io/analytics; https://nullmask.io/docs/project-roadmap |
| Pearl: PRL compute market and proof of inference | The whitepaper describes a PRL-based compute marketplace with no launch date, and a proof-of-inference layer is being built with Attestable. Either would give inference demand a route to PRL. | Bankless, 16 October 2026 |

[View slide 22](https://kdotpham.github.io/khala-privacy-reviewed/#catalysts)

