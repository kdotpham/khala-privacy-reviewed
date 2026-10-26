# Privacy: Who Captures the Value?

Authors: 0xSammy; Jack Ai-Leung
Publication date: 2026-11-02
Market-cap snapshot: 2026-10-15
Canonical report: https://kdotpham.github.io/khala-privacy-reviewed/

Slide 15: SAMPLE DATA · NOT FOR POSTING. Its monthly chart contains placeholders. Slide 21 scenarios are illustrative assumptions. Nullmask market values were observed 2026-10-19; other peer market caps retain the 2026-10-15 snapshot.

## Slide 1: Demand for privacy is growing, but most of the value still sits in privacy coins


Executive summary
1 Institutions now want private payments, and Tether and Sui are building them Tether offers USDT on Zama’s confidentiality layer and Sui opened confidential stablecoin transfers with issuer controls in June, while about $390B of stablecoin payments a year still settle in public. $390B stablecoin payments a year on public ledgers 2 Investors still pay far more for private money than for privacy apps Zcash and Monero are worth about $32B, about 14 times the nine other tokens covered here. Venice, the largest app token, trades at about 10 times its estimated revenue. 14× privacy money’s value against other tokens 3 Venice and URnetwork show real demand, and Venice already turns it into buybacks Half of Zcash’s Q3 transactions were private, Venice has 3.5M users and URnetwork reports 350K monthly users of its VPN app. Only Venice links its token to customer revenue, and new supply from Pearl and Venice weighs on holders. 350K monthly URnetwork app users (team-reported) 4 Legal risk and trust in operators could slow adoption Roman Storm’s retrial on Tornado Cash laundering and sanctions charges will test the legal risk of building privacy tools, and many users still trust operators: Nullmask’s servers hold users’ keys. Apr 2027 Storm retrial date
Catalysts to watch Pearl listing on Coinbase First private NOCK transfers, Q2 2027 UR (SN25) operators start locking tokens Venice investor unlock, July 2027
Disclosure: Khala Research may have commercial relationships with projects in this sector, including Sui. Data as of 19 to 26 October 2026.

