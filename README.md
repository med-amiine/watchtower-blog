
# Watchtower: The Credit Intelligence Layer We Built For Ourselves by bond.credit

## Opening Hook

Autonomous agents are deploying capital today. But when an agent asks for a credit line, what do you actually check? Yield? That's not enough.

A single yield number can mask three separate problems at once. We learned this the hard way—and built something to fix it.

---

## The Problem We Had

We're building **bond.credit** — a decentralized lending protocol for autonomous DeFi agents. Before we could allocate real capital to them, we needed something critical: a way to underwrite them.

But here's the gap: no scoring system existed that was designed **for agents** (as opposed to humans, or protocols). Everything in crypto defaults to social signals, speculation, or vibes.

We needed something different:
- **Algorithmic** — not based on reputation or hype
- **Onchain** — observable, verifiable, real
- **Behavioral** — based on how agents actually execute, not what they promise

No tool like this existed. So we built one.

---

## So We Built Watchtower — For Ourselves

**Watchtower** is the credit intelligence layer we needed to do our job. It continuously monitors autonomous DeFi agents across five behavioral dimensions and assigns a **Bond Score** that directly determines credit capacity.

We didn't publish a whitepaper first. **We ran the experiment.**

### Genesis Cohort: 107 Days of Real Capital

| Metric | Value |
|--------|-------|
| Duration | Nov 5, 2024 – Feb 19, 2025 |
| Agents | 5 (Arma, Sail.Money, ZyFAI, SurfLiquid, Mamo) |
| Capital Deployed | $10,000 |
| Total Volume Cycled | $761,806 |
| Total Yield Generated | $295.75 |
| Transactions | 570 |
| Blended APY | 10.45% |
| Native APY (Reward-Stripped) | 6.49% |

---

## Why These Five Metrics

The methodology answers a simple question: **What do you actually check before giving an agent a credit line?**

A single yield number isn't enough. It masks three problems at once. So we broke it down into five dimensions:

### The Five-Factor Model

| Dimension | Weight | What It Catches |
|-----------|--------|-----------------|
| **Performance** | 30% | Yield efficiency — but stripped of emissions (TYR, native APY) |
| **Risk** | 25% | Leverage, drawdown, liquidation exposure, Sharpe ratio |
| **Stability** | 20% | Behavioral consistency — cadence, protocol diversity |
| **Sentiment** | 15% | Human trust — audits, dev reputation, operator track record |
| **Provenance** | 10% | Verifiable execution — TEE attestation, ERC-8004 compliance |

### Why This Matters: SurfLiquid vs. ZyFAI

Look at two agents from Genesis:

**SurfLiquid:**
- Headline APY: **16.49%** (highest in cohort)
- But 62.9% came from **token emissions**, not trading
- Leverage: **3.1×**
- Liquidation proximity: **High**
- **Bond Score: 72 (C)**
- **Credit cap: $500K**

**ZyFAI:**
- APY: **10.17%** (lower headline)
- 100% **native yield**, zero emissions
- Sharpe ratio: **1.88**
- **Bond Score: 85 (A)**
- **Credit cap: $3M**

Same $2K starting capital. Radically different credit decisions.

The difference? **One is sustainable. One is living off token inflation.**

---

## What We Found: Genesis Results

After 107 days of live capital, here's what the data showed:

### The Numbers
- **5 agents**, $10K deployed
- **$295.75 total yield** across the portfolio
- **10.45% blended APY** (with all revenue streams)
- **6.49% native APY** — the floor we actually underwrite to
- **$761K volume** cycled through agent strategies
- **570 transactions** executed onchain
- **Bond Scores:** ranging 68–91 across the cohort

### The Key Learning

**Reward emissions inflate APY but don't reflect sustainable yield.** 

When we strip out token incentives, reward dependency, and temporary conditions, the real picture emerges. SurfLiquid's native APY was 5.91% (not 16.49%). ZyFAI's stayed at 10.17% (already clean). That difference is credit capacity.

### Bond Score Distribution

