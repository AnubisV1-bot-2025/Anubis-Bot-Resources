# 🔱 Anubis Bot Trading Guide - TLDR Version
## Quick Reference for Maximum Profit

---

## ⚠️ LEGAL DISCLAIMER - READ CAREFULLY

**NOT FINANCIAL ADVICE:** This guide is provided for educational and informational purposes only. Nothing contained herein constitutes financial advice, investment advice, trading advice, or any other type of advice. You should not treat any of the content as such.

**NO GUARANTEES:** Past performance is not indicative of future results. The performance statistics presented are historical data and do not guarantee future profitability. Cryptocurrency trading, especially memecoin trading, involves substantial risk of loss.

**ASSUMPTION OF RISK:** By using this information, you acknowledge and agree that:
- You are solely responsible for your own trading decisions
- Cryptocurrency trading can result in complete loss of capital
- Memecoins are extremely high-risk and speculative assets
- 98% of memecoins fail regardless of any alert system
- You may lose all money invested in any trade

**NO LIABILITY:** The creators, operators, and distributors of this guide and the Anubis Bot system assume no liability whatsoever for any losses, damages, or negative outcomes resulting from your use of this information. You trade entirely at your own risk.

**REGULATORY COMPLIANCE:** Ensure cryptocurrency trading is legal in your jurisdiction. This guide does not constitute an offer to sell or solicitation to buy any securities or financial instruments.

**BY CONTINUING TO READ, YOU ACKNOWLEDGE YOU HAVE READ AND UNDERSTOOD THIS DISCLAIMER.**

---

**Last Updated:** November 4, 2025  
**Current System Performance (Conservative):**
- 40% hit 2X | 20% hit 3X | 2.61x average multiplier
- ~5 alerts per day

---

## 📊 Performance Reality Check

**What the numbers mean:**
- Winners (40%) average ~5x at peak
- Losers (60%) average ~1x
- Overall average: 2.61x across ALL trades
- Volume varies with market conditions

**The baseline:** 98% of ALL memecoins rug. Our system finds the tradeable 2%.

---

## 💰 Trading Strategies

### Strategy 1: "Set It and Forget It" (No Stop Loss) ✅ RECOMMENDED

**Process:** Buy → Hold → Exit when rugged  
**Expected:** +$13/trade @ $25 position | +$88/trade @ $100 position  
**Pros:** Positive EV, captures moonshots, zero stress  
**Cons:** 10% rug immediately after 2X, requires diamond hands  
**Best For:** Busy traders, maximum EV

---

### Strategy 2: "Safe Exit at 2X" ❌ NOT RECOMMENDED

**Process:** Buy → Auto-sell at 2.0x  
**Expected:** -$17/trade (NEGATIVE EV)  
**Why it fails:** Fees eat small gains, miss all 3X+ runs  
**Result:** Only 10% of trades show profit

---

### Strategy 3: "Smart Trailing" (2.2X Stop Loss) ✅ RECOMMENDED

**Process:** Buy → After 2X, set SL at 2.2X → 75% continue to 5x  
**Expected:** +$6/trade @ $25 position | +$60/trade @ $100 position  
**Pros:** Protects from rug backs, still catches moonshots  
**Cons:** Requires monitoring, slightly lower EV than no-SL  
**Best For:** Active traders wanting protection

---

### Strategy 4: "Moon or Bust" (3X Target) ❌ NOT RECOMMENDED

**Process:** Hold for 3X or bust  
**Expected:** -$6/trade (NEGATIVE EV)  
**Why it fails:** Only 20% hit 3X, watching 2X+ rug is brutal

---

## 🎯 Position Sizing

**Fee Impact (Critical):**
- Trading fees: ~$10 per round trip
- $25 position = 40% fees (need 1.4X to break even)
- $50 position = 20% fees (need 1.2X to break even)
- $100 position = 10% fees (need 1.1X to break even)

**Recommended Sizes:**
- **Small ($500-1k):** $25-50/trade | Returns: +$65-$130/week
- **Medium ($2k-5k):** $50-100/trade | Returns: +$220-$440/week
- **Large ($10k+):** $100-250/trade | Returns: +$440-$1,100/week

**Golden Rule:** Larger positions = dramatically better returns due to fixed fees.

---

## 📱 Execution Steps

1. **Alert arrives** → Decide within 60 seconds
2. **Execute** → Use contract address, 5-10% slippage
3. **Set exit** → Based on chosen strategy
4. **Monitor** → If using active strategy
5. **Exit** → When criteria met, no emotion
6. **Track** → Record all data for learning

**Common mistakes to avoid:**
- Hesitating too long (entry moves)
- FOMOing after pump
- Changing strategy mid-trade
- Revenge trading after losses

