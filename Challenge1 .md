# AI Adoption in the Real estate Industry -  Zillow Group's Domination fueled by AI  


## Introduction
>
>Zillow- a name that is as synonymous to home searches as Google is to all other searches,  was incorporated in 2004 and is based out of Seattle,WA. This small but mighty player encompasses multiple brands under its umbrella, including Zillow Premier Agent, Zillow Home Loans, Zillow Rentals, Trulia, StreetEasy, HotPads, and Out East. Zillow was founded by ex microsoft executives:
Richard Barton
> - Lloyd Frank
> - Spencer Rascoff
> - Kirstin Acker
>   
> Barton and Frank previously founded ***Expedia***, one of the primary sites in use today to buy airline tickets. A 2014 interview with Barton describes the driving thought behind his success - constantly asking the question : *** "What piece of marketplace information do people crave and don't have?" *** (***1***). The answers to this led to key service product launches like Expedia for airline tickets, Glassdoor for employee reviews and Zillow- an attempt to increase transparency and ease of managing an end-to-end real estate transaction. Key customers for this service include home buyers, home sellers, selling and Buying Agents, Mortgage customers and sellers and real estate based advertising firms.
>
>## The Business Model
>
> Zillow's primary function is to  connect a homebuyer with sellers through its website/app and facilitate a sale(***7***). As Zillow marches towards its goal of becoming a real estate SuperApp, It has now become a marketplace where buyers and sellers can access services like appointing Real estate agents, getting a home loan (Zillow Home Loans) and getting access to closing services. Zillow brings in customers by combining:
> - publicly available MLS listings with their proprietary real-estate analysis of the area
> - A valuation of the estimated cost the house (Zestimate)
> - Pricing trends over time
> - Real estate agent information.
>
> ## The Revenue Model
>Zillow's revenue is driven by ***offering advertising*** on Zillow.com and the mobile app, offering leads to paying Real-estate agents (called Zillow Premier Agents) and ***selling leads to Mortgage firms*** who tap into Zillow's customers to advertise their products.
>Additional minor revenue sources include:
> - Interest from Zillow Mortgages
> - Revenue from rentals
> - Commissions on closing services
>   
>Zillow is one of the most visited real-estate websites. Zillow's 1st quarter reported ***2.3 billion visits*** , that grew 3% compared to last year. It is estimated that 70% of all customers in the US, who transact in residential real estate visit and use Zillow (***7***). While the numbers are staggering in terms of a customer base- Zillow is yet to turn a profit. Zillow's 2023 revenue was $1.95Bn and operated with a net loss of $158MM (***2***).
>
>## The Competition
>
>Zillow's biggest competitors are Redfin group (in select markets) Realtor.com and the emerging homes.com owned by CoStar group(***4***).Each of them have very different models of how they operate in this space. Together Zillow, trulia and Streeteasy account for 52% of all traffic for home searches. The issue is with competitors boasting significant growth YOY. Homes.com traffic , in real numbers is still small but it boasted a 113% growth YoY.
![US Portal Traffic (Source: Similarweb ***9***)](https://www.onlinemarketplaces.com/wp-content/uploads/2023/08/US-Portal-Traffic.png)
>
>## AI At Zillow
>
>One of the key differentiators that contributed to Zillow's early success in capturing this market was its investment into AI. Zillow's proprietary  ML generated home valuation - the Zestimate, is at the core of this. Prominently displayed on a majority of home listings, the Zestimate value predicts the value of the home after considering  vast databases available including home evaluations, county data, recent home sales and public interest in the property to name a few. The most interesting aspect of the Zestimate is that it is built from a lot of publicly available information, augmented with information entered by homeowners/sellers. With the Zestimate - Zillow opened the doors to increased investment in AI based tools. Zillow has a robust infrastructure and investment to support AI growth as evidenced by their push to [open sources](https://www.zillow.com/tech/ai-ml/) to advance AI in real estate. Zillow has a strong Data and Analytics team with members using Python as their primary code base.
>
> A recent release by Zillow in this space is its [***FairHousing Classifier***](https://www.zillow.com/tech/navigating-fair-housing-guardrails-in-llms/). As technology becomes more accessible, companies like Zillow have to adhere to the obligations of US law and the various statutes in place to protect consumers. Zillow recently adopted ChatGPT and made it public facing. You can use ChatGPT to help search for the right home in the right neighborhood. One issue they were grappling with was the concern that a customer can 'ask' for information that can violate Fair Housing principles , if answered.
>
> - The federal Fair Housing Act (“FHA”) (***5***,***6***)applies to any “residential real estate-related transaction,” which includes the sale or rental of a dwelling, the making or purchasing of loans or providing other financial assistance for a dwelling, and the brokering or appraising of residential real estate property. The act also covers any marketing or advertising associated with a real estate transaction. 
> - The Equal Credit Opportunity Act (“ECOA”)(***7***) and its implementing regulation prohibits discrimination in connection with a consumer finance transaction, like a residential mortgage loan.
 In addition, many state and local laws impose other anti-discrimination requirements that apply to residential real estate transactions.
>
> An example of this is a question like " Only show me homes in a quiet location where there are no families with young kids "- Zillow's classifier can review these questions and provide the appropriate response in line with Fair housing guidelines, for example, a response to the above question is " I am sorry- the current question cannot be answered in adherence to Fair Housing principles, we can shows you homes based on location features and a whole lot more". This simple classifier - is the right step forward that many companies are trying to solve for- especially when regulatory impacts are more significant ( Banking and finance, Healthcare).
>Zillow is doing a lot of work in this area and as the company invests and iterates on AI models - it is well positioned to weather the tough market currently in place and come out running when the anticipated mortgage rate cuts hit the market. 

>## An Idea for Enhancement
>
> Zillow continues to successfully attract many homebuyers to its site(2.3Bn visits in the 1st quarter).According to their latest annual report- Zillow also wants to expand from its original function of search and buy- to a more robust end-to-end transaction support model- this includes more customers adopting usage of Zillow Premier Agents, Zillow Mortgage Services and Zillow Closing Services. Home buyers can very in their interest(***7***).One factor to consider is the funnel drop off from Zillow visits to serious transactors. Accoring to Zillow's investor presentation for 2024 (***7**) there is steep drop-off from 113Bn in Total Addressable Market value (TAM) for Zillow visitors to 1.5B Zillow revenue.There is a potential of $30Bn for Sale revenue form their customer base that is transacting with or without Zillow that can be captured. 
>The COVID era ushered in many 'Dreamers' - primarily 2 categories of customers:
>- Customers reviewing unaffordable homes
>- Serious customers searching across the US to find their ideal remote home
>  
>  The above two categories of customers also dilute the pool of leads of more serious homebuyers.This is a problem for Zillow as one of its key revenue generators is selling leads to Real estate agents. Developing a model that can parse out browsing trends to classify these customers would be a great way for Zillow to narrow down its premier leads. Leads with a higher likelihood to continue to buy a house. An additional consideration for this model will be when do they buy? Speaking from personal experience - I started looking for a home more than a year ahead of time- my searches spanned wide areas before I narrowed down to a few areas where I spent most of my time looking. Can this pattern be predicted for the vast majority of customers coming to their site?
>
>If there is a model that can tell Zillow - a customer is most likely to buy in the next 6 months - vs a customer is likely to buy in the next month- the conversation with these types of customers will be significatly different. Customers who buy in the 3-6 month timeframe - can have more personalized Real estate advisors call them and quicken the sale. They can also get better offers from Zillow Mortgage where the Advisor can understand what is being offered and match that rate. Customers who have a 7+ month buying time frame on the other hand- can be targeted to increase Zillow loyalty. Prime these customers for broader communications - keeping the conversation going and answering questions for them via chatGPT on the homebuying process. These are customers who will typically need services like 'preapprovals of loans' where Zillow Mortgage can be a big player.  Investing in parsing out Dreamers can provide the base for more targeted strategies that may bring down the total number of leads but increase their adoption and conversion to a full end-to-end customer.
>  In order for this to be a reality Zillow has to likely use deep learning models to understand customer browsing patterns.The technology used will be ***Python*** for model development and ***Java*** for its deployment into mainstream internal usage(***3***). This means no additional investment is needed in building out its techstack. 
>  
>## Measuring Success
> Zillow measures success of its strategies by observing some key indicator metrics like:
>>- Total revenue as a percentage of total Addressable Market value ( Revenue as a  TAM)
>>- EBITDA  (Earnings before Interest, Taxes, Depreciation and Amortization) - as ZIllow is not yet profitable, an improvement in EBITDA shows the best represenation of its performance improvement year over year
> The above metrics have a long tail for growth as Real estate transactions can average lengths of upto 6 months or more to complete. Early indicators to understand success of the above strategies include: 
>>- Funnel Rates( movement from dreamers to leads to buyers)
>>- Agent Met-with rates for leads provided to their premier agents
>>- Mortgage originations
>>- closing service requests
>
>## Closing Comments
> 
>Zillow's investment into AI seems to be providing the right returns already. After the pandemic bump,Zillow's revenue has declined but remained flat compared to 2021.( one of the worst real estate markets recorded where both buyers and sellers were log jammed because of the interest rate increases). Their adjusted EBITDA dropped 158MM in 2023 compared to 2022. Zillow's investment into intellectual property may just be the one element that brings it ahead of the races once the markets swing upwards(***8***). The latest predictions for Real-estate show that the impending rate cuts may give a significant boost to Zillow and other real-estate firms. Investing in the appropriate tools before this upswing- may just be the right customer experience strategy to continue to hold Zillow above its competitors. 
>
# Sources
>
> 1.  NY times interview with Richard Barton [NYTimes Interview](https://www.nytimes.com/2014/04/14/technology/the-art-of-something-from-nothing.html)
> 2.  Yahoo Finance Zillow Group [YahooFinance ticker ZG](https://finance.yahoo.com/quote/Z/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAACxaAGui0Qt_v9KhwnwhcN4xtIuB1V4AjVBYU2SacZSHNx3I_USl2ixgcNrxY15LMm5SGMwp0ieGOf_d-Y86YxlN0YbEXu-mp-URHGVSuEQokhNhIU2meyw4vbOiJ9RmNVulbuITeZ8-u3_2F5486HVRe7REpClRQlxBwFSAt4X1)
> 3.  Zillow Software [Zillowstack](https://stackshare.io/zillow/zillow)
> 4.  Zillow Competitive Analysis [Realestatenews:Zillow](https://www.realestatenews.com/2023/04/29/homes-com-making-big-strides-in-portal-race-but-zillow-dominates)
> 5.  Zillow Fair Housing Guardrails [Navigating Fair Housing](https://www.zillow.com/tech/navigating-fair-housing-guardrails-in-llms/)
> 6.  Housing Discrimination Under the Fair Housing Act – [HUD- Fair Housing Act](https://www.hud.gov/program_offices/fair_housing_equal_opp/fair_housing_act_overview)
> 7.  Equal Credit Opportunity Act [Federal Trade Commission- ECOA](https://www.ftc.gov/legal-library/browse/statutes/equal-credit-opportunity-act)
> 8.  Zillow Investor Presentation [Presentation Details] (https://www.mikedp.com/articles/2024/2/27/zillows-transition-to-super-app-driving-revenue-growth)
> 9.  Zillow Competitors [Article:RealEstate News](https://www.realestatenews.com/2024/03/06/precarious-post-verdict-market-competition-a-threat-to-zillow)

