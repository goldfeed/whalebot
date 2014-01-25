WhaleBot
========

WhaleBot is a bot for use on CEX.io for automated trading.

Designed to hold GHS and buy more GHS with the mined BTC. The WhaleBot will also sell your GHS when the price goes down at a grade slope of 0. If the price of GHS Suddenly dips it will sell your GHS right after the initial dip. When GHS starts to rise WhaleBot will quickly buy for the sell when it reaches the the top of the down slope.

Watch WhaleBot trade live @ https://cryptotrader.org/topics/448532/whalebot-cex-io

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
