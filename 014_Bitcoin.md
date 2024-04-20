# Bitcoin

## Scalability

One of the most prominent issues with Bitcoin is its scalability. The Bitcoin network has a limited throughput, capable of processing only a relatively small number of transactions per second. As a result, during times of high demand, transaction fees can skyrocket, and confirmation times can become excessively long.

## Energy Consumption

Bitcoin mining, the process by which new bitcoins are created and transactions are verified, requires significant computational power. This has led to concerns about the environmental impact of Bitcoin mining, as it consumes a considerable amount of energy, primarily from fossil fuels, contributing to carbon emissions and environmental degradation.

Image -> An (((interesting infographic))), breaking down the (((energy consumption))) associated with Bitcoin mining, illustrating how it compares to everyday activities like running a home or powering a small city

## Volatility

Bitcoin's price is highly volatile, subject to rapid fluctuations that can make it challenging to use as a stable store of value or medium of exchange. The speculative nature of Bitcoin's price movements can deter merchants and consumers from adopting it for everyday transactions, preferring more stable forms of currency.

## Regulatory Uncertainty

Bitcoin operates in a regulatory gray area in many jurisdictions, with governments struggling to classify it and determine appropriate regulations. This uncertainty can hinder mainstream adoption and investment in Bitcoin, as businesses and individuals may be hesitant to engage with an asset that lacks clear legal status and regulatory oversight.

## Long-term Security Budget Problem

https://dune.com/christianblockslide/bitcoin-security-budget

The block reward lies at the heart of Bitcoin’s cryptoeconomic design. For miners, the block reward represents a return on investment for the capital (hardware, real estate) and operational (electricity, maintenance, and employee wages) expenditures required to mine. It is the monetary stimulus incentivizing them to dedicate computing power to the network, effectively securing it from malicious actors. Anyone wishing to attack the network would have to gain and maintain control over 51% of the network’s total hash power, and the higher the network’s total hash power, the harder or more expensive it is to pull off a 51% attack.

Basic economic reasoning tells us that honest miners are willing to spend up to but no more than what they’d earn from the block reward. For example, if the Bitcoin block reward is $1,000 per block, collectively miners would be willing to spend (CapEx + OpEx) up to ~$999 to maximize their odds of earning this reward. Since the total amount of money miners are willing to spend is capped by their revenue—which comes from the block rewards—this reward is really what sets Bitcoin’s security level. If miners spend a lot of money to mine Bitcoin, then potential attackers would have to spend a lot to attack it.

At the moment, Bitcoin’s security budget (considering operational expenses alone) is around $25.6 million per day, meaning that if attackers were to suppress the Bitcoin network via a never-ending, month-long 51% attack campaign, they would need to spend roughly $768 million in operational costs alone, assuming all things stay equal. Additionally, the cost to acquire enough hardware to pull off this attack would cost billions, and sourcing the hardware is not as straightforward a process as it may seem—if possible at all. Considering that nobody has attempted to attack the network so far, it can be concluded that Bitcoin’s current security budget is more than sufficient.

References: https://www.nervos.org/knowledge-base/bitcoin_and_ckb_security_models

## Fragmentation of Standards

BRC20
Inscriptions
Runes
