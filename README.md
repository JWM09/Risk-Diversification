# Risk-Diversification
UW Fintech Bootcamp Module 4 Challenge Assignment

---

## Technologies

The following libraries are used in this analysis:  
  
  * pandas  
  * numpy
  * pathlib (Path only)
  * %matplotlib
  
---

## Purpose of Program

We have been tasked with evaluating various funds against the S&P 500 to understand which ones have upside, excessive risk,  
and ultimately select a fund to recommend to company for inclusion in our fund offerings.  
  
To analyze the funds we conducted the following calculations:  
  
  * Daily Return Performance  
  * Cumuative Returns  
  * Volatility
  * Standard Deviation
  * Annualized Standard Deviation (assuming 252 trading days)
  * Rolling averages
  * Sharpe Ratio
  * Beta analysis

---

## Conclusions

Through this exercise, we have recommended that our company add the Berkshire Hathaway Fund to our current offerings for clients.  
The first reason is due to their Sharpe Ratio.  As visualized in the image below, the BH Fund had a higher Sharpe Ratio than all other funds,  
including the S&P 500  

![image info](./Images/Sharpe Ratio.png)

Additionally when we look at the 60 Rolling beta for BH vs the S&P 500 we see a lower variance, which means it is more likely to follow  
the same path as the S&P 500, which helps to mitigate the risk.

---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
