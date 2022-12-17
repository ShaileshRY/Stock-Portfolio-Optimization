# Stock-Portfolio-Optimization

### Objective: Create a portfolio of stocks that appropriately balances the conflicting risk and profit and compare different investment strategies.  

#### In this project, I will investigate investment strategies for stocks based on Modern Portfolio Theory (MPT) and momentum trading (MT).

#### Modern Portfolio Theory (MPT): In MPT, my goal is to allocate money into stocks to maximize the expected return while accounting formy risk tolerance, which is measured by volatility. Unfortunately, I cannot optimize two conflicting quantities (profit and risk) simultaneously. Instead, I will take a piecewise approach: for each given risk tolerance ceiling (the max amount of risk I am willing to take on), I will maximize profit for that given risk level. So I will calculate one optimal mix of allocation of stocks that maximizes profit for each risk level; for example, if I evaluate 100 different risk levels, I will have 100 (potentially distinct) allocations. Low-risk levels will have well-balanced and diversified portfolios, but I will probably make less money. High-risk levels will have very skewed/narrow portfolio mixes (like only buying Tesla in your portfolio!), but this can be highly volatile. My goal is to show the range of profit outcomes you could achieve for all risk levels (the efficient frontier).

#### Momentum trading (MT): The MT strategy is based on the crossing points of the moving averages. If we consider the moving averages of 9 days and 21 days, buy operations are triggered when the 9-day moving average becomes larger than the 21-day moving average, and sell operations are triggered when the 21-day moving average becomes larger than the 9-day moving average. My goal is to identify good parameters for a momentum trading strategy tailored for a portfolio identified by the MPT model.

I chose the following three sectors: Energy, Financials, Materials
I have picked three stocks from each sector, and I will create an optimal portfolio of three stocks out of the 9 that I have initially selected.

Energy Sector Stocks
1. ExxonMobil (XOM)
ExxonMobil Corporation is an American multinational oil and gas corporation headquartered in Irving, Texas. The company is vertically-integrated across the entire oil and gas industry, and within it is also a chemicals division which produces plastic, synthetic rubber, and other chemical products. ExxonMobil is the largest investor-owned oil company in the world, and the largest of the Big Oil companies in both production and market value.
2. Chevron Corporation (CVX)
Chevron Corporation is an American multinational energy corporation. The second-largest direct descendant of Standard Oil. It is headquartered in San Ramon, California, and active in more than 180 countries. Chevron is one of the largest companies in the world and the second largest oil company based in the United States by revenue.
3. Schlumberger (SLB)
Schlumberger Limited is an oilfield services company. Schlumberger has four principal executive offices located in Paris, Houston, London, and The Hague. Schlumberger is the world's largest offshore drilling compan and biggest offshore drilling contractor (in terms of revenue) in the world.

Financial Sector Stocks
1. BlackRock (BLK)
BlackRock, Inc. is an American multi-national investment company based in New York City. Founded in 1988, initially as a risk management and fixed income institutional asset manager, BlackRock is the world's largest asset manager, with US$10 trillion in assets under management as of January 2022. BlackRock operates globally with 70 offices in 30 countries, and clients in 100 countries.
2. Lincoln Financial Group (LNC)
Lincoln National Corporation operates multiple insurance and investment management businesses through subsidiary companies. LNC was organized under the laws of the state of Indiana in 1968, and maintains its principal executive offices in Radnor, Pennsylvania.
3. Citigroup (C)
Citigroup Inc. or Citi is an American multinational investment bank and financial services corporation headquartered in New York City. Citigroup is the third largest banking institution in the United States; alongside JPMorgan Chase, Bank of America, and Wells Fargo, it is one of the Big Four banking institutions of the United States.

Materials Sector Stocks
The stocks selected under Materials sectors are of those firms which are the among the leading companies in the world. These stocks are large cap stocks, i.e. they have a market cap of $10 Billion or more. Large-caps are generally safer investments than their mid- and small-cap counterparts because the companies are more established.
1. Barrick Gold (GOLD)
Barrick Gold Corporation is a mining company that produces gold and copper with 16 operating sites in 13 countries. It is headquartered in Toronto, Ontario, Canada. Barrick had been the world's largest gold mining company until Newmont Corporation acquired Goldcorp in 2019.
2. Newmont Corporation (NEM)
Newmont Corporation is a gold mining company based in Greenwood Village, Colorado, United States. It is the world's largest gold mining corporation. In addition to gold, Newmont mines copper, silver, zinc and lead.
3. PPG Industries (PPG)
PPG Industries, Inc. is an American Fortune 500 company and global supplier of paints, coatings, and specialty materials. With headquarters in Pittsburgh, Pennsylvania, PPG operates in more than 70 countries around the globe. By revenue it is the largest coatings company in the world
