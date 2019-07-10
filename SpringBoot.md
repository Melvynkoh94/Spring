# Spring Boot Basics and Some Definitions

## Servlets
  - An applet, typically a Java software component that runs on the server
  - Its main function is to extend the capabilities of a server

## Apache Tomcat
  - It implements several Java EE specifications including Java Servlet, JavaServer Pages, WebSocket
  - Basically provides a "pure Java" HTTP web server environment in which Java code can run
  - We choose Apache Tomcat in the start.spring.io
  - Spring uses Tomcat as the DEFAULT embedded container

## JSP (Java Server Pages)
  - Equity is the difference between the value of the assets and the value of the liabilities of something owned. 
    -   ### Example     
    -     Someone owns a car worth $15,000, but owes $500 on a loan against the car, the represents $10,000 of equity
  - It can also be known as shares, equities as stocks,  shares in a company. If you buy stocks, you are buying equities.

## Spring Configurations (.properties/.yml files)
  - applications.properties or .yml (YAML)
  - This is where we generate metadata for developers to offer contextual help and "code completion" when working with custom configuration keys 
  - A great comparison - https://medium.com/@thammarath014/yml-vs-properties-1cd895e80f62
    - ### YAML Advantages
    -       Better readability
    -       YAML is a superset of JSON
    -       YAML can hold multiple profiles ina single file (example in the link above)
  
## No need for SQL Statements in Spring BOOT
  - Advantage of Spring BOOT over Spring MVC is that there is minimal or no SQL statements to be written

## POM.XML
  - A Project Object Model or POM is the fundamental unit of work in Maven
  - It is an XML file that contains information about the project and configuration details used by Maven to build the project
  - It contains default values for most projects





* [Investopedia - Liquidity] - Understanding Financial Liquidity


>  Cash is the most liquid asset. However, some investments are easily 
converted to cash like stocks and bonds. Since stocks and bonds are 
extremely easy to convert to cash, they're often referred to as liquid assets. 

  - ### Illiquid (of assets) 
  - not easily converted into cash, opposite meaning of liquid
  - Illiquid market means the market has a few participants and a low volume of activity
  - Examples of penny stocks, microcap stocks and nanocap stocks; ownership interests in private companies; collectibles like art and antiques


## Market Liquidity 
  - Refers to a market's ability to allow assets to be bought and sold easily and quickly, such as a country's financial markets or real estate market. 
  - The market for a stock is liquid if its shares can be quickly bought and sold and the trade has little impact on the stock's price. 
  - Company stocks traded on the major exchanges are typically considered liquid.

