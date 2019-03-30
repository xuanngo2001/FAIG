# What does it do?
- Login Code, generates a token that is used throughout the program.
- Read in lots of data from the markets for your chosen instrument.
- Create two arrays, One Array has an (Low Price, Volume) and the second (High Price)
- Pass this into a Linear Regression Algorithm.
- Returns the next High price prediction point.
- Check this is at least 80% accurate
- Check if this prediction is above or below current price on market.
- Trade accordingly, Long or Short.
- Check the price continuously until in profit.
- Trade either hits Limit Distance OR predefined limit.
- Close trade
- Loop round again.

**Note to self**: It only uses linear regression function to predict price. I haven't read the code but this is can be served as a good example to see how to interact with IG api.


# Reference
- https://www.reddit.com/r/Forex/duplicates/7q6af1/faig_fully_automated_ig_trading_a_python_script/
- https://labs.ig.com/rest-trading-api-reference

# FAIG - Fully Automated IG Index

1. Requires a valid IG Index Account - https://www.ig.com/uk/welcome-page
2. Requires a valid IG Index API Key. (Works for DEMO and LIVE accounts)
3. Cross Platform (Linux and Windows)
4. Python3

Copy default.conf to config.conf and add all settings there

**We have a Discord Server for Help, Support and Chat .... https://discord.gg/ZfwukPz**

**More Information can be found on Reddit ....https://www.reddit.com/r/UKInvesting/comments/7q67cw/faig_fully_automated_ig_trading_a_python_script/**

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WQ6V6K8ZY6D84">
  <img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" alt="Donate with PayPal" />
</a>

###### Bitcoin Cash (BCH) - 	qpz32c4lg7x7lnk9jg6qg7s4uavdce89myax5v5nuk
###### Ether (ETH) - 				0x843d3DEC2A4705BD4f45F674F641cE2D0022c9FB
###### Litecoin (LTC) - 			Lfk5y4F7KZa9oRxpazETwjQnHszEPvqPvu
###### Bitcoin (BTC) - 			14Dm7L3ABPtumPDcj3REAvs4L6w9YFRnHK
