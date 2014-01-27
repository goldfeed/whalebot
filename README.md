WhaleBot for CEX•IO
========

WhaleBot is a bot for use on CEX.io for automated trading.

-WhaleBot is designed to buy, hold and profit GHS when the CEX•IO market is on its way down. When the CEX•IO market is trending up WhaleBot will buy, hold and profit both GHS and BTC.

Watch WhaleBot trade live @ https://cryptotrader.org/traders/yT6eZdA48puWca3An

Donate @ 1KVZzMZfhkYXHB2cR5ynSnVGVMWw9CFNVb


Bounty
========
Have you tuned WhaleBot to be optimal?
I will pay 0.20 BTC for the most optimized WhaleBot possible using as much of the original coffeescript as possible. I would like it to be non-cumbersome to CryptoTrader.

• Must work with 0 GHS balance as well as with 0 BTC balance. ie; 80 GHS & 0 BTC or 0 GHS and 8 BTC.

Results are to be proven in a 48 hour live uninterrupted or tampered with test.

Submissions are to be sent to: gradestake@gmail.com


FUNCTIONS FOR TUNING:

    context.lag		        = 1
    context.period		    = 10
    context.NbDevUp         = 2
    context.NbDevDn         = 2
    context.FastPeriod  	= 5
    context.SlowPeriod  	= 10
    context.MAType		    = 1
    context.SignalPeriod	= 5
    context.FastMAType	    = 1
    context.SlowMAType	    = 1
    context.SignalMAType	= 1
    context.FastLimitPeriod	= 5
    context.SlowLimitPeriod = 10
    context.periods         = 10
    context.MinPeriod	    = 5
    context.MaxPeriod	    = 10
    context.StartValue	    = 0
    context.OffsetOnReverse	= 0
    context.accel           = 0.02
    context.accelmax        = 0.20
    context.AccelerationInitLong	= 0.02
    context.AccelerationLong	    = 0.02
    context.AccelerationMaxLong	    = 2.00
    context.AccelerationInitShort	= 0.02
    context.AccelerationShort	    = 0.02
    context.AccelerationMaxShort	= 2.00
    context.fastK_period	= 5
    context.slowK_period	= 10
    context.slowK_MAType	= 1
    context.slowD_period	= 10
    context.slowD_MAType	= 1
    context.fastD_period	= 5
    context.fastD_MAType	= 1
    context.vfactor		    = 1
    context.Period1        = 5
    context.Period2        = 10
    context.Period3        = 20
    context.NbDev           = 1
    context.NbVar		    = 1
