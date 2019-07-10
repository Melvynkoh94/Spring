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
  - Java Server Pages (JSP) is a server-side programming technology that enables the creation of dynamic, platform-independent method for building Web-based applications
  - It has access to the entire family of Java APIs, including the JDBC(Java Database Connectivity) API to access enterprise databases
  - JDBC: A standard Java API for database-independent connectivity between Java language and a wide range of database

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