---

## 🧠 Psychology Essentials

**Accept reality:**
- 60% of calls lose money
- Losing streaks happen
- Focus on long-term edge
- Emotions lie, data doesn't

**When to stop:**
- Revenge trading
- Ignoring your rules
- Trading rent money
- Constant anxiety

---

## 📈 Track Everything

**Essential data per trade:**
- Entry/exit price, position size, fees paid
- Profit/loss in USD
- Multiplier achieved
- Exit reason

**Calculate performance:**
- Win Rate = Wins / Total Trades
- Expected Value = (Win Rate × Avg Win) + (Loss Rate × Avg Loss)

---

## 🎓 Advanced Tips

**Market awareness:**
- **Bull:** More calls (8-10/day), higher success, hold for 3X
- **Bear:** Fewer calls (2-3/day), faster rugs, lock at 2X
- **Sideways:** Stick to plan (5/day average)

**Volume signals:**
- Good: Steady increase, more buyers, organic growth
- Bad: Spike then death, whale domination, coordinated dumps

**Early exit if:**
- Volume dies (no trades 5+ min)
- Single holder with 50%+
- Major SOL crash (>15% in 1hr)

---

## 🛡️ Stop Loss Reality: The Brutal Truth

### What You Need to Know

**Rugs happen in 10 seconds.** Manual selling = already rugged. You need automation or a system.

### What's Actually Available (Be Realistic)

**IMPORTANT:** Most bots do NOT have automatic trailing stop loss. They have:

**Fixed Stop Loss:**
- You set SL at specific price (e.g., $12k MC)
- It stays at $12k FOREVER, even if token goes to $100k
- You must MANUALLY update it as price rises
- If you forget to update = miss all upside

**Example of the Problem:**
1. Buy at $10k MC
2. Set SL at $12k after hitting $15k
3. Token pumps to $50k (5X!)
4. Your SL still at $12k (you forgot to update)
5. Token rugs to $12k, you exit at 1.2X
6. **You missed 5X because you didn't update SL**

### The Manual SL Management System

**Step 1:** Token hits 2X → Set SL at 2X (breakeven) → Set DexScreener alert at 2.5X

**Step 2:** Update every 0.5-1X gained
- Alert at 2.5X → Move SL to 2.2X (lock profit) → Alert at 3X
- Alert at 3X → Move SL to 2.5X → Alert at 4X
- Continue ladder: Keep SL ~20% below current price

**Rule:** Update SL at every major milestone (takes 30 seconds each time)

### Platform Reality Check

**Photon / BullX / Trojan / All Others:**
- ❌ NO automatic trailing SL
- ✅ Fixed SL only
- **Reality:** Manual updates required or you miss upside

### Your 3 Real Options

**Option 1: Active SL Management** (Best protection, most work)
- Set SL at 2X when reached
- Set DexScreener alerts at 2.5X, 3X, 4X, 5X
- Update SL when alert fires (30 seconds)
- Repeat 4-5 times per winning trade
- **Time:** ~2-3 min per trade over lifetime
- **Result:** Capture 80%+ upside, protected from rugs

**Option 2: Wide Safety Net** (Less work, decent protection)
- Set SL at 1.5X after hitting 2X (breathing room)
- Don't update - let it sit
- Alert only at 5X, manually sell if hit
- **Time:** 1 min to set, forget
- **Result:** Protected from total loss, miss some upside

**Option 3: No SL - Ride It Out** (Original strategy, least work) ✅
- No stop loss at all
- Set awareness alerts at 3X, 5X, 10X
- Accept catching rugs on some trades
- Catch full moonshots to 10X-50X
- **Time:** 30 seconds for alerts
- **Result:** Best long-term EV (+$88/trade), highest variance

### DexScreener Alerts (Critical for Manual SL)

1. Open token chart
2. Click bell icon
3. Set alerts at: 2X, 2.5X, 3X, 4X, 5X of entry
4. When alert fires → Update SL in bot (10 seconds)

**DexScreener updates live automatically** via websocket - no manual refresh needed.

### The Harsh Reality

**Without automatic trailing SL:**
- You manually race against rugs
- Must be disciplined updating SL
- Forget to update = lose gains
- It's tedious but necessary

**The alternative (no SL):**
- Accept catching some rugs
- Catch full 5X-10X moonshots
- Average still works (2.61x overall, 5X on winners)
- Less work, more variance

**Most successful traders pick Option 3:**
- No SL at all
- Set awareness alerts
- Accept losses as cost of moonshots
- Focus on 40% win rate averaging 5X
- **Result: +$440/week on $100 positions**

### Bottom Line: Pick Your Poison

**Don't fool yourself into thinking you have trailing SL when you don't.**