[View slide 1](https://kdotpham.github.io/khala-privacy-reviewed/#summary)

## Slide 2: Ethereum’s and Telegram’s founders want privacy built into the apps people already use


Buterin wants privacy built into Ethereum itself and Durov would rather pull Telegram’s billion monthly users out of a market than weaken its encryption.
Vitalik Buterin
Co-founder
Ethereum
“Privacy is not about standing apart. It’s about standing together.” Why I support privacy, 14 April 2025
Why privacy matters
Control over information is power, so privacy protects decentralisation, personal freedom and institutions such as the secret ballot.
What he proposes
Build privacy into Ethereum itself, covering payments, app activity, what users look up and their network identity.
What is missing today
Ethereum transactions are still public by default, and most of the plan needs wallets and apps to build it.
Pavel Durov
Founder and CEO
Telegram, over 1B monthly users
“Telegram would rather exit a market than undermine encryption with backdoors and violate basic human rights.” Telegram channel, 21 April 2025
Why privacy matters
Encryption protects everyday communication and personal safety, and any access built for authorities is also available to attackers.
What he proposes
Keep Telegram’s encryption free of government backdoors, even if Telegram has to leave a country to do it.
What is missing today
Telegram’s default chats are not end-to-end encrypted; only its opt-in Secret Chats are.
Implication Privacy that plugs into existing wallets and apps has the clearest path to users, which favours tools like Nullmask and Venice over standalone privacy chains.

[View slide 2](https://kdotpham.github.io/khala-privacy-reviewed/#founders)

## Slide 3: Privacy investment is accelerating as US policy turns supportive


Since Tornado Cash sanctions were lifted, Venice has raised at a $1B valuation and a Zcash ETF has gathered $463M, though whether developers can be prosecuted for how others use their code is unsettled until Roman Storm’s retrial in April 2027.

### From enforcement to infrastructure

Chart labels in display order: 2023 · 2024 · 2025 · 2026 · Tornado Cash under sanctions for 31 months · Aug 2022 · US Treasury sanctions Tornado Cash · Nov 2024 · Fifth Circuit rules its immutable contracts are not property · Mar 2025 · US Treasury lifts the sanctions · Apr 2025 · Buterin publishes an L1 privacy · roadmap; Durov pledges no backdoors · Jul 2025 · GENIUS Act sets a federal stablecoin · framework · Oct 2025 · Paxos Labs and Aleo announce USAD; · Ethereum Foundation forms a Privacy · Cluster · Jan 2026 · a16z names privacy crypto's most · important moat · Sep 2026 · ZEC tops $20B and · its ETF holds $463M · Jul 2026 · Venice raises $65M at a $1B · valuation, led by Dragonfly · Policy · Builders and capital · Jun 2026 · Sui opens confidential · stablecoin transfers in · public beta

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| 31 months under sanctions | Tornado Cash stayed on the US sanctions list from 8 August 2022 until 21 March 2025. For that period any US person who used it risked breaking sanctions law, which pushed developers and companies away from onchain privacy tools. | US Treasury; Van Loon v. Treasury |
| US Treasury sanctions Tornado Cash | Tornado Cash is an Ethereum mixer: users deposit into a shared pool and withdraw to a fresh address, breaking the public link between sender and recipient. On 8 August 2022 the US Treasury’s sanctions office (OFAC) blacklisted its smart contracts, saying it had laundered more than $7B since 2019, including $455M stolen by North Korea’s Lazarus Group. | US Treasury OFAC, 8 August 2022 |
| Court rules code is not property | In Van Loon v. Department of the Treasury, decided 26 November 2024, the Fifth Circuit appeals court held that Tornado Cash’s immutable smart contracts are not property that can be sanctioned, because nobody owns or controls them. It put ownerless privacy code outside sanctions law at the appellate level. | US Court of Appeals for the Fifth Circuit, 26 November 2024 |
| US Treasury lifts the sanctions | The US Treasury removed Tornado Cash from the sanctions list on 21 March 2025, so US users could interact with it again. Developer liability is still open: in August 2025 a jury convicted developer Roman Storm of conspiring to run an unlicensed money-transmitting business and deadlocked on laundering and sanctions charges, which face retrial on 26 April 2027. | US Treasury, 21 March 2025; Cointelegraph |
| Buterin and Durov | On 11 April 2025 Buterin proposed making privacy part of Ethereum’s core design, covering payments, app activity, chain reads and network-level anonymity. On 21 April Durov said Telegram would leave a market rather than build encryption backdoors for authorities. Two founders with very large user bases put privacy at the centre of their products. | Buterin, 11 April 2025; Durov’s Telegram channel, 21 April 2025 |
| GENIUS Act | The Guiding and Establishing National Innovation for US Stablecoins Act, signed on 18 July 2025, is the first US federal law for payment stablecoins, setting rules for reserves, licensing and redemption. It gives banks and payment companies a legal route onto public chains, bringing payroll and supplier flows that companies normally keep confidential. | GENIUS Act, signed 18 July 2025 |
| USAD and the Privacy Cluster | On 1 October 2025 Paxos Labs and Aleo announced USAD, a US dollar stablecoin whose balances and transfers are private by default. On 9 October the Ethereum Foundation formed a Privacy Cluster of 47 researchers, engineers and cryptographers to make privacy a first-class property of Ethereum. | Paxos Labs and Aleo, 1 October 2025; The Block, 9 October 2025 |
| a16z: privacy is crypto’s moat | a16z crypto’s Ali Yahya argued that privacy will be the strongest moat for blockchains: “bridging tokens is easy, bridging secrets is hard”. A chain that holds users’ private state is harder to leave than one that holds only public balances, which favours privacy networks that gain users early. | a16z crypto, January 2026 |
| ZEC passes $20B as its ETF fills | Grayscale’s Zcash ETF (ZCSH) began trading on NYSE Arca on 25 August 2026 and held $463.2M by 7 September, giving investors with ordinary brokerage accounts regulated exposure to a privacy coin. On that same day ZEC reached $1,249, taking its market value to about $20.4B and making it the ninth-largest crypto asset, ahead of Hyperliquid. | Grayscale; NYSE Arca, 25 August to 7 September 2026; Bitcoin.com News and Cointelegraph, 7 September 2026, citing CoinGecko |
| Venice Series A | Venice, the private AI platform behind VVV, raised a $65M Series A at a $1B valuation led by Dragonfly. It reported 3.5M registered users and a $100M annualised revenue run rate in August 2026 (company-reported). | TechCrunch via AI Weekly, 1 July 2026; Erik Voorhees via Phemex, August 2026 |
| Sui confidential transfers enter public beta | On 8 June 2026 the Sui Foundation opened confidential transfers in public beta on Devnet. Balances and amounts are hidden onchain while sender and receiver stay visible; issuers opt their tokens in and set who can access data for compliance. Bridge is exploring it for stablecoin payments, and TRM Labs and Merkle Science for monitoring. Testnet is targeted for later in 2026, with no mainnet date. | Sui Foundation blog, 8 June 2026 |

[View slide 3](https://kdotpham.github.io/khala-privacy-reviewed/#policy)

## Slide 4: Privacy spend is led by VPNs and AI, but payments and trading lead deployments


VPNs ($54B) and confidential computing ($24B) take most privacy spend, but trading and payments lead company deployments.
* Company or team-reported. Privacy infrastructure sells into all four rows: Zama, which builds fully homomorphic encryption, reached a $1B valuation in June 2025 in a round led by Pantera, and Multicoin backs Fhenix.

| Use case | Market size | What must stay private | Evidence so far | Who is building or backing it |
| --- | --- | --- | --- | --- |
| Trading and tokenised assets | $2.7T traded onchain each year | Orders, positions and holdings | ~$4B shielded through Railgun, 2× Oct 2024* $121M shielded on Ethereum in Zama’s token sale $340M traded through Renegade’s dark pool to date | Railgun Zama Renegade Pantera investor |
| Payments and payroll | $390B paid in stablecoins each year, ~$2B in privacy fees | Salaries, supplier invoices and treasury movements | 29% of ZEC supply shielded, up from ~24% a year earlier Sui private stablecoin transfers in public beta $1B+ of payroll through Toku, now on private USAD* | Zcash Monero Nullmask Paxos (USAD) Toku Sui Umbra |
| Private connectivity | $54B spent on VPNs, 2025 | IP addresses and browsing traffic | 3.3M daily Tor users, up 70% in two years About 350K monthly URnetwork users* 126,717 IP providers on URnetwork* | Tor UR (SN25) Nym Mysterium |
| Private computation and AI | $24B spent on confidential computing, 2025 | Customer data and model inputs | 3.5M Venice users, up from 2M in February* $100M Venice run rate, up from $70M in July* 1.34B tokens of confidential AI on Phala in one day* | Venice Phala NEAR AI Pearl |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Trading and tokenised assets | Railgun, the main private trading protocol on Ethereum, has shielded about $4B since 2021, double the $2B it had reached in October 2024 (team-reported), with $1.6B of that in 2025, and the Ethereum Foundation’s Kohaku wallet toolkit integrates it. GSR executed a confidential OTC trade on the Zama protocol in March 2026, and Zama’s own token sale shielded more than $121M on Ethereum. Renegade, an onchain dark pool that hides orders until they match, has handled about $340M of volume across Arbitrum and Base since launch. Market size: about $1.6T of onchain trading and investment and $1.1T of exchange flows in 2025. Tokenised real-world assets, excluding stablecoins, were about $46B in September 2026 and McKinsey’s base case is about $2T by 2030. | DL News, 21 October 2025; RAILGUN, 2024 year in review; GSR, 12 March 2026; The Block, February 2026; BCG and Allium, January 2026; Token Terminal via Crypto Briefing, 1 October 2026; McKinsey, From ripples to waves, June 2024; DefiLlama, Renegade, October 2026 |
| Payments and payroll | About 29% of all ZEC sat in Zcash’s shielded pools on 22 October 2026, by onchain pool balances, against about 24% at the end of September 2025. Nullmask, which adds privacy to existing wallets, reported $50M of private volume in its first three weeks. Tether made USDT available on Zama’s confidentiality layer in September 2026. Sui opened confidential transfers in public beta in June 2026, letting stablecoin issuers hide balances and amounts while setting who can access data for compliance; Bridge is exploring it for payments, and TRM Labs and Merkle Science for monitoring. Bron paid salaries in confidential USDT on Ethereum mainnet through Zama in January 2026. Toku, a token payroll provider that has processed more than $1B of payroll, launched private stablecoin payroll on Paxos Labs’ USAD in January 2026. Market size: $390B of genuine stablecoin payments in 2025, worth about $2B a year at a 0.5% privacy fee (Khala calculation, slide 5). | ZecStats onchain pool balances, 22 October 2026; Blockworks Zcash Q3 2026 and Q4 2025 reports; Pinion Newswire, 19 October 2026; Tether, 15 September 2026; Sui Foundation, 8 June 2026; Zama and Bron, 16 January 2026; McKinsey and Artemis, 2025 data; Aleo, USAD case study, 21 July 2026 |
| Private connectivity | Tor averaged about 3.3M directly connecting users a day from mid-September to mid-October 2026, against about 1.95M in the same weeks of 2024, according to the Tor Project’s own measurements. Late-2025 readings, which spiked above 15M, are excluded as an outlier. URnetwork reports 126,717 IP providers sharing bandwidth, and NymVPN runs on about 750 mixnet nodes. Both offer decentralised alternatives in which no single company sees both who a user is and what they visit. URnetwork reports about 350K monthly users of its VPN. Market size: the global VPN market was about $54.1B in 2025 and is forecast to reach about $156B by 2034, and about 6 billion people were online in 2025. | Tor Metrics, 15 September to 20 October 2026; URnetwork; Nym town hall, 13 March 2026; IMARC Group; ITU, Facts and Figures 2025 |
| Private computation and AI | Venice reported 3.5M users at its July 2026 Series A, up from 2M in February, and a $100M annualised revenue run rate in August, up from about $70M at the raise (company-reported). In June 2026 Apple extended Private Cloud Compute, which processes Apple Intelligence requests without Apple or the host being able to read them, to Google Cloud on NVIDIA Blackwell GPUs with confidential computing. Phala, which runs AI models inside secure hardware enclaves, processed more than 1.34B language-model tokens of confidential inference in a single day in 2025 and had more than 1,000 teams running production workloads. Market size: confidential computing, which keeps data encrypted while it is processed, was about $24B in 2025, and Gartner predicts that by 2029 more than 75% of operations processed on untrusted infrastructure will be secured this way. Gartner forecasts worldwide AI spending of about $2.7T in 2026. | Cointelegraph, 2 July 2026; Crypto Briefing, 17 August 2026; Seczine, February 2026; DatacenterDynamics, 10 June 2026; Fortune Business Insights; Gartner, 20 October 2025 and 16 September 2026; Phala 2025 report |

[View slide 4](https://kdotpham.github.io/khala-privacy-reviewed/#usecases)

## Slide 5: Stablecoin payments could pay about $2B a year for privacy, over half of it from businesses


Of about $62T moved by stablecoins in 2025, 93% was bots and intermediary hops, and within the $4.2T of real activity, trading and exchange flows are seven times larger than payments, but payments are where a 0.5% privacy fee is plausible.
Businesses are the larger prize at about $1.1B a year, but consumer transfers are where stablecoins are already used most, so consumer privacy wallets may find paying users first.
The $2.7T of trading and exchange flows is a second, lower-fee market, where privacy hides positions from copy-traders and front-running bots, and which Umbra’s private swaps already serve.
These fees go to whoever processes private stablecoin flows, so Zcash and Monero holders only benefit if that activity moves onto their chains.

### Where 2025 stablecoin transfer volume goes, from $62T of transfers to $4.2T of economic activity to $390B of payments, and the privacy fee pool by payment segment

Chart labels in display order: All stablecoin transfers in 2025: about $62T · Bots and internal transfers $50T · Hops $7.5T · Economic activity: about $4.2T · Trading and investment $1.6T · Exchange flows $1.1T · Unclassified $0.95T · Payments: about $390B · Payments by segment · Privacy fees at 0.5% · Business to business · $226B · ~$1.1B · Consumer to consumer · $77B · ~$385M · Consumer to business · $76B · ~$380M · Business to consumer · $11B · ~$55M · All payments · $390B · ~$2.0B

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Bots and internal transfers: about $50T | Automated trading bots, MEV, smart-contract plumbing and wallets moving money to themselves. About 81% of all stablecoin transfers, with no buyer paying a seller. | Source: BCG, Stablecoin Payments: The Truth Behind the Numbers, January 2026, using Allium data for 2025 |
| Intermediary hops: about $7.5T | The same dollar passing through routers, bridges and contracts on the way to its destination, counted again at each step. About 12% of transfers. | Source: BCG, Stablecoin Payments: The Truth Behind the Numbers, January 2026, using Allium data for 2025 |
| Economic activity: about $4.2T | What remains after removing bots, internal transfers and intermediary hops, about 7% of all transfers. It covers trading, exchange flows and payments. | Source: BCG, Stablecoin Payments: The Truth Behind the Numbers, January 2026, using Allium data for 2025 |
| Trading and investment: about $1.6T | Stablecoins used to buy and sell crypto onchain, including about $100B of decentralised exchange flow. Traders want privacy to hide positions from copy-traders and front-running bots, but pay fees of hundredths of a percent rather than 0.5%. | Source: BCG, Stablecoin Payments: The Truth Behind the Numbers, January 2026, using Allium data for 2025 |
| Exchange flows: about $1.1T | About $700B settled inside centralised exchanges and $400B of deposits and withdrawals between exchanges and personal wallets. | Source: BCG, Stablecoin Payments: The Truth Behind the Numbers, January 2026, using Allium data for 2025 |
| Unclassified: about $0.95T | Economic transfers BCG could not assign to a category. Some is likely payments, which is why BCG calls its payment figures lower bounds. | Source: BCG, Stablecoin Payments: The Truth Behind the Numbers, January 2026, using Allium data for 2025 |
| Payments: about $390B | Transfers between separate parties paying for goods, services, wages or remittances. McKinsey and Artemis put 2025 at $390B, within BCG’s $350B to $550B range. | Source: McKinsey, Stablecoins find their niche, 26 May 2026, using Artemis Analytics and the McKinsey Global Payments Map, 2025 data; Source: BCG, Stablecoin Payments: The Truth Behind the Numbers, January 2026, using Allium data for 2025 |
| Business to business: $226B in 2025 | 58% of genuine stablecoin payments and up 733% in a year, yet only 0.01% of global business payments. These are the flows companies least want competitors to see. Fee pool is a Khala calculation at a 0.5% privacy fee, the rate Nullmask charges on deposits and withdrawals, and is an upper bound rather than a forecast. | Source: McKinsey, Stablecoins find their niche, 26 May 2026, using Artemis Analytics and the McKinsey Global Payments Map, 2025 data |
| Consumer to consumer: $77B in 2025 | Stablecoins already carry 0.37% of global person-to-person payments, the highest share of any segment and about 37 times their share of business payments. Fee pool is a Khala calculation at a 0.5% privacy fee, the rate Nullmask charges on deposits and withdrawals, and is an upper bound rather than a forecast. | Source: McKinsey, Stablecoins find their niche, 26 May 2026, using Artemis Analytics and the McKinsey Global Payments Map, 2025 data |
| Consumer to business: $76B in 2025 | Stablecoins carry 0.11% of global consumer-to-merchant payments. A public wallet lets any merchant see a shopper’s balance and history. Fee pool is a Khala calculation at a 0.5% privacy fee, the rate Nullmask charges on deposits and withdrawals, and is an upper bound rather than a forecast. | Source: McKinsey, Stablecoins find their niche, 26 May 2026, using Artemis Analytics and the McKinsey Global Payments Map, 2025 data |
| Business to consumer: $11B in 2025 | The smallest segment at 0.01% of global business-to-consumer payments. Fee pool is a Khala calculation at a 0.5% privacy fee, the rate Nullmask charges on deposits and withdrawals, and is an upper bound rather than a forecast. | Source: McKinsey, Stablecoins find their niche, 26 May 2026, using Artemis Analytics and the McKinsey Global Payments Map, 2025 data |
| Privacy fees on all payments: about $2B a year | A 0.5% privacy fee on every genuine stablecoin payment would come to about $2B a year, of which businesses would pay about $1.1B. Trading and exchange flows are excluded because traders pay far lower fees. The fee pool is a Khala calculation at a 0.5% privacy fee, the rate Nullmask charges on deposits and withdrawals, and is an upper bound rather than a forecast. | Source: McKinsey, Stablecoins find their niche, 26 May 2026, using Artemis Analytics and the McKinsey Global Payments Map, 2025 data |

[View slide 5](https://kdotpham.github.io/khala-privacy-reviewed/#capital)

## Slide 6: Privacy as money is worth $32B, about 14 times all other privacy tokens combined


Zcash and Monero, held as private money, are worth about $32B together, while the nine other tokens covered here, from apps to newer chains, total about $2.3B, led by Venice at $1.2B.
Like Bitcoin, Zcash and Monero are valued as money to hold rather than on fees, while the app tokens’ value depends on their products growing and linking that use to the token.

### Market capitalisation of eleven privacy tokens grouped by use case, logarithmic USD scale, CoinGecko 26 October 2026

Chart labels in display order: 1M · 10M · 100M · 1B · 10B · 100B · Log scale · Payments and payroll · Zcash · $20.5B · Monero · $11.1B · NOCK · $44M · Nullmask · $19M · Umbra · $6.2M · Private computation and AI · Venice · $1.2B · Pearl · $624M · Trading and tokenised assets · Zama · $178M · Railgun · $147M · Private connectivity · Nym · $23M · UR (SN25) · $9.7M

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Zcash: ~$20.5B | Private money with optional shielded pools, which hold about 29% of supply. Holders do not receive fees; the value is a bet on ZEC as private money. Fees: about $1.1M a year, annualised from DefiLlama’s 24-hour chain fees on 24 October 2026, all paid to miners. | CoinGecko and CoinMarketCap, 23 October 2026; DefiLlama, 24 October 2026 |
| Monero: ~$11.1B | Private by default for every transfer. Like Zcash, holders do not receive fees. Fees: about $1.6M a year, annualised from DefiLlama’s 24-hour chain fees on 24 October 2026, all paid to miners. | CoinGecko and CoinMarketCap, 23 October 2026; DefiLlama, 24 October 2026 |
| NOCK: ~$44M | Money on a chain mined with zero-knowledge proofs; private transfers are planned for Q2 2027. Miners receive all fees and 80% of new issuance. | CoinGecko, 26 October 2026; Nockchain documentation |
| Nullmask: ~$19M | Private transfers and swaps for existing wallets on Ethereum and Base, launched in October 2026. MASK holders earn ZEC from a fee on MASK trading; the 0.5% product fees are kept by Nullmask. | CoinGecko, 26 October 2026; Nullmask documentation |
| Umbra: ~$6.2M | Private transfers and swaps on Solana, built on Arcium. Protocol fees of about 0.21% go to a treasury that UMBRA holders direct by vote. | CoinGecko, 26 October 2026; Umbra documentation |
| Venice: ~$1.2B | Private AI chat, images, video and audio. Customer revenue, about $100M a year (company-reported), funds VVV buybacks and burns. Revenue: about $123M a year by Tokenomist’s onchain count, and above $150M by the CEO’s claim of 14 October 2026; VVV buybacks and burns ran at about $985K in the last 30 days (DefiLlama), about $12M a year. | CoinGecko and CoinMarketCap, 23 October 2026; DefiLlama, 24 October 2026 |
| Pearl: ~$624M | A layer 1 whose miners do useful AI computation, verified with zero-knowledge proofs. Fully diluted value is about $4.3B because 17% of supply circulates. Fees: not disclosed. About 1M PRL, roughly $1.9M, is issued to miners each day as a subsidy, and Pearl’s inference revenue is not published. | CoinGecko and CoinMarketCap, 23 October 2026; DefiLlama, 24 October 2026 |
| Zama: ~$178M | Encryption layer that keeps balances and transfers confidential on existing chains; fees for confidential operations are paid in ZAMA. Fully diluted value is about $862M because only 23% of supply circulates. Fees: not tracked by DefiLlama. | CoinGecko and CoinMarketCap, 23 October 2026; DefiLlama, 24 October 2026 |
| Railgun: ~$147M | Private trading and transfers on Ethereum, with $1.6B shielded in 2025. A share of shielding fees is paid to RAIL stakers. CoinMarketCap shows $39.5M on 15M circulating tokens; CoinGecko’s 60M supply is used as the more conservative figure. Fees: about $4.2M over the last 12 months (DefiLlama), paid to a treasury that pays RAIL stakers who vote. | CoinGecko and CoinMarketCap, 23 October 2026; DL News, 21 October 2025; DefiLlama, 24 October 2026 |
| Nym: ~$23M | Mixnet that hides who is talking to whom and powers NymVPN. Operators are paid in NYM for routing traffic. Fees: not disclosed. NymVPN does not publish subscription revenue, and node operators are paid mainly from NYM reward pools. | CoinGecko and CoinMarketCap, 23 October 2026; DefiLlama, 24 October 2026 |
| UR (SN25): ~$9.7M | Bittensor subnet 25, the token for URnetwork’s decentralised VPN, which reports about 350K monthly users (team-reported). Fees to the subnet: zero, because operator deposits launched at a zero rate. | CoinGecko and CoinMarketCap, 23 October 2026; DefiLlama, 24 October 2026 |

[View slide 6](https://kdotpham.github.io/khala-privacy-reviewed/#priced)

## Slide 7: Privacy tokens capture value in four ways


Buy and burn · Venice Part of revenue buys back and burns VVV, about $12M a year.
Governance · Umbra Fees build a treasury that token holders direct by vote.
Mining · NOCK, Pearl Fees and new tokens reward miners for their work.
Not yet built · Nullmask, UR (SN25) A link from product use to the token is designed or planned but not live.
These designs can change by upgrade or vote, so the link is worth tracking as each product grows.

|  | Venice | Umbra | NOCK | Pearl | Nullmask | UR (SN25) |
| --- | --- | --- | --- | --- | --- | --- |
| What it produces | Private AI chat, images, video and audio, on self-hosted and third-party models. | Private Solana balances, transfers and swaps. | Money on a zero-knowledge chain. Private transfers are planned for 2027. | Private AI compute: ZK proofs verify GPU work without revealing models or data. | Private transfers and swaps. Deposits and withdrawals are public. | Bandwidth and routing, measured by validators. |
| Adoption | 3.5M users, up from 2M in February | 3.4K encrypted accounts on Solana | 9.5K wrapped NOCK holders on Base | ~320K GPU-equivalents mining; study, June 2026 | ~$3M private volume a day | 350K monthly app users |
| Who pays for it | Subscriptions, API credits or staked DIEM. | Users pay fees and tips. Protocol fees reach the DAO. | Users pay size-based fees, all to miners. | Inference customers pay credits, not PRL. | Users pay 0.5% on deposits and withdrawals. | Customers pay operators. Subnet revenue is separate. |
| How value reaches the token | Buy and burn About a tenth of revenue, roughly $12M a year, buys and burns VVV. | Governance Fees build a DAO treasury. Paying holders needs a vote. | Mining Miners take all fees and 80% of new issuance. | Mining Block rewards go to miners. Inference revenue does not reach PRL. | Not yet built Holders earn ZEC from MASK trading, not product fees. | Not yet built No live route from customer fees to the token. |

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Venice | A full-stack private AI service: chat, image, video, audio and an API. Its Private tier runs self-hosted open models with zero data retention, and its Anonymised tier routes to third-party models with identifying metadata removed. | venice.ai, checked 21 October 2026 |
| Umbra | Private balances, transfers and swaps for Solana assets; deposits and withdrawals stay public. | Umbra documentation |
| NOCK | Nockchain miners produce zero-knowledge proofs instead of hashes. Its own FAQ says the mining proof does not hide transaction values or chain state, and its roadmap plans a privacy pool app for Q2 2027 and private DeFi foundations for Q3 2027. | https://docs.nockchain.org/start-here/faq; https://www.nockchain.org/roadmap |
| Pearl (PRL) | Pearl miners run the matrix maths used in AI inference, so the same GPU work can serve a customer and compete for PRL block rewards. Its zero-knowledge mining proofs are designed to verify the work without revealing the matrices, which can hold model weights or user data. PRL transfers themselves are not shielded, and private, verifiable inference for customers is being developed with Attestable. | Bankless, 16 October 2026; pearlresearch.ai; BTCC, Pearl guide |
| Nullmask ($MASK) | Private balances and transfers inside shielded pools; swaps conceal the user, but assets and amounts stay public. Nullmask can read account history. | https://nullmask.io/docs/privacy |
| UR (SN25) | A marketplace in which independent providers carry VPN traffic and validators score their performance. | URnetwork documentation |
| Venice | Venice reported 3.5M users at its July 2026 Series A, up from 2M in February (company-reported). | Cointelegraph, 2 July 2026; Seczine, February 2026 |
| Umbra | 3,428 encrypted accounts on Solana on 23 October 2026, holding about $250K of deposits. | Solana chain data; DefiLlama, Umbra Privacy V2, 23 October 2026 |
| NOCK | 9,549 addresses hold wrapped NOCK on Base (Basescan, 20 October 2026). Nockchain’s own explorer does not publish a readable address or holder total, so native-chain holders are not included; this is a holder count, not monthly activity. | https://basescan.org/token/0x9b5e262cf9bb04869ab40b19af91d2dc85761722 |
| Pearl (PRL) | A June 2026 study estimated the mining network at the equivalent of 320,000 RTX 3090-class GPUs drawing 112 MW, and found the dominant mining software it examined was not serving customer inference. Pearl publishes no wallet, holder or user count. | Tom’s Hardware, June 2026; Datawallet, 2 October 2026 |
| Nullmask | About $3M of private volume a day in October 2026, and more than $50M since 1 October (company-reported). Nullmask publishes no user or wallet count. | Nullmask press release via The Block, 19 October 2026 |
| UR (SN25) | URnetwork reports about 350K monthly users of its VPN app (team-reported, offchain). | URnetwork, October 2026 |
| Venice | Users pay subscriptions or API credits, or stake for a daily share of inference. | venice.ai |
| Umbra | Users pay protocol fees and relayer tips; protocol revenue accrues to the DAO treasury. | Umbra documentation |
| NOCK | Fees scale with the encoded size of a transaction and go entirely to the miner. Third-party analysis describes fee revenue as negligible next to issuance. | https://docs.nockchain.org/usdnock-asset/overview; Datawallet |
| Pearl (PRL) | Inference customers pay per token from prepaid credits. A PRL-based compute marketplace is described in the whitepaper, with no launch date announced. | https://platform.pearlresearch.ai/docs; Bankless, 16 October 2026 |
| Nullmask ($MASK) | Deposit and withdrawal fees are 0.5%; swaps have no Nullmask protocol fee, although DEX and network fees still apply. Fees checked 19 October 2026. | https://nullmask.io/docs/fees |
| UR (SN25) | Customers pay operators; URnetwork’s Pro subscription is operator revenue, not automatically subnet revenue. | URnetwork documentation |
| Venice | Venice uses part of its revenue to buy back and burn VVV: about $985K in the last 30 days, or about $12M a year, which is about 8% to 12% of revenue. Minting still runs at about four times the burn, so supply keeps growing. | DefiLlama, Venice holders revenue, 22 October 2026; Tokenomist, 20 October 2026 |
| Umbra | Protocol fees and relayer revenue go to a DAO treasury that UMBRA holders govern through MetaDAO markets; there is no automatic buyback or dividend. | Umbra documentation; MetaDAO |
| NOCK | Miners receive 80% of new issuance and all fees, and a protocol fund receives 20%; no mechanism routes revenue to holders. Supply is capped at 4.29B. | docs.nockchain.org, usdnock asset overview |
| Pearl | PRL pays block rewards and transfer fees to miners. No mechanism links inference revenue to the token, so its value rests on demand to hold it. | BTCC, Pearl guide; Bankless, 16 October 2026 |
| Nullmask | MASK launched on StonkFun, where fees on trades of MASK are converted to ZEC and paid to holders pro rata. Nullmask’s 0.5% deposit and withdrawal fees go to its protocol contract, and no source links them to holder payouts. | DefiLlama adapter PR 9855; Datawallet and Blocmates, StonkFun explainers; app.nullmask.io/analytics |
| UR (SN25) | Operators are designed to deposit UR (SN25) against expected traffic, but the deposit rate is zero, so customer fees do not yet create demand for the token. | UR price.yml and README, checked 20 October 2026 |

[View slide 7](https://kdotpham.github.io/khala-privacy-reviewed/#tokens)

## Slide 8: Zcash’s $20.9B price is a bet that Q3’s jump in private use will last


Shielded pools have held about 30% of ZEC for a year, and in Q3 2026 more than half of transactions used them, the highest share in five quarters.
Holding privately is still a minority habit, with about 70% of ZEC in transparent addresses, yet at $20.9B ZEC is worth about 1.8 times Monero, so its price assumes private use keeps growing.
Q3 2026 network fees: ~$204K
Transparent 60% Shielded 28%

### Shielded share of ZEC supply and of transactions, quarter-end, Q3 2025 to Q3 2026

Chart labels in display order: 0% · 20% · 40% · 60% · Q3 2025 · Q4 2025 · Q1 2026 · Q2 2026 · Q3 2026 · ~24% · 39.2% · 30.8% · 18.9% · 31.0% · 21.2% · 26.3% · 27.4% · 29.1% · 52.7% · Transactions using shielded pools · ZEC supply held shielded

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Q3 2026 network fees | Network fees were about $204K in Q3 2026, up about 85% from $110K in Q2. Transparent transfers paid 60.1% of fee value, down from 83.6%, and shielded transfers 27.6%; the report leaves 12.3% unattributed. All fees go to miners. | Blockworks Zcash Q3 2026 report, 16 October 2026, funded by GenZcash |
| Q3 2025 | Shielded share of supply: About 3.81M ZEC at the end of Q3 2025, roughly 24% of supply. Khala estimate from Blockworks’ ZEC count and about 16.1M ZEC in circulation. Shielded share of transactions: 39.2% of non-coinbase transactions. | Blockworks Zcash token holder reports, Q4 2025 to Q3 2026, funded by GenZcash |
| Q4 2025 | Shielded share of supply: 30.8%, about 5.07M ZEC. Shielded share of transactions: 18.9% of non-coinbase transactions, by the Q4 report’s privacy section; its summary gives 16.7%. | Blockworks Zcash token holder reports, Q4 2025 to Q3 2026, funded by GenZcash |
| Q1 2026 | Shielded share of supply: 31.0%, about 5.16M ZEC. Shielded share of transactions: 21.2% of non-coinbase transactions. | Blockworks Zcash token holder reports, Q4 2025 to Q3 2026, funded by GenZcash |
| Q2 2026 | Shielded share of supply: 26.3%, about 4.42M ZEC, after 745K ZEC left shielded pools in June. Shielded share of transactions: 27.4% of non-coinbase transactions. | Blockworks Zcash token holder reports, Q4 2025 to Q3 2026, funded by GenZcash |
| Q3 2026 | Shielded share of supply: 29.1%, about 4.94M ZEC. ZecStats’ independent onchain count was 29.2% on 22 October 2026. Shielded share of transactions: 52.7% of non-coinbase transactions, from 710K transactions in the quarter. | Blockworks Zcash token holder reports, Q4 2025 to Q3 2026, funded by GenZcash; ZecStats, 22 October 2026 |

[View slide 8](https://kdotpham.github.io/khala-privacy-reviewed/#zcash)

## Slide 9: Nullmask adds privacy to existing wallets, with 32K transactions in three weeks

**Nullmask product documentation and reward-accounting disclosures checked 2026-10-20. Deposits and withdrawals are public; the operator can read private balances and history. Market cap/FDV retain the 2026-10-19 observation date. Product fees and token rewards are separate reported metrics, not proof of automatic fee sharing. Solana and private perpetuals remain roadmap targets.**

Users keep MetaMask or Rabby and move funds into shielded pools on Ethereum and Base, hiding transfers from outside observers, although Nullmask’s servers hold the keys that read their balances.
What it does Private transfers and swaps from a shielded balance, with no Nullmask fee on either. Deposits and withdrawals cost 0.5% each and stay public. Ethereum Base
Traction in three weeks About 32K transactions to the pool contract since launch around 2 October, and more than $50M of private volume, company-reported. Only about $220K sits in the pools, so most money passes through rather than stays.
The MASK token MASK has no documented role in the product yet. Holders earn ZEC from a fee on trading MASK itself on StonkFun, about $1.5M so far, and 2.15% of supply has been burned. The 0.5% product fees are kept by Nullmask.
What to watch Whether use holds once launch incentives and points fade, whether the SDK, Solana and private perpetuals ship as planned in Q4 2026, and whether users accept an operator that holds their keys.

### Nullmask product flow: existing wallet, shielded pool, relayed actions and public withdrawal; valuation snapshot 19 October 2026

Chart labels in display order: Deposits and withdrawals remain public · Existing wallet · MetaMask · Rabby · Wallet creates your keys · Shielded pool · 0.5% deposit fee · deposit · Transfer or swap · Relayer submits the action · Swap assets and amounts visible · use · Withdraw · 0.5% withdrawal fee · Destination and amount public · exit · Private from chain watchers · Nullmask’s servers hold the keys that read balances and history. · $19.0M · Market cap · 26 Oct 2026 · $31.3M · FDV · 26 Oct 2026

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Supported wallets | Connecting a wallet and signing a free message creates the account keys, and the same wallet always gives the same keys. MetaMask and Rabby are named as examples, not partners. | Nullmask documentation, getting started, checked 24 October 2026 |
| Shielded pool | Balances and private transfers are hidden from chain observers. Deposits publish the source, asset and amount. | https://nullmask.io/docs/privacy |
| Relayed transfers and swaps | Private transfers conceal the sender, recipient and amount. A swap publishes its assets and amounts, but not who made it. | https://nullmask.io/docs/swap |
| Withdrawal | The recipient, asset, amount, fee and timing are public. Amount and timing can still link pool entry and exit. | https://nullmask.io/docs/privacy |
| Who can see the history? | Nullmask’s servers hold users’ account keys and can read private balances and history. The documentation says the product protects against outside observers, not the operator. | Nullmask documentation, privacy, checked 24 October 2026 |
| MASK market cap: $19.0M | About 590M MASK in circulation at about $0.032. | CoinGecko, 26 October 2026 |
| MASK fully diluted value: $31.3M | About 40% of supply is not yet circulating. | CoinGecko, 26 October 2026 |
| What it does | Private transfers and swaps from a shielded balance. Deposits and withdrawals cost 0.5% each and are public; swaps and private transfers carry no Nullmask fee, only network and exchange fees. MetaMask and Rabby are named as supported wallets, which does not imply a partnership. | Nullmask documentation: fees, privacy, getting started and networks, checked 24 October 2026 |
| Traction in three weeks | 20,287 transactions to the pool contract on Ethereum and 11,994 on Base to 24 October 2026; the count includes relayer and housekeeping transactions, so it is not a user count, and Nullmask publishes none. Nullmask reported more than $50M of private volume since 1 October, about $3M a day. TVL was about $222K on 23 October. | Etherscan and Basescan, pool contract 0xd64E…91c6, 24 October 2026; Nullmask press release via The Block, 19 October 2026; DefiLlama, 23 October 2026 |
| The MASK token | StonkFun is a Solana launchpad whose reward tokens convert trading fees into a chosen asset and pay holders pro rata; Nullmask chose ZEC, and its team wallet also receives ZEC as a holder. The product does not run on Zcash. Nullmask’s documentation has no token page and describes no staking, governance or fee-discount role for MASK; the roadmap says Solana support would bring the product to MASK’s home chain. 2.15% of supply has been burned. Not to be confused with Mask Network, an unrelated project that also trades as MASK. About 590M of roughly 980M MASK circulate, a market cap of about $19.0M and fully diluted value of about $31.3M. | Nullmask press release via The Block, 19 October 2026; DefiLlama adapter PR 9855; Datawallet and Blocmates, StonkFun explainers; CoinGecko, 26 October 2026 |
| What to watch | Points Season One launched on 19 October 2026. The roadmap targets an SDK, Solana integration and private perpetuals for Q4 2026, and BNB Chain and Robinhood Chain support, a cross-chain bridge and direct withdrawals to ZEC wallets for October 2026. Nullmask’s documentation says it protects against outside observers, not the operator. | Nullmask documentation: roadmap and privacy, checked 24 October 2026; Nullmask press release via The Block, 19 October 2026 |

[View slide 9](https://kdotpham.github.io/khala-privacy-reviewed/#nullmask)

## Slide 10: Nockchain mines with zero-knowledge proofs and plans private NOCK transfers for 2027


Miners prove their work with zero-knowledge proofs, and since August can also mine with the maths behind AI, but NOCK balances and transfers stay public until a privacy pool ships, planned for Q2 2027.
What it does Money on a chain whose miners produce zero-knowledge proofs instead of hashes. Since August, miners can also win blocks doing the matrix maths used in AI inference.
Traction No private transfers or paying apps yet. AI mining was set to win 30% of blocks at launch, and its first inference customer is National Compute, a company founded by Nockchain’s founder.
The NOCK token Supply is capped at about 4.29B with no premine or sale, and 55% is mined. Each block pays 2,048 NOCK, 80% to the miner and 20% to a community-run fund, and miners keep all fees.
What to watch Whether the ZK opcode, privacy pool and private apps ship on their 2027 dates, and whether paid AI demand grows beyond the founder’s own company.

### Nockchain today, where zero-knowledge proofs secure mining but transfers are public, and the 2027 roadmap that would make NOCK private

Chart labels in display order: Today: proofs and AI maths secure the chain · Miners · Produce a ZK proof, or · AI maths since August · Block reward · 2,048 NOCK a block; · 80% miner, 20% fund · NOCK holders · Balances and transfers · are fully public · The thesis: the proving system that already secures mining becomes the engine for · private transfers and private apps. Nockchain calls NOCK “soon-to-be private”. · 2027: the same proofs are meant to make NOCK private · ZK verification · Native opcode to · verify proofs, Q1 2027 · Privacy pool · Private NOCK transfers, · planned for Q2 2027 · Private apps · Prove results without · revealing inputs · $44M · market cap, 26 Oct 2026 · 9,549 · wrapped NOCK holders on Base · Q2 2027 · first private NOCK transfers

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Miners | ZK miners produce a compact STARK proof for each candidate block. Since the Logos upgrade in August 2026, AI miners can instead win blocks with Pearl-compatible integer matrix maths, proved with recursive STARK certificates. | Nockchain tokenomics documentation, checked 24 October 2026 |
| Block reward | Each block pays 2,048 NOCK under the current schedule, falling in steps to a 64 NOCK floor. New issuance is split 80% to the miner and 20% to a protocol fund; fees go entirely to the miner. | Nockchain documentation, tokenomics |
| Not private yet | Nockchain’s FAQ answers whether transfers are private with “Not currently”: the mining proof does not hide transaction values or public chain state. Wrapped NOCK also trades publicly on Base. | https://docs.nockchain.org/start-here/faq |
| The privacy thesis | Nockchain describes NOCK as “programmable gold, soon-to-be private”. The bet is that the proving system already running for mining becomes the engine for private transfers and private apps, so privacy arrives on a chain built for zero-knowledge proofs from day one. | Nockchain README and vision documents |
| ZK verification opcode | A native opcode for verifying zero-knowledge proofs, alongside the completed Nock ZKVM, is planned for Q1 2027 together with forced data availability, which Nockchain calls the foundation for client-side-validation privacy apps. | https://www.nockchain.org/roadmap |
| Privacy pool | Privacy is planned as a pool application following the ShieldedCSV specification, rather than as a base-layer transaction feature. It would be the first time NOCK can move privately. | https://www.nockchain.org/roadmap |
| Private NockApps | The proposed design lets an app prove a state change so nodes verify it without seeing its private inputs, with private DeFi foundations planned for Q3 2027. The current transaction engine does not yet verify these proofs. | Nockchain README; https://www.nockchain.org/roadmap |
| Market cap: $44.5M | Price about $0.019; fully diluted value about $80.7M; about 2.37B NOCK circulating. | CoinGecko, 26 October 2026 |
| Holders: 9,549 | Addresses holding wrapped NOCK on Base; native Nockchain holders are not published in readable form | Basescan, 20 October 2026 |
| Privacy pool: Q2 2027 | Planned date on the Nockchain roadmap; not yet live | https://www.nockchain.org/roadmap |
| What it does | Each ZK miner runs a fixed Nock program and produces a compact STARK proof that nodes check without redoing the work. The Logos upgrade at block 126,000 in August 2026 added a second puzzle, AI proof of work, using Pearl-compatible integer matrix maths, with its own difficulty. | Nockchain FAQ and tokenomics documentation, checked 24 October 2026; Blockworks 0xResearch, 13 August 2026 |
| Traction | Blocks were split 30% to the AI puzzle and 70% to ZK mining at activation; no measured split is published. National Compute also wrote the Logos proposal, so the upgrade and its first customer share an author. About 9,549 addresses hold wrapped NOCK on Base; native holder counts are not published in readable form. | Blockworks 0xResearch, 13 August 2026; KuCoin News, 14 August 2026; Basescan, 20 October 2026 |
| The NOCK token | The cap is 2^32 NOCK. Since the Aletheia upgrade in May 2026, each block pays 2,048 NOCK, falling in nine steps to a 64 NOCK floor. Zorp, the company that built Nockchain, mined NOCK and owed seed investors 35% of what it acquired; it wound down in mid-2026 and handed its code and trademark to Nock Community Co., which governs the 20% fund. About 2.37B NOCK circulate, a market cap of about $44.5M and fully diluted value of about $80.7M. | Nockchain FAQ and tokenomics documentation; nockchain.org, NOCK trades; Blockworks 0xResearch, 13 August 2026; CoinGecko, 26 October 2026 |
| What to watch | The roadmap targets a ZK verification opcode and forced data availability for Q1 2027, the privacy pool for Q2 2027 and private DeFi foundations for Q3 2027. Activation dates for Logos moved twice before launch. | nockchain.org roadmap, checked 24 October 2026; Blockworks 0xResearch, 13 August 2026 |

[View slide 10](https://kdotpham.github.io/khala-privacy-reviewed/#nock)

## Slide 11: Umbra brings private transfers and swaps to Solana, built on Arcium


Users deposit Solana tokens into a private balance that hides who paid whom and how much, while protocol fees build a treasury that UMBRA holders direct through MetaDAO votes.
What it does A private wallet for Solana that hides sender, recipient and amount on transfers and the size of swaps. Deposits are free; private transfers and withdrawals cost about 0.21%, a rate governance can change.
Traction About 3.4K encrypted accounts and $250K deposited. Streamflow, a token vesting platform with 1.3M users, now offers private vesting through Umbra, and Range screens transfers for compliance.
The UMBRA token Umbra sold $3M of tokens at $0.30 on MetaDAO against about $155M of demand from 10.5K investors. Fees go to a treasury holders direct by vote, and up to 13.5M new tokens can be issued to the team from 2027 if the price multiplies.
What to watch Whether deposits grow from a small base, whether more apps follow Streamflow in building on Umbra, and how the DAO chooses to use its fee income.

### How a private payment moves through Umbra on Solana, what stays public, and where protocol fees and control go

Chart labels in display order: How a private payment moves through Umbra · Solana wallet · Deposits SOL or · tokens into Umbra · Private balance · Encrypted on Solana · using Arcium · Recipient · Another Umbra user, · or any Solana address · deposit · send · Public · wallet, token, amount · Hidden · balances, senders, amounts · Public on withdrawal · destination and amount · Where fees and control go · Protocol fee · About 0.21% on each · private transaction · DAO treasury · Payout account set · only by a vote · UMBRA holders · Steer the treasury via · MetaDAO markets · fees · govern · $250K · deposits, 23 Oct 2026 · 3,428 · encrypted accounts · $6.2M · market cap, 26 Oct 2026

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
| Deposits: $250K | Value deposited in Umbra, up from about $187K on 15 October. | DefiLlama, 23 October 2026 |
| Encrypted accounts: 3,428 | Existing encrypted user accounts on Solana, a cumulative count rather than monthly users | Solana chain data, 17 October 2026 |
| Market cap: $6.2M | Price about $0.45 against the $0.30 sale price; fully diluted value about $12.2M; about 13.8M UMBRA circulating. | CoinGecko, 26 October 2026; The Block, 10 October 2025 |
| What it does | Opened to the public in March 2026 with viewing keys, risk screening and geo-blocking for compliance. The protocol fee is set as 35 parts in 16,384, about 0.21%, on private transfers, withdrawals and mixer use, with deposits free; a relayer fee exists but is currently zero, and rates sit in configuration accounts that authorised parties can update. Umbra does not publish fee revenue. Computation runs over encrypted data on Arcium, and a relayer submits private sends. Deposits are public, and withdrawals show the destination and amount. | The Block, 27 March 2026; Umbra documentation, checked 20 October 2026; Umbra developer documentation, fee structure, via DeepWiki, checked 24 October 2026 |
| Traction | 3,428 encrypted accounts is a cumulative count, not monthly users. DefiLlama shows about $250K deposited on 23 October 2026. The Streamflow integration launched in May 2026, and each new vesting schedule adds to Umbra’s shared anonymity pool. | Solana chain data, 17 October 2026; DefiLlama, 23 October 2026; The Block, 26 May 2026; Range |
| The UMBRA token | The October 2025 sale was capped at $3M, so buyers received about 2% of their commitments. 55% of supply went to the sale. From 18 months after launch, 13.5M performance tokens can be minted in five tranches at 2×, 4×, 8×, 16× and 32× the sale valuation. Spending, issuance and buybacks need a passing MetaDAO proposal. Market cap about $6.2M and fully diluted value about $12.2M. | The Block, 10 October 2025; Blockworks token transparency filing, as of 15 February 2026; CoinGecko, 26 October 2026 |
| What to watch | Umbra says several high-volume integrations are in discussion but has named none beyond Streamflow. Any buyback or distribution of fees would need a MetaDAO proposal. | The Block, 26 May 2026; Blockworks token transparency filing |

[View slide 11](https://kdotpham.github.io/khala-privacy-reviewed/#umbra)

## Slide 12: Venice is a ChatGPT-style app that keeps no chat history, and funds VVV buybacks


People pay a subscription or buy credits to use many AI models from one account without Venice storing their conversations, and part of every sale buys VVV on the market and burns it.
What it does A ChatGPT-style chat app and API for text, images, video and code. It runs open-source models itself and passes requests to big-name models with the user’s identity removed.
Traction 3.5M users and revenue of over $100M a year, which its CEO now puts above $150M and an onchain count at about $123M. Tokens it serves on OpenRouter nearly doubled from August to October.
The tokens VVV is the main token and carries no claim on revenue or equity; about a tenth of revenue buys and burns it. DIEM is a second token, made by locking VVV, worth $1 of Venice AI a day.
What to watch VVV supply still grows, because new issuance and team tokens vesting until January 2027 outpace burns, and up to 6.5M investor tokens unlock from July 2027.

### How Venice compares with ChatGPT and how its VVV and DIEM tokens work

Chart labels in display order: How Venice differs from ChatGPT · ChatGPT · Venice · Chat history · Saved to your OpenAI account · Kept on your device only · Your prompts · Kept by OpenAI, and can train · its models unless you opt out · Not kept by Venice; outside · model providers may keep theirs · AI models · OpenAI’s own models · Open models Venice runs, plus big · names with your identity removed · How the two tokens work · Customers pay · $18 to $200 a month, · or buy API credits · VVV is bought and burned · $2 of each $18 plan, · 5% of credits bought · About a tenth of revenue · roughly $12M a year, · October pace · VVV · Venice’s main token; no claim · on revenue or equity · Stake it: earn new VVV · stakers share 2M · new VVV a year · Lock it: get DIEM · a second token worth $1 · of Venice AI every day · from sales · stake · lock

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| Chat history | ChatGPT saves conversations to the user’s account on OpenAI’s servers. Venice says conversation history stays on the user’s device and is never stored on its servers; Pro users can add an encrypted backup. | OpenAI data controls FAQ; venice.ai/privacy and pricing, checked 25 October 2026 |
| Your prompts | In Venice’s default Private mode, prompts are not stored, enforced by contract rather than technology. In Anonymised mode the outside provider sees and may keep the prompt but not who sent it. TEE and end-to-end encrypted modes on Pro keep prompts sealed in verified hardware. | venice.ai/privacy, checked 25 October 2026; OpenAI data controls |
| AI models | Venice runs open-source models itself and routes requests to third-party models such as OpenAI’s and Anthropic’s through its proxy with identifying details removed. | venice.ai/privacy, checked 25 October 2026 |
| Customers pay | Subscriptions and API credit purchases are Venice’s revenue: over $100M a year by the company’s August figure, above $150M by its CEO on 14 October, and about $123M by Tokenomist’s onchain count. | Venice, August 2026; Erik Voorhees, 14 October 2026; Tokenomist, 20 October 2026 |
| Buy and burn | Each plan funds a fixed burn ($2 of $18 Pro, $5 of $68 Pro+, $10 of $200 Max) and 5% of API credit purchases buys VVV on the market and burns it, plus occasional larger discretionary burns. In October this came to about a tenth of revenue. | Tokenomist, 20 October 2026; Venice, 17 July 2026 |
| Burn size | About 30,700 VVV burned from 1 to 18 October, worth about $750K, about 10% to 12% of revenue on Tokenomist’s figures. | Tokenomist, 20 October 2026; DefiLlama |
| VVV | VVV is Venice’s main token, on Base and, since 6 October 2026, Solana. It gives no claim on Venice’s revenue or equity. About 48.6M circulate of 81M outstanding. | Tokenomist, 20 October 2026; CoinGecko, 26 October 2026; Pluang, 6 October 2026 |
| Staking | Staked VVV earns a share of new issuance, cut from 14M a year at launch to 2M from 1 October 2026, about 6% a year at current staking. Unstaking takes seven days. | Decrypt, 21 September 2026; Tokenomist, 20 October 2026; Venice documentation |
| DIEM | Locking staked VVV creates DIEM, a separate tradeable token. Each staked DIEM gives $1 of Venice API use that refreshes daily, so a developer holding 100 DIEM gets $100 of AI a day without a monthly bill. | Venice documentation, VVV and DIEM; Venice, 17 July 2026 |
| What it does | Users choose a privacy mode per model: Private, where Venice keeps nothing; Anonymised, where the outside provider sees the prompt but not the user; and TEE or end-to-end encrypted modes on Pro, sealed in verified hardware. Venice says it never stores conversation history on its servers. | venice.ai/privacy, checked 25 October 2026 |
| Traction | 3.5M users reported at the July 2026 Series A ($65M at a $1B valuation, led by Dragonfly). Revenue: $100M run rate in August (company), above $150M (Erik Voorhees, 14 October), about $123M from burn-wallet payments (Tokenomist). OpenRouter tokens served rose from about 40B to 76B a day. | Cointelegraph, 2 July 2026; Venice, August 2026; Tokenomist, 20 October 2026 |
| The tokens | VVV market cap about $1.21B and fully diluted value about $2.03B. A Venice-owned wallet holds about 20.75M VVV, roughly a quarter of supply, and a 4-of-6 multisig controls staking settings. | CoinGecko, 26 October 2026; Tokenomist, 20 October 2026 |
| What to watch | From 1 to 18 October about 98,700 VVV were minted and 30,700 burned, so net supply rose about 3,800 VVV a day; team vesting adds about 10,300 VVV a day until late January 2027. Holding supply flat would take about a third of revenue. | Tokenomist, 20 October 2026 |

[View slide 12](https://kdotpham.github.io/khala-privacy-reviewed/#venice)

## Slide 13: Pearl turns mining into AI computing, with proofs that keep the work’s data hidden


Like Bitcoin, miners compete for block rewards, but their work is the maths AI models run on, and a zero-knowledge proof lets the network check it without seeing the data inside; PRL transfers stay public.
What it does A Bitcoin-style blockchain whose miners run AI maths instead of puzzles, so GPUs can earn PRL while serving AI customers. Nockchain’s AI mining uses Pearl-compatible maths.
Traction About 320K GPU-equivalents mine it. Together AI, a cloud that hosts AI models, mines PRL while serving one and passes the rewards on as a 25% discount. Coinbase added PRL to its listing roadmap.
The PRL token Capped at 2.1B with no premine or sale, and about 17% mined. About 1M PRL a day are still mined, nearly doubling supply within a year, and customers pay in credits, not PRL.
What to watch Whether private inference with Attestable goes live, whether paid AI work replaces synthetic mining, and how concentrated mining stays. The company does not disclose its PRL holdings.

### How Pearl mining works, and who earns what from customers and mining

Chart labels in display order: How mining works: like Bitcoin, but the work is AI maths · AI work · a customer’s request, · or synthetic workloads · GPU miner · runs the maths · on NVIDIA GPUs · ZK proof · checks the work, · hides the data · Block reward · the lucky chunk · wins new PRL · Not live yet: private prompts for paying customers (with Attestable), and paying for AI in PRL. · Who earns what · AI customers · pay for AI in credits, · not PRL · Pearl Research Labs · the company: sells AI access, · runs an official mining pool · PRL holders · no link to customer · revenue yet · Pearl network · creates about 1M · new PRL a day · Miners · GPU owners, mostly in · two large pools · Exchanges · miners sell PRL to · cover their costs · credits · new PRL · sell some · 20% pool fee, in PRL

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| AI work | Bitcoin miners repeat SHA-256 hashing, which has no use beyond securing the chain. Pearl’s work is matrix multiplication, the core of AI inference, so a GPU can answer an AI request and mine at the same time. Today mining also rewards the same maths run on synthetic data, with no customer behind it. | Pearl whitepaper; Bankless, 16 October 2026; CoinMarketCap, October 2026 |
| GPU miner | About 320,000 RTX 3090-class GPU-equivalents were estimated to be mining in June 2026. A testnet upgrade cut the slowdown mining adds to AI work from 10–15% to 0–3%. | Tom’s Hardware, June 2026; KuCoin News, 13 October 2026 |
| ZK proof | A zkSNARK lets the network verify the work without seeing the input matrices, which can hold model weights or user data; the proof still shows shapes and commitments. PRL balances and transfers are public. | Pearl whitepaper |
| Block reward | Like a lottery, each chunk of work has a small chance to win a block. Rewards started near 3,230 PRL a block and decay smoothly instead of halving. | BTCC, Pearl guide; Bankless, 16 October 2026 |
| Not live yet | Private prompts and answers for paying customers are being built with Attestable, and a marketplace where customers pay for AI in PRL has no launch date. | Bankless, 16 October 2026 |
| AI customers | Customers buy prepaid credits on Pearl’s inference platform and pay per token for open models such as DeepSeek and GLM. Launch prices were up to about 75% below a major provider’s standard rates. | pearlresearch.ai platform documentation; Bankless, 16 October 2026 |
| Pearl Research Labs | The company behind Pearl, led by co-founder and CEO Omri Weinstein, a Hebrew University computer scientist. It sells inference through its platform and runs an official pool that takes a 20% fee and accepts only H100 and H200 GPUs. It has not disclosed its headcount, legal structure or PRL holdings, and no venture round has been announced. | Hashrate Index; Datawallet; IQ.wiki |
| PRL holders | No buyback, burn or fee share links customer spending to PRL. Its price rests on demand to hold it. A marketplace where customers pay for AI in PRL is planned with no launch date. | Bankless, 16 October 2026; CoinMarketCap, October 2026 |
| Pearl network | About 1.01M PRL are created each day, about 305M over the next 12 months, nearly doubling supply. Each winning block carries a zero-knowledge proof of the work. | KuCoin News, 13 October 2026; Pearl whitepaper |
| Miners | Independent GPU owners, mostly in the Kryptex and PearlPool pools, earn new PRL and sell some on exchanges to pay for power and hardware. One example of real AI work that also mines: Together AI, a cloud company that runs AI models for developers, mines PRL on the GPUs serving a Gemma model and passes the expected rewards on as a discount of more than 25%. | Bankless, 16 October 2026; Hashrate Index; Datawallet |
| Exchanges | PRL trades mainly on BigONE and SafeTrade, with about $6M to $8M a day of volume; Coinbase added it to its listing roadmap on 20 October 2026. | KuCoin News, 13 October 2026; CoinMarketCap, 20 October 2026; CoinGecko, 26 October 2026 |
| What it does | Pearl forked Bitcoin’s code in April 2026 and swapped hashing for matrix multiplication. Nockchain’s AI proof of work, live since August 2026, runs Pearl-compatible integer matrix maths. | KuCoin News, 13 October 2026; Nockchain tokenomics documentation |
| Traction | The GPU estimate comes from a June 2026 study. Coinbase’s roadmap listing sets no trading date and does not guarantee one. PRL trades on BigONE and SafeTrade, with about $6M to $8M of daily volume. | Tom’s Hardware, June 2026; CoinMarketCap, 20 October 2026; KuCoin News, 13 October 2026; CoinGecko, 26 October 2026 |
| The PRL token | Market cap about $624M and fully diluted value about $3.7B. About 122M PRL, 36% of supply at the time, were issued in the first six days. Inflation is very high in year one and falls to roughly 30% by year three. | CoinGecko, 26 October 2026; KuCoin News, 13 October 2026; Bankless, 16 October 2026 |
| What to watch | Kryptex and PearlPool reportedly control a majority of hashrate; Bankless put the two pools at 75-80% of blocks. Three hard forks this summer patched mining exploits and restricted which hardware can mine. | Bankless, 16 October 2026; TechFlow, 19 October 2026 |

[View slide 13](https://kdotpham.github.io/khala-privacy-reviewed/#pearl)

## Slide 14: Wallet privacy can fail at network connections and cross-chain swaps

**Primary paper checked on 2026-10-18: address-to-IP linking under controlled router observations; Ethereum mainnet and testnet are separate. Not a population-wide exposure estimate; UR (SN25) was not tested.**

In a 2025 controlled experiment, researchers linked wallet addresses to IPs with 95-98% success after 3-4 observations, a result specific to the study’s setup.
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
| Ethereum mainnet: 95.33% | MetaMask · 3 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8-10; https://arxiv.org/html/2508.21440v1 |
| Ethereum testnet: 96.80% | MetaMask · 3 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8-10; https://arxiv.org/html/2508.21440v1 |
| Bitcoin testnet: 97.70% | Electrum · 4 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8-10; https://arxiv.org/html/2508.21440v1 |
| Solana testnet: 96.58% | Torus · 4 observations. Success linking a wallet pseudonym/address to an IP under the paper’s observer setup; not named-person identification or population-wide exposure. Researcher-controlled endpoints and emulated routers. | Wang et al., Time Tells All, arXiv:2508.21440v1, §§8-10; https://arxiv.org/html/2508.21440v1 |

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
| Apr 1 | 120K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |
| May 1 | 150K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |
| Jun 1 | 185K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |
| Jul 1 | 220K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |
| Aug 1 | 265K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |
| Sep 1 | 300K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |
| Oct 1 | 330K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |
| Oct 15 | 350K monthly active users | SAMPLE DATA: NOT FOR POSTING. Placeholder monthly series. |

[View slide 15](https://kdotpham.github.io/khala-privacy-reviewed/#mau)

## Slide 16: UR (SN25) uses validator scores to reward routing capacity

**Design is distinct from launch: the documented launch has a UR-run operator and sole validator. The 200-fleet figure is a design cap.**

Launch documentation describes one UR-run operator and validator, with provider allocation starting at 10% of the native miner share.
126,717 Providers on URnetwork (team-reported)
103 Countries covered (team-reported)
Up to 200 Top-level fleet capacity in the design; not a live count
$7.4M UR (SN25) market cap, 23 October 2026

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

## Slide 18: UR (SN25) would be worth 11× at Helium’s market cap and 21× to 61× at Grass’s


The 23 October 2026 comparison places UR (SN25) at $7.4M, Helium at $82M and Grass at $157M to $452M, depending on the circulating supply used, on a logarithmic USD scale, illustrating relative size rather than a modelled valuation.
A wide valuation gap Transaction-privacy assets are valued at about $32B, against $32M for Nym and UR (SN25), a gap of around 1,000 times.
A product already in market URnetwork, the VPN that UR (SN25) supplies, reports about 350K monthly users and 126,717 providers across 103 countries, so the thesis does not depend on a product launch.
Demand linked to usage If a non-zero rate is adopted, usage-based deposits would lock tokens, although growing traffic would not guarantee new market buying because revenue-funded purchases are not enforced.
What UR (SN25) would be worth at its peers’ market caps

### UR (SN25) market cap against peers

Chart labels in display order: $1M · $10M · $100M · $1B · UR (SN25) · $7.4M · Nym · $24.7M · 3.3x · Helium · $82M · 11x · Grass · $452M · 61x

### Chart details and interactive notes

| Metric or element | Detail | Source supplied with the slide |
| --- | --- | --- |
| A wide valuation gap | Transaction-privacy assets are valued at about $32B, against $32M for Nym and UR (SN25), a gap of around 1,000 times. |  |
| A product already in market | URnetwork, the VPN that UR (SN25) supplies, reports about 350K monthly users and 126,717 providers across 103 countries, so the thesis does not depend on a product launch. |  |
| Demand linked to usage | If a non-zero rate is adopted, usage-based deposits would lock tokens, although growing traffic would not guarantee new market buying because revenue-funded purchases are not enforced. | https://github.com/urfoundation/sn |
| UR (SN25) today: ~$7.4M | UR (SN25) market cap, 23 October 2026. | CoinGecko and CoinMarketCap, 23 October 2026 |
| Nym: ~$24.7M | Mixnet with its own VPN; rewards moving to gateways that serve users. | CoinGecko and CoinMarketCap, 23 October 2026 |
| Helium: ~$82M | Carriers and subscribers pay for coverage; about $50K a day of data credits burned. | CoinGecko and CoinMarketCap, 23 October 2026 |
| Grass: ~$452M | Sells residential bandwidth to AI firms; about $17M of 2025 revenue (team-reported). CoinMarketCap shows $157M on 244M circulating tokens; CoinGecko’s 699M supply is used as the more conservative figure, which would put UR (SN25) at 21× rather than 61×. | CoinGecko and CoinMarketCap, 23 October 2026 |

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
| Operator deposits | Priced deposits lock tokens against traffic; purchases from revenue are expected offchain, not enforced. The current reserve has no outbound transfer path. | https://github.com/urfoundation/sn |
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

| Scenario | What has to happen | $1M $10M $100M $1B 23 Oct 2026 $7.4M | Market-cap multiple |
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

