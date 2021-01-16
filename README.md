# Frequently Asked Questions about TSD on Binance Smart Chain

<hr/>

## True Seigniorage Døllar

### What is True Seigniorage Dollar? 

TSD is designed to be fully a decentralized self-stabilizing dollar.


### Who created TSD?

The team is anonymous. 

However, if you'd like to contact them you can email them here: truedollar@protonmail.com

### If TSD is a stablecoin, is it always worth $1?


No. The goal, at maturity, is to see the stablecoin stay very close to \$1.  However, it is expected in the early days of the project, it will be more volatile. Some volatility is natural -- the whole design of the protocol is to adjust the money supply when the price diverges -- consequently, it is not a surprise that it would diverge. And the fact that it was designed with a maximum award in one epoch of 1.1, indicates the designer felt like prices above $1.10 were to be expected.  So high volatility in the early days of the project is not necessarily a sign the protocol is not working.  However, over time it is expected for the volatility to subside and TSD to maintain its peg against the desired asset.


### How TSD's supply grow in relation to token holders? 

TSD uses a seigniorage model to grow the money supply. This means, if the market demands more TSD (more buyers than sellers of TSD), more of the coin (TSD) will be minted to meet that demand and bring the price back down to $1.  That extra minted money supply is distributed to the current holders of TSD (who have taken steps to lock their holdings to the protocol, as detailed below.). Keep in mind, if the reverse happens -- demand goes down -- the protocol has to reduce the supply of TSD, having an opposite effect.

### How does TSD become a sustainably useful token?

For TSD to become a sustainably useful stablecoin like USDT or DAI, it must begin to be accepted as currency by DeFi and other applications on the Ethereum protocol. In periods of volatility, the token's utility may be diminished. However, as the protocol matures the volatility will reduce increasing its utility. 

### I want to contribute to TSD’s success, what should I do?

Thank you for wanting to help make the project succeed. You can contribute to everyone’s benefit in many ways. Some clear ones:

- Take time to do research on the project to understand the implications of the protocol and how it can be applied to the DeFi ecosystem.
- Join the Telegram group linked from the DAO to help answer questions & discuss governance issues. 
- Advocate for TSD to be added into other DeFi platforms

<hr />

## Token Mechanics

### What is an epoch?

The length of time between adjustment to the money supply. Every epoch, currently 15 mins on BSC, the protocol assesses whether the money supply ought to grow or shrink, and then issues rewards or debt to make that happen. As an investor, at the end of every epoch you receive rewards if it expands.

### What is a coupon?

Coupon is the method used to shrink the money supply. Simply, the protocol offers an incentive for users to voluntarily burn their TSD in return for a coupon that can be redeemed when the money supply grows again, to regain their TSD along with a bonus for having bought the debt.

### What is staging?

### What is bonding?

### What do frozen and fluid states mean?

The best way to visualize this is with the flow below:

**Deposit/Withdraw ←→ Staged ←→ Bond/Unbond.**

- Any time, you use Bond or Unbond once, you go into a locked state
- Upon the next 48 hours with LP (or 72 hours with DAO), you will go back into the unlocked state

**In locked state:**

- You will not be able to withdraw or deposit
- You will be able to bond/unbond any number of times.

**In unlocked state:**

- You will be able to deposit and withdraw.
This means when you are bonded and want to withdraw, you will first unbond, spend the 48 hours with LP or 72 hours with DAO in locked state and when state changes to unlocked, you will be able to withdraw.

For Deposit, you will be able to deposit and bond in the same epoch as when you deposit and stage you will still be in a unlocked state, but as soon as you bond, you will be in a unlocked state, so you cannot deposit again in the next 48-72 (LP-DAO) hours, or withdraw.

Unlocked and Locked states appear on the wallet page and the LP Reward Pool page of the DAO. This terminology is a bit confusing, but you are basically allowed to interact with the DAO by bonding or unbonding TSD or LP just once per epoch. Unlocked and Locked tell you the state of your access to transacting with the DAO. “Unlocked” enables you to transact.

