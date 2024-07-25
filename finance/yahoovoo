import yfinance as yf 
voo = yf.Ticker("VOO")
DATA = voo.info
PC = ((float(DATA["bid"])-float(DATA["previousClose"]))/float(DATA["previousClose"]))*100
print("{a} ({b}%) | +{c} -{d}".format(a=DATA["bid"], b=round(PC, 3), c=DATA["fiftyTwoWeekHigh"], d=DATA["fiftyTwoWeekLow"]))