# Derivatives
 A few common forms of derivatives:
  -  ### Futures
        -   It’s an agreement between parties to buy or sell an asset at a certain time in the future and at a certain price.
        -   Let’s say there is a Christmas sale on Xbox where it’s been sold for $300 instead of $600 and you want to buy the Xbox, the only problem being: you don’t have enough money to buy it right now but you don’t want to miss out of this opportunity.
        -   If there is a way that you can buy the Xbox at the same discounted rate even after a few months then it would be great. 
        -   This contract of getting the Xbox at the discounted price after a few months is called Futures Contract. As you can see here the price is dependent on the underlying asset (Xbox) hence it’s a form of derivative.
  - ### Forwards
    - Similar to Futures with the only difference being that they are not traded on an exchange but are traded on over-the-counter markets.
    - So as there is no central exchange to keep track of what goes where and the terms aren’t regularised, you can change the lot size and the settlement process for the derivative. 
    - It also involves counterparty risk which means that it is possible that either the buyer or the seller in the contract is not able to meet financial needs or basically doesn’t have money to pay back. 
    - This happens because it is not under any regulations and sometimes buyer or seller sells the contract to some other party because of which more people get involved. 
    - Consider you and the oil company have the contract so now it is possible that the oil company will sell the contract to some other company ABC. Which means that now you and ABC have a contract which increases the counterparty risk.
  - ### Swaps
    - Swap is literally what the word means. 
    - Let’s say there are two businessmen Karan and Bhoomit, they both have 5 Playstation’s and 5 Xbox’s. 
    - But Karan wants to make business in Playstations and Bhoomit wants to make business in Xbox’s. 
    - Assume that they cannot trade directly with each other, So they go to a SWAP Bank let’s say HSBC. 
    - HSBC tells Karan to give all his Xbox’s, it then keeps one with itself and gives the rest 4 Xbox’s to Bhoomit while HSBC asks Bhoomit to give all his Playstations, keeps one to itself and gives rest 4 Playstations to Karan. 
    - Now Karan has 9 Playstations and Bhoomit has 9 Xbox’s and HSBC has 1 Xbox and 1 PlayStation. 
    - So HSBC gets some profit to initiate the swap.
        - In more real terms, let’s say Karan is in India and Bhoomit is in Australia. 
        - Karan goes to a bank in India asking for a loan for his business and the bank says we offer 
            - 1. Fixed Rate of 6%  
            - 2. Floating rate of LIBOR+3%
        - Bhoomit goes to a bank in Australia asking for a loan for his business and the bank says we offer 
            - 1. Fixed Rate of 8%  
            - 2. Floating rate of LIBOR+1%
        - Karan has the requirement of Floating Rate and Bhoomit has the requirement of Fixed Rate. 
        - So HSBC tells Karan to buy Fixed Rate, in return, he will get a Floating rate of LIBOR+2% and HSBC tells Bhoomit to buy Floating rate, in return he will get a Fixed rate of 7%. 
        - So here what HSBC does is called swapping, it swaps the Floating rate from Australia to India and Fixed Rate from India to Australia
  - ### Options
    -  Options are of two types: Call and Put. 
    -  Calls give the buyer the right but not the obligation to buy a given quantity of the underlying asset (stock), at a given price on or before a given future date. 
    -  Puts give the buyer the right but not the obligation to sell a given quantity of the underlying asset at a given price on or before a given date
    -  Even options have lot size which was discussed in the Futures post. So when you say that you buy one option of Apple, it means you buy 100 shares of Apple where 100 is the lot size.
  - ### Collateralized Debt Obligations (CDOs)
    - A CDO is actually a form of insurance (offered by FIs like AIG)
    - You bet on debt defaulters. 
    -       If the borrower defaults, the investor that bought the CDO earns. If the borrower finished repayment or amortized the loan, the investor loses.
    - A form of asset-backed debt security (ABS)
    -  CDO is "sliced" into "tranches", which "catch" the cash flow of interest and principal payments in sequence based on seniority
    -  Repackages this asset pool into discrete "tranches" that can be sold to investors
    -  FIs like AIG re-package B, BB and BBB that couldn't sell, rated them as AAA ratings, and sell them to the market (a whole new thing)
    - [CDOs] explained by Khan Academy
  - ### Synthetic CDOs
    - A CDO of a CDO
    - A CDO that invests in credit default swaps (CDSs)


# Some Definitions
  - ### Over-the-counter (OTC)
    - Private negotiations of a contract 
  - ### Clearinghouses
    - Opposite of over-the-counter
    - Trading or contract through an exchange basis, a more formal approach
    - Basically, it's a third-party agency or separate entity that acts as a go-between for buyers and sellers in the financial markets
  - ### Counterparty risk
    - the risk that the other party to the transaction will fail to perform
    - Counterparty refers to the party on the opposite side of the transaction. So if you're the buyer, your counterparty is the seller.
  - ### Tranches
    - A French for "slices", widely used in CDOs, where a pool of assets are repackaged in a form of "tranches".
  - ### Mutual Fund
    -   A managed portfolio where managers choose securities expected to perform well and group them together into a single portfolio
    -   Investors buy portion of this fund
    -   Easy to purchase with minimal cash
    -   Low-risk, low return 
  - ### Hedge Fund 
    - A much more aggressive approach as compared to Mutual Fund
    - Usually bought by investors with high-net worth
    -  Only available to accredited investors, who must meet a specific set of criteria to qualify
    - 'Risky' funds...




## Important & Useful Resources 
* [Derivatives] - Explain it to me like I am a 5 year old: Derivatives (Futures, Forwards, Swaps, Options)
* [CDOs] - How CDOs can give different investors different levels of risk and returns with the same underlying assets. Created by Sal Khan.


### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| Github | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |


   [Derivatives]: <https://medium.com/@avs431/explain-it-to-me-like-i-am-a-5-year-old-derivatives-futures-forwards-swaps-options-1d19bf204253>
   [CDOs]: <https://www.khanacademy.org/economics-finance-domain/core-finance/derivative-securities/cdo-tutorial/v/collateralized-debt-obligation-overview?utm_source=YT&utm_medium=Desc&utm_campaign=financeandcapitalmarkets>
 

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