### Should I advance an epoch? What does this mean?

Epochs happen every 15 mins. For technical reasons, someone needs to manually trigger the start of a new epoch. Advancers are competing for the 1 TSD reward. Some users write bots to call it, or you can also manually try it at https://bsc.truedollar.finance/#/epoch/.

### What does the governance page do and how should I engage with it?

Since TSD is owned by the users, there is a governance section for proposals to make changes. You need to own at least 1% of bonded DAO to make a new proposal. This again is probably something to engage in when you have already mastered the basics.

### Why do some epochs grant rewards and some epochs do not?

If there is excess demand for TSD, then the price will trend above $1 on the Pancakeswap pool, and that signals the protocol to mint additional token supply. Conversely, if the demand shrinks, excess selling on Pancakeswap will push the price below $1, which triggers the protocol to generate debt and incentivise token holders to burn TSD to shrink the token supply.

If the money supply needs to be shrunk, no supply expansion will be made that epoch. If the money supply was shrunk in the past, those debts will either remain on the protocol, or get bought by users in the form of coupons. Both coupons and debt will be paid off in the future ahead of new rewards, so it is possible to receive no new rewards in a money supply expansion epoch if there are historical debts to be repaid first.

### How do we know if any given epoch will have rewards and how much rewards?

You can’t know for sure until right when the new epoch is triggered as the TWAP price is adjusted by the trading activity right up to the new Epoch.

