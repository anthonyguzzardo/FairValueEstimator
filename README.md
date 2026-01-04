# FairValueEstimator

FairValueEstimator is a deterministic evaluation system for assessing the quality of market propositions by estimating fair value relative to a quoted price.

It is designed to work across probabilistic markets, including:
- Sports betting
- Equities
- Crypto assets
- Any market where a price implies an underlying probability

The system does not predict outcomes.
It evaluates whether a price is justified given current information.

---

## Problem Statement

Markets compress complex assumptions into a single number:
- Odds
- Price
- Line
- Spread

That number embeds:
- Implied probabilities
- Risk assumptions
- Information freshness
- Market consensus and bias

FairValueEstimator decomposes a market proposition and estimates whether the quoted price aligns with a defensible notion of fair value.

---

## Core Idea

Every market proposition implies a probability.

FairValueEstimator:
1. Extracts the implied probability from the quoted price
2. Reconstructs the assumptions required for that price to be fair
3. Re-estimates probability using current, relevant data
4. Compares implied value vs estimated fair value
5. Produces a structured quality assessment

The output is evaluative, not prescriptive.

---

## High-Level Flow