| Agent | Bond Score | Grade | Native APY | Credit Cap |
|-------|-----------|-------|-----------|-----------|
| Sail.Money | 91 | A+ | 6.39% | $1.8M |
| ZyFAI | 85 | A | 10.17% | $3.0M |
| Giza | 82 | A | 5.27% | $2.2M |
| SurfLiquid | 72 | B+ | 5.91% | $500K |
| Mamo | 67 | B | 4.77% | $300K |

---

## Why We're Sharing This

The agentic DeFi space is early. **Standards don't exist yet.** Everyone is figuring out how to think about agent risk for the first time.

We built Watchtower for ourselves because we had to. Now we're publishing it because the ecosystem needs it:

1. **The data is public** — Full Genesis dataset, live Bond Scores, credit reports for each agent
2. **The methodology is open** — Five-factor model, weighting, threshold formulas
3. **The standard is ERC-8004** — Verifiable agent identity that carries credit history across chains
4. **The invitation is real** — If you're building agents, you can see exactly how we'd score you

### What We Want From You

If you're an **agent builder:**
- See exactly how Watchtower scores you
- Understand what to optimize (reward dependency, drawdown, Sharpe)
- Get real credit capacity estimates
- Build with verifiable execution

If you're an **allocator or LP:**
- Use this framework to evaluate agents you're considering
- Stress-test the methodology (is it missing something?)
- Propose improvements to the model

If you're a **protocol or infrastructure team:**
- Help us build ERC-8004 as the standard for agent identity
- Integrate Watchtower scoring into your products
- Propose alternative scoring dimensions

---

## What's Next: Season 1

We're not stopping at Genesis. Here's what's coming:

### Three Strategic Priorities for Season 1

1. **Reduce Reward Dependency**
   - Sustainable yield should not be tied to token inflation
   - Target: 80%+ of native APY from trading, not incentives

2. **Scale Portfolio**
   - 17 new agents targeting Q2 2026
   - Expand across strategies (staking, market-making, yield farming)
   - Build redundancy and portfolio effects

3. **Reduce Concentration Risk**
   - Current portfolio: 
   - Expand to multi-chain execution
   - Better protocol diversity metrics

### Timeline

- **Q1 2026:** ERC-8004 registry live, TEE attestation expanding
- **Q2 2026:** 17 new agents onboarded
- **Ongoing:** Watchtower data updated weekly, Bond Scores live

---

## The Invitation

**Watchtower is live at bond.credit/watchtower**

The data is public. The methodology is open. The code is transparent. Come stress-test it.

We built this because we needed it. We're sharing it because the ecosystem needs it.

If you're building agents, allocating to them, or thinking about how credit works in DeFi — start here.

---

## Quick Links

- **Dashboard:** bond.credit/watchtower (live Bond Scores, agent profiles)
- **Genesis Data:** Full portfolio breakdown, agent performance, credit reports
- **Methodology:** Five-factor scoring model, threshold documentation
- **ERC-8004:** Agent identity standard proposal (in review)
- **GitHub:** Watchtower scoring code and formula reference

---

## FAQs

**Q: Can I integrate Watchtower scoring into my protocol?**
A: Yes. The methodology is open-source. You can implement Bond Scores directly or contact us.

**Q: Will Watchtower score agents outside of bond.credit?**
A: Eventually, yes — but we're starting with agents we've directly observed and tested. This ensures we're not scoring on incomplete data.

**Q: Is this a credit rating agency?**
A: No. We're a methodology, not a monopoly. We're publishing this so the ecosystem can build using our score and test our assumptions.

---

## Closing

We didn't think a credit layer for autonomous agents should exist based on vibes. We needed one to do our job. So we built it, tested it with real capital for 107 days, and now we're handing it to the ecosystem.

The future of agent finance is onchain, algorithmic, and verifiable. Watchtower is the first tool designed to make that real.

Come build with us.

---

*All data verified from Genesis cohort (Nov 2024 – Feb 2025). Full transparency: all Bond Scores, agent details, and transaction history available onchain.*
