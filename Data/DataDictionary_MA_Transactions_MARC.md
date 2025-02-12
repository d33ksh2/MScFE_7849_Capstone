| Column Name | Description |
|-------------|------------|
| Date Announced | The date the parties announced that the transaction would happen |
| Year of Announcement | Simply the year value of the above |
| Date Effective | The date the transaction legally happened |
| Deal Value | The price that the target was acquired for (Value of Transaction $mil) |
| Deal Size | Natural Log of the above |
| Acquirer Market Value | The market value (value of equity) of the acquirer 4 weeks prior to the announcement, but 26% are empty, because the acquirers weren't publicly traded |
| Relative Size | Deal Size as a proportion of Acquirer Market Value, i.e. (Deal Size)/(Acquirer Market Value) |
| Acquirer Net Sales One Year Prior | The revenue of the acquirer 1 year prior to the transaction |
| Acquirer Size | Natural Log of the above |
| Target Net Sales One Year Prior | The revenue of the target 1 year prior to the transaction |
| Target Size | Natural Log of the above |
| Acquirer Full Name | The name of the acquirer |
| Target Name | The name of the target |
| Acquirer Nation | The geography of the acquirer |
| Target Nation | The geography of the target |
| Cross-border Deal Dummy | A binary identifier if the geographies are different |
| Target Ultimate Parent | Final owner of the target |
| Acquirer SIC Code | Identifies the primary industry of the acquirer |
| Target SIC Code | Identifies the primary industry of the target |
| Offer Price to Target Premium 1 Day Prior | Ratio of the price offered with the premium above the target's market value but contains 80% missing values, presumably because the targets weren't publicly traded |
| Offer Price to Target Premium 1 Week Prior | Ratio of the price offered with the premium above the target's market value but contains 80% missing values, presumably because the targets weren't publicly traded |
| Offer Price to Target Premium 4 Weeks Prior | Ratio of the price offered with the premium above the target's market value but contains 80% missing values, presumably because the targets weren't publicly traded |
| Acquirer Public Status | Identifier on whether it is public or private (bigger typically acquires smaller, so public acquiring private, but not necessarily) |
| Acquirer Parent Public Status | Identifier on whether it is public or private (bigger typically acquires smaller, so public acquiring private, but not necessarily) |
| Target Public Status | Identifier on whether it is public or private (bigger typically acquires smaller, so public acquiring private, but not necessarily) |
| Target Parent Public Status | Identifier on whether it is public or private (bigger typically acquires smaller, so public acquiring private, but not necessarily) |
| Acquirer Nation Region | Geography of the company ("Primary" is higher level, e.g. Europe rather than Western Europe) |
| Target Primary Nation Region | Geography of the company ("Primary" is higher level, e.g. Europe rather than Western Europe) |
| Target Nation Region | Geography of the company ("Primary" is higher level, e.g. Europe rather than Western Europe) |
| Acquirer Primary Nation Region | Geography of the company ("Primary" is higher level, e.g. Europe rather than Western Europe) |
| Acquirer Macro Industry | Identifies the industry |
| Target Macro Industry | Identifies the industry |
| Cross Industry Dummy | A binary identifier if the industries are different |
| Attitude | Categorical variable describing the nature of the acquisition, i.e., "Friendly", "Hostile", etc. |
| Consideration Structure | Whether the acquirer paid cash, stock, or a mix for the target |
| Acquirer Current Assets One Year Prior | Financial Metric ($ mil) |
| Acquirer Current Liabilities One Year Prior | Financial Metric ($ mil) |
| Acquirer Liquidity | Financial Metric (Current Assets to Current Liabilities) |
| Target Current Assets One Year Prior | Financial Metric ($ mil) |
| Target Current Liabilities One Year Prior | Financial Metric ($ mil) |
| Acquirer Total Assets One Year Prior | Financial Metric ($ mil) |
| Target Total Assets One Year Prior | Financial Metric ($ mil) |
| Target EBIT One Year Prior | Financial Metric ($ mil) |
| Acquirer EBIT One Year Prior | Financial Metric ($ mil) |
| Target EBITDA One Year Prior | Financial Metric ($ mil) |
| Acquirer EBITDA LTM | Financial Metric ($ mil) |
| Acquirer Net Sales One Year Prior | Financial Metric ($ mil) |
| Acquirer Profitability | Financial Metric (EBITDA to Sales) |
| Acquirer Net Debt One Year Prior | Financial Metric ($ mil) |
| Acquirer Leverage | Financial Metric (Net Debt to Total Assets) |
| Target Net Debt One Year Prior | Financial Metric ($ mil) |
| Target Market Value 4 Weeks Prior | Financial Metric ($ mil) |
| Acquirer Market Value 4 Weeks Prior | Financial Metric ($ mil) |
| Acquirer Common Equity One Year Prior | Financial Metric Book Value ($ mil) |
| Acquirer Market to Book Value of Equity | Financial Metric |
| Acquirer Cash One Year Prior | Financial Metric ($ mil) |
| Target Cash and Marketable Securities One Year Prior | Financial Metric ($ mil) |
| Host Currency Target Net Interest Income One Year Prior | Financial Metric ($ mil) |
| Host Currency Acquirer Net Interest Income One Year Prior | Financial Metric ($ mil) |
| Host Currency Acquirer EBIT One Year Prior | Financial Metric ($ mil) |
| Host Currency Acquirer EBITDA One Year Prior | Financial Metric ($ mil) |
| Host Currency Target EBIT One Year Prior | Financial Metric ($ mil) |
| Host Currency Target EBITDA One Year Prior | Financial Metric ($ mil) |
| Acquirer Net Income One Year Prior | Financial Metric ($ mil) |
| Target Net Income One Year Prior | Financial Metric ($ mil) |
| Target Common Equity One Year Prior | Financial Metric Book Value ($ mil) |
| Number of Bidders | The number of bidders for the target, but more than one is only 1% of the time |
| Acquirer Total Fees | Fees paid to advisors by the acquirer ($ mil) |
| Acq Fin Adv Fees as % of Deal Val | Fees paid to advisors by the acquirer, as % of deal value |
| Target Total Fees | Fees paid to advisors by the target ($ mil) |
| Target Fees % | Fees paid to advisors by the target, as % of deal value |
| Acquirer Termination Fee | Fees the acquirer would have to pay to the target if it backed out of the deal |
| Target Termination Fee | Fees the target would have to pay to the acquirer if it backed out of the deal |
| Initial Pr/Sh | Initial price per share |
| % change Initial Price to Final Price | % change Initial Price to Final Price |
| Merger of Equals | Identifies if both companies were approximately the same size |
| Proxy Fight | Identifies if a significant proportion of target shareholders attempted to overrule the management to accept/decline the acquisition |
| Significant Family Ownership of Target | Identifies if the target is significantly family-owned, because in such situations people sell their company if they're looking to retire |
| Tender Offer | Identifies whether the acquirer made a public offer to buy some or all of the target's shares |
| Target Net Sales Two Years Prior | Financial Metric ($ mil) |
| Target Net Sales Three Years Prior | Financial Metric ($ mil) |
| Purpose Code Description | Why the acquisition happened -- this may help us with motivations |
| Purpose Description | Why the acquisition happened -- full description from company |
| Purpose Code | Why the acquisition happened -- a code identifier for the purpose |
| Acquirer Full Business Description | What the company is/does |
| Target Full Business Description | What the company is/does |
| Buyside Government Owned Involvement | If there was some government ownership of the acquirer |
| Sellside Government Owned Involvement | If there was some government ownership of the target |
| Defense | If the deal was hostile, this identifies if the target used defense mechanisms to not be acquired |
| Defensive Tactics | What defense mechanisms were used, if they were used |
