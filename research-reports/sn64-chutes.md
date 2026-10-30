# SubnetROI Research — SN64 Chutes

**Deep-dive research report · First Edition · October 2026**

*Data snapshot: live on-chain data via TaoMarketCap, October 2026. Figures change frequently — verify current values before acting. This report is research, not financial advice.*

---

## At a glance

| Metric | Value |
|---|---|
| Subnet | SN64 — Chutes |
| Alpha price | ~0.0673 τ |
| 24h | −0.27% |
| 7d | −1.64% |
| 30d | −4.36% |
| Emission share | 9.14% (#2 of 129) |
| Miner income/day | ~198.6 τ/day |
| Validator stake in subnet | ~1.52M τ |
| Liquidity (TAO side) | ~200k τ |
| Liquidity (Alpha side) | ~2.98M α |
| Validators staked | 49 |
| Market cap rank | #2 |
| Dev activity (tracked) | No commits observed (7d/30d/90d) |
| Dereg risk flag | None |

**Verdict: large, established, liquid — but development appears paused and momentum is drifting.** Chutes is a top-2 subnet by emission with deep liquidity and strong validator backing, which makes it a relatively safe place to stake *today*. But zero tracked commit activity in the last 90 days is a yellow flag: the network rewards active development, and a subnet that stops shipping can lose demand over time.

---

## 1. Position in the network

Chutes is the **second-largest subnet by emission** at **9.14%** of total network emission, behind lium.io (~17%). It captures roughly **198.6 τ/day** of miner income — a substantial allocation that flows to miners, validators, and the subnet owner.

Its **market cap rank is #2** of 129 subnets. This is not a small or speculative subnet; it is one of the largest, most-established positions in the network.

## 2. Alpha price and momentum

The Alpha price is **~0.0673 τ**. The trend is mildly negative across all horizons:

- 24h: −0.27%
- 7d: −1.64%
- 30d: −4.36%

This is not a crash — it is a slow drift downward. The 30-day number is the most meaningful: a ~4% monthly decline in Alpha price means a staker is losing roughly that much in value *on top of* whatever rewards they earn. If rewards net out below ~4% monthly, the position is underwater even while "earning."

**Staking implication:** a stake here has been slowly losing value in TAO terms. Rewards must exceed the Alpha's price decline for the position to be net-positive.

## 3. Liquidity and tradeability

Liquidity is one of Chutes' strengths:

- **~200k τ** on the TAO side
- **~2.98M α** on the Alpha side

For context, this is deep liquidity relative to most subnets. It means:
- Staking and unstaking are unlikely to be blocked by thin markets.
- Large positions can be entered or exited without heavily moving the price.
- The "can't unstake because the fee exceeds the balance" failure mode is much less of a risk here than on a new, illiquid subnet.

**Staking implication:** one of the safer subnets from a liquidity standpoint. You are unlikely to get trapped.

## 4. Stake concentration

**~1.52M τ** of validator stake is allocated into the subnet across **49 validators**. The top validators by stake into SN64:

| Validator | Stake (τ) | Share |
|---|---|---|
| TAO.com | ~263k | 17.3% |
| tao.bot | ~247k | 16.2% |
| Taostats & Corcel | ~235k | 15.5% |
| Arbos | ~192k | 12.6% |
| Yuma (DCG) | ~162k | 10.6% |

The concentration is **high — the top five validators control ~72% of the stake into this subnet**. This is not unhealthy in an absolute sense (all five are credible institutions), but it is a real concentration: a major shift by any one of the top operators (take-rate change, reputation event, or stake migration) can move the subnet's dynamics noticeably.

**Staking implication:** validator choice matters enormously here. Because the top operators hold such large shares, compare their take rates and staker yields carefully before choosing — a small difference in take rate across a large stake is a real difference in yield (see the playbook's take-rate framework).

## 5. Development activity — the yellow flag

**Zero commits observed in the 7-day, 30-day, and 90-day windows** per the data source used. This is the single most important observation in this report.

Two readings are possible:

1. **Development has genuinely paused.** The team has stopped shipping observable changes to the tracked repositories. If true, this is a long-term risk: Bittensor rewards active subnets, and demand (and emission) can shift away from a subnet that stops evolving.

2. **The data source is not tracking the right repos.** Some subnets develop off the primary tracked repositories, or the tracking lags. If true, the flag is a false negative.

**Honest caveat:** I cannot distinguish these two from the data available. What I can say: on the tracked data, Chutes shows no recent development activity, which is unusual for a top-2 subnet and worth monitoring. If this persists next month, downgrade the risk assessment.

## 6. Risks

| Risk | Level | Notes |
|---|---|---|
| Alpha price drift | Medium | −4.4%/mo trend; rewards must outpace it |
| Development pause | Medium (watch) | Zero tracked commits in 90d |
| Liquidity trap | Low | Deep liquidity — unlikely to be stuck |
| Deregistration | Low | No risk flag |
| Validator concentration | High | 49 validators, top-5 ~72% of stake |

## 7. Conclusion

Chutes is a **large, liquid, established subnet** — one of the safest places to stake *today* from a liquidity and position standpoint. The catch is momentum: Alpha has drifted down ~4% over the past month, and the absence of tracked development activity is a yellow flag that demands attention.

**For stakers:** if you stake here, your rewards need to beat the Alpha's decline to be net-positive. Monitor the Alpha trend and the development activity monthly. This is a "hold and watch closely" subnet, not a "stake and forget" one.

**Watch items for next month:**
1. Does the Alpha price trend stabilize or continue down?
2. Does any commit activity appear in the tracked repos?
3. Does emission share hold at ~9% or start to erode?

---

*SubnetROI Research · Included with Pro · subnetroi.com — research is education, not financial advice. Always verify current data and consult a professional before acting.*