You can estimate the amount of rewards by looking at the Regulation page on the DAO and doing some calculations. We made the [TSD Tools](https://bsc.truedollar.finance/#/tool/), that makes an estimate of what, if any, rewards can be expected in this epoch, but it is not perfect, only indicative.

<hr/>

## Maintaining TSD's price peg

### How do I participate in maintaining the peg?

In order to participate in maintaining the price peg for TSD you need to have tokens to either bond or provide liquidity with. 

### How do I buy TSD?

Currently the only place to buy TSD is the Pancakeswap TSD-BUSD pool. For your safety, please access this pool by going to the Trade page of the TSD DAO site and clicking the trade button, which will take you to the pool: (https://bsc.truedollar.finance/#/trade/)

Because TSD has not been whitelisted at Pancakeswap, you have to approve the unknown token. Please understand, in these early days of TSD, the price can be very volatile. In recent bull runs, the price of TSD has gone up over $1,121 per BUSD, even though over time it should converge to $1. So pay attention to what price you are paying when you buy it. On the other hand, in these bull periods, returns can often hit 1% compounding per epoch (160% daily), which if it held into the future could offset any premium paid. The future is inherently uncertain so you have to use your own judgment here.

### Do I gain rewards for buying TSD?

If you buy TSD on Pancakeswap but do nothing else, no. Your TSD is in a state called “circulating” and it just sits inert.

### What methods exist to receive TSD rewards?

There are three methods to generate rewards when holding TSD:

1. Take your TSD and bond it to the DAO (recommended for beginners)
2. Take your TSD and provide liquidity to the Pancakeswap LP pool, and bond those tokens to the DAO to receive liquidity rewards. 
3. Buy TSD debt coupons during periods the protocol goes into debt, and redeem them later when it goes into surplus

### How does bonding compare with providing liquidity?

The relative reward to bonding to the DAO, and providing liquidity in the Pancakeswap pool, vary somewhat. 60% of created new supply is awarded to those who bond to the DAO, and 40% to people who provide liquidity to the LP. Depending on the total amount in the Pancakeswap LP, those rewards can vary dramatically. Also, being a liquidity provider has its own risks including impermanent loss.

We made [TSD Tools](https://truedollar.finance/#/tool/) which estimates the relative rewards for the current epoch. Large token holders can move large sums in and out of the LP pool on Pancakeswap in between epochs and dramatically move the rewards distributed to the LP.

Further, the rewards can change right up to the end of the epoch. So LP rewards are sometimes higher than the DAO, sometimes less, but are more volatile.

### As a beginner, how should I use my tokens to balance the peg?

Bonding your TSD to the DAO is very likely the best way to go. It is simple, and you can “set it and forget it”.

Entering the liquidity pool is more complicated — you have to provide at uniswap, risk impermanent loss, stake the Pancakeswap token at the DAO. Most importantly, this method does not automatically add the reward into the LP pool — each epoch you are granted rewards but they will just float, circulating, unless you take action every 48 hours to enter them (either re-providing them into the liquidity pool, or claiming them and staking them to the DAO). For these reasons, when getting started, bonding to the DAO is a good place.

Purchasing coupons also has risks — you have to have a view on when the protocol will come out of debt, and if the protocol goes a month without coming out of contraction, your coupons could expire — so as a beginner coupons may not be for you.

### What are the exact steps to buy TSD from Pancakeswap and bond to the DAO?

1. Step 1. Go to the Trade page on the DAO site: https://bsc.truedollar.finance/#/trade/
2. Step 2. Click on Trade button to go to Pancakeswap
3. Step 3. Connect to Pancakeswap, and approve the tokens for trading
4. Step 4. Enter an amount of BUSD into Pancakeswap, approve the transaction and buy TSD.
5. Step 5. Pay attention to the price and slippage as the market’s liquidity changes hourly.
6. Step 6. Come back to the TSD DAO wallet page: https://bsc.truedollar.finance/#/dao/
7. Step 7. Click unlock to allow the DAO to interact with your TSD
8. Step 8. Enter the number of TSD into the Staged Deposit box — or click max — then click the Deposit button and approve the transaction, wait for that transaction to complete on the Binance Smart Chain network.
9. Step 9. Click Max to load the box next to the “bond” button and click bond. When that transaction clears, your TSD will be bonded to the DAO and begin earning rewards at the end of the epoch.

> **Note**: that once you initiate a bond during an epoch, you will not be able to deposit/withdraw thereafter for 72 hours.

### What are the exact steps to bond Pancakeswap LP pool tokens?

You should probably not do this unless you have experience with Pancakeswap LP staking. If you are comfortable with the processed the following:

1. Step 1. Bond TSD & BUSD on Pancakeswap
2. Step 2. Go to https://bsc.truedollar.finance/#/pool/
3. Step 3. Click “Unlock”, and wait for confirmation
4. Step 4. Under the “Stage” section: Enter amount and click “Deposit”, and wait for confirmation
5. Step 5. Under the “Bond” section: Enter amount and click “Bond”, and wait for confirmation

### What can I do with rewards from bonding to the DAO?

If you have bonded to the DAO, any awarded TSD are automatically bonded, so your rewards continue to compound automatically.

If you want to sell TSD, you must first unbond them from the DAO, and then unstage them. After you unbond, you need to wait until the subsequent epoch to unstage them. This delay of a 72 hours to access your TSD is deliberate.

### What can I do with rewards from bonding Pancakeswap LP tokens?

After you are rewarded tokens for providing liquidity to the Pancakeswap pool, they will appear on the LP Reward Pool page of the DAO (https://bsc.truedollar.finance/#/pool/) under rewarded on the header. Those tokens, in that state, are circulating — they are not generating further rewards. You need to unbond (wait 48 hours) to claim the rewards from bonding Pancakeswap LP tokens. With your claimed TSD, you can sell it, bond it back to DAO or start bonding Pancakeswap LP tokens again.

<hr />

## Troubleshooting

### I am trying to do an action on the DAO site, such as deposit or bond, and the button stays grayed out or won’t work -- why might this happen?

Chances are, you already did a transaction in Locked state, and have to wait until the status is Unlocked to interact again. See above regarding Locked and Unlocked states.
