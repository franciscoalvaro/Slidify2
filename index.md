---
title       : Savings Calculator	
subtitle    : Version1.0
author      : Francisco Alvaro - SPAIN -
job         : Engineer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap] # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Savings Calculator App

   
    A simple savings calculator take into account several factors
    as current balance, current salary, annual salary increase, rate of inflation,
    percentage of saving monthly or bank interest. 
    
    Savings Calculator app make a prediction of your future balance in the number 
    of months that you specified.
   <hr/>

    

--- .class #id 


## Manual (1/2)

  <h3>Data input
  <br/>

  On the left side of the Savings Calculator app, the user must input several factors. <br/>
  
  The user have to select the correct value of the followings parameters: <br/>

   1. Current balance - It's its current balance of savings. <br/>
   2. Rate of inflation. <br/>
   3. Current salary.  <br/>
   4. Percentage of salary increase. Amount in percent of your annual increase salary <br/>
   5. Percentage of monthly savings. Amount in percent you save by month<br/>
   6. Bank interest. Interest that banks give you for your money stored in them. <br/>
   7. Number of months. Its the amount of months which you want to calculate your savings prediction. 


--- .class #id 
    

## Manual (2/2)

 
   <h3>Findings
   <br/>
  
   On the right side the user can see the echo of input of current balance <br/>
   and current salary and the final calculate of its future balance.<br/>

   Too, the user can see a little tutorial embebbed in the website itself. 



--- .class #id 



## Theory

    The formula 


    The mathematical formula for calculating the future balance is the following:

    $Future balance = CB + (1 + BI - RI) * \frac{ (1 + (\frac{IS}{1200} * CS * PSM  }{ 1200}$

    where
    CB is Current Balance
    BI is Bank Interest
    RI is Rate of Inflation
    CS is Current Salary
    IS is Increase Salary, and 
    PSM is Percentage of Savings Monthly

    
    ```r
    2 + 2
    ```
    
    ```
    ## [1] 4
    ```

   

--- .class #id 
    