Your real options:
1. **Active SL** = Best protection, tedious (~3 min/winning trade)
2. **Wide safety net** = Mediocre protection, minimal work, okay results
3. **No SL** = Best long-term EV (+$88/trade), least work, highest swings

**All three work.** Pick based on personality and time.

**WORST option:** Setting SL at 2X and never updating, then wondering why you only made 2X when token went 10X. That's leaving money on the table.

---

## 📋 Quick Reference: Strategy Comparison

### At $25 Position Size

| Strategy | Weekly Profit | Monthly Profit | Stress Level | Time Required | Best For |
|----------|---------------|----------------|--------------|---------------|----------|
| **No SL** | **+$65** ✅ | **+$260** | Medium | 5 min/day | Diamond hands |
| **2.2X Trailing** | **+$30** ✅ | **+$120** | Low-Med | 15 min/day | Risk managers |
| **2X Lock** | -$85 ❌ | -$340 | Low | 10 min/day | Not recommended |
| **3X Only** | -$30 ❌ | -$120 | High | 30 min/day | Not recommended |

### At $100 Position Size

| Strategy | Weekly Profit | Monthly Profit | Stress Level | Time Required | Best For |
|----------|---------------|----------------|--------------|---------------|----------|
| **No SL** | **+$440** ✅ | **+$1,760** | Medium | 5 min/day | Maximum returns |
| **2.2X Trailing** | **+$300** ✅ | **+$1,200** | Low-Med | 15 min/day | Steady growth |
| **2X Lock** | -$220 ❌ | -$880 | Low | 10 min/day | Not recommended |
| **3X Only** | +$20 | +$80 | High | 30 min/day | Barely breakeven |

**Key:** Position size dramatically impacts profitability due to fixed $10 fees.

---

## 🚀 Getting Started Checklist

**Before first trade:**
- [ ] Read full guide + understand disclaimers
- [ ] Accept losses are part of trading
- [ ] Determine capital + position size (2-5%)
- [ ] Set up trading bot, test smallest position
- [ ] Choose strategy, write it down
- [ ] Set up tracking spreadsheet
- [ ] Enable Telegram notifications
- [ ] Fund wallet with SOL

**After 10 trades:**
- [ ] Review actual vs expected performance
- [ ] Calculate real win rate + average profit
- [ ] Identify mistakes made
- [ ] Adjust position size if needed
- [ ] Recommit or change strategy

---

## 💡 Final Thoughts

**Success requires:**
- Discipline to follow strategy
- Patience through losing streaks
- Capital management
- Emotional control
- Realistic expectations

**The Anubis Bot gives you an edge** - finding the 2% worth trading. But edge ≠ guaranteed profit per trade. Over hundreds of trades with sound strategy, you have positive expected value.

**Your advantage:** Discipline, strategy, and Anubis alerts. Use them wisely.

---

## ⚠️ FINAL LEGAL DISCLAIMER

**CRYPTOCURRENCY TRADING INVOLVES EXTREME RISK**

This educational guide presents strategies based on historical data analysis. However:

- **NO STRATEGY GUARANTEES PROFIT:** All trading strategies can and do lose money
- **PAST PERFORMANCE ≠ FUTURE RESULTS:** Historical win rates do not predict future outcomes
- **YOU CAN LOSE EVERYTHING:** Memecoins are highly speculative and can go to zero instantly
- **NOT REGULATED:** Cryptocurrency markets are largely unregulated and subject to manipulation
- **NO RECOURSE:** Lost funds typically cannot be recovered; there is no FDIC insurance or investor protection

**By using the Anubis Bot and implementing any strategies described in this guide, you explicitly acknowledge that:**

1. You are an adult legally capable of entering into contracts in your jurisdiction
2. You have read, understood, and agree to assume all risks associated with cryptocurrency trading
3. You will not hold the creators, operators, distributors, or affiliates of this guide or the Anubis Bot liable for any losses, damages, or adverse outcomes
4. You understand that trading memecoins can result in total loss of your invested capital
5. You are trading with discretionary funds you can afford to lose entirely
6. You have consulted with financial, legal, and tax professionals as appropriate for your situation
7. You understand this is NOT financial advice and you are making your own independent trading decisions

**SEEK PROFESSIONAL ADVICE:** Before trading, consult with a licensed financial advisor, tax professional, and attorney familiar with cryptocurrency regulations in your jurisdiction.

**TRADE RESPONSIBLY:** Never invest more than you can afford to lose. Never trade with borrowed money, credit cards, or funds needed for living expenses.

**This guide is provided "AS IS" without warranties of any kind, express or implied.**

---

*Last Updated: November 4, 2025*  
*Educational Material Only - Not Financial Advice*  
*© 2025 - All Rights Reserved*