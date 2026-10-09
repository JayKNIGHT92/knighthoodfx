---
title: Pips, lots and leverage explained with real numbers
date: 2026-10-07
category: Basics
description: Demystify forex position sizing, pip value calculations, and margin requirements with step-by-step mathematical examples and realistic trading scenarios.
---
## Introduction

When beginners take their first steps into foreign exchange trading, they are usually drawn in by charts, technical indicators, or fundamental economic news headlines. But as soon as they open a live trading platform or order window, they encounter three core technical terms that dictate every order execution: pips, lots, and leverage.

Many new traders breeze past these concepts, treating them as mere jargon or leaving calculations entirely to automated trading calculators. Unfortunately, ignoring the foundational mechanics of how trade size, price movement, and borrowed capital interact is the single fastest way to suffer unexpected losses or blow up a trading account.

To trade forex sustainably, you do not need an advanced degree in mathematics. You do, however, need to understand the exact mathematical relationship connecting these three variables. A pip tells you how far price moved; a lot determines how much each unit of that movement is worth in cash; and leverage dictates how much capital you must post as collateral to hold the trade.

In this comprehensive guide, we strip away vague definitions and dive straight into real-world numbers. By walking through clear, step-by-step calculations across major, minor, and JPY currency pairs, you will learn how to calculate risk, size your positions accurately, and handle leverage responsibly.

_The Triad of Position Sizing: Pips measure market distance, Lots determine monetary scale, and Leverage controls purchasing power. Master their combination, and you master account protection.


## What is a Pip? (Percentage in Point)
A pip stands for "Percentage in Point" or "Price Interest Point." It represents the standardized unit of measurement used to track changes in value between two currencies. A pip is the standard unit of price movement. For most pairs it is the fourth decimal place, so a move in EUR/USD from 1.0800 to 1.0850 is 50 pips. For pairs with the Japanese yen, a pip is the second decimal place.

### Standard 4-Decimal Currency Pairs
For the vast majority of global currency pairs—such as EUR/USD, GBP/USD, and AUD/USD—a pip corresponds to a price movement in the fourth decimal place (0.0001).
Example: If EUR/USD moves from 1.0850 to 1.0855, the price has increased by 5 pips.

### Japanese Yen (JPY) 2-Decimal Pairs
The Japanese Yen is a notable exception. Because the Yen trades at a much higher nominal value relative to Western currencies, JPY currency pairs (such as USD/JPY, EUR/JPY, and GBP/JPY) are quoted to two decimal places. For JPY pairs, a single pip corresponds to a change in the second decimal place (0.01).
Example: If USD/JPY advances from 152.20 to 152.85, the exchange rate has moved upward by 65 pips.

### What About Fractional Pips (Pipettes)?
Modern digital broker platforms quote prices to an additional decimal digit—the fifth decimal place for standard pairs (0.00001) and the third decimal place for JPY pairs (0.001). These extra digits are called pipettes or fractional pips.
Example: If EUR/USD moves from 1.08502 to 1.08508, price moved by 6 pipettes, which equals 0.6 pips.


## What is a Lot? (Position Sizing)
Currencies are not traded in single dollar or euro increments; they are traded in standardized contract sizes called lots. A lot represents the exact amount of base currency unit you buy or sell in a single order.

In retail forex trading, there are three primary lot sizes you will use:

### Standard Lot (1.00 Lot):
Consists of 100,000 units of the base currency. On EUR/USD, 1.00 lot represents a $100,000 contract value.

### Mini Lot (0.10 Lot):
Consists of 10,000 units of the base currency. On EUR/USD, 0.10 lot represents a $10,000 contract value.

### Micro Lot (0.01 Lot):
Consists of 1,000 units of the base currency. On EUR/USD, 0.01 lot represents a $1,000 contract value.

## Calculating Real Pip Values
To understand how much money you win or lose per pip, you multiply your lot size by the pip increment (0.0001 for 4-decimal pairs). Assuming an account denominated in US Dollars trading EUR/USD:
- 1 Standard Lot (100,000 units): $100,000 \times 0.0001 = \mathbf{\$10.00\text{ per pip}}$1
- Mini Lot (10,000 units): $10,000 \times 0.0001 = \mathbf{\$1.00\text{ per pip}}$1
- Micro Lot (1,000 units): $1,000 \times 0.0001 = \mathbf{\$0.10\text{ per pip}}$


## What is Leverage and Margin?
Very few retail traders have $100,000 cash sitting in a trading account to purchase a single standard lot of EUR/USD. This is where leverage and margin come into play.

Leverage allows you to control a large trade position using a small amount of your own capital. Margin is the specific collateral deposit required by your broker to open and maintain that leveraged position.

### How Leverage Ratios Work
Leverage is expressed as a ratio, such as 30:1, 50:1, 100:1, or 500:1. The ratio shows how many times larger your contract size can be relative to the margin deposited:

### 1:1 Leverage (No Leverage):
To open a $100,000 position, you must deposit $100,000 margin.

### 30:1 Leverage (European Regulatory Limit):
To open a $100,000 position, you need 3.33% margin ($3,333.33 deposit).

### 100:1 Leverage:
To open a $100,000 position, you need 1.00% margin ($1,000 deposit).

### 500:1 Leverage:
To open a $100,000 position, you need 0.20% margin ($200 deposit).

_Leverage Warning: Leverage is a double-edged sword. While it allows small accounts to control meaningful trades, high leverage increases exposure to fast margin calls if price moves against you.

## Real-World Walkthrough: Combining Pips, Lots, and Leverage

Let us put all three concepts together in a comprehensive, real-world trading scenario.

### Scenario Parameters:
Account Balance: $2,000 USD
Account Leverage: 100:1 (1% Margin Requirement)
Currency Pair: EUR/USD
Entry Price: 1.0850
Trade Position: Buy (Long) 0.20 Lots (2 Mini Lots = 20,000 units)
Take-Profit Target: 1.0895 (+45 pips)
Stop-Loss Target: 1.0825 (-25 pips)

### Step 1: Calculate Total Position Value & Required Margin

$$\text{Position Value} = 20,000\text{ units} \times 1.0850 = \$21,700\text{ total contract value}$$$$\text{Required Margin (at 100:1)} = \frac{\$21,700}{100} = \mathbf{\$217.00}$$Your broker locks $217.00 of your $2,000 balance as collateral, leaving $1,783.00 in Free Margin.

### Step 2: Calculate Pip Value

$$\text{Pip Value} = 20,000\text{ units} \times 0.0001 = \mathbf{\$2.00\text{ per pip}}$$

### Step 3: Calculate Profit / Loss Outcomes

Winning Outcome (+45 pips): $45\text{ pips} \times \$2.00/\text{pip} = \mathbf{+\$90.00\text{ profit}}$. New account balance = $2,090.00 (+4.5% account gain).
Losing Outcome (-25 pips): $25\text{ pips} \times \$2.00/\text{pip} = \mathbf{-\$50.00\text{ loss}}$. New account balance = $1,950.00 (-2.5% account loss).


## Smart Position Sizing Rules for Beginners

To protect your account from devastating drawdowns, always base your lot size on a fixed dollar risk model rather than guesswork:

### 1. Risk No More Than 1% to 2% Per Trade:
If your account holds $2,000, risking 1% means your maximum allowable dollar loss on a trade is $20.00.

### 2. Calculate Lot Size Based on Stop Loss Distance:
If your trade setup requires a 40-pip stop loss and your maximum risk is $20.00, your allowable pip value is:

$$\text{Allowable Pip Value} = \frac{\$20.00}{40\text{ pips}} = \$0.50/\text{pip}$$

This means you should open a 0.05 Micro Lot position (5 Micro Lots).

### 3. Ignore Available Margin as a Reason to Over-Leverage:
Just because 500:1 leverage allows you to open 5 standard lots on a small account does not mean you should. Always let your stop loss distance determine your trade size.

## Conclusion

Pips, lots, and leverage are not complex obstacles—they are the basic mathematical toolkit of every professional trader. By taking the time to master pip calculations, choose proper lot sizes, and treat leverage as a risk management tool rather than a lottery ticket, you instantly place yourself ahead of most retail traders.

Before placing your next trade, practice running these numbers manually or verifying them inside a demo account. Developing complete mathematical clarity is the cornerstone of disciplined, long-term forex trading.


Decide how much of your account you will risk per trade (many educators suggest 1% or less), then choose a position size that fits that limit. Use a stop-loss, and start with micro lots while you learn.
