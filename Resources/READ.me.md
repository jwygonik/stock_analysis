# VBA _stockanalysis

## Overview of Project
Steve is new to the financial industry and wants to help two of his clients diversify their investments in green energy stocks to maximize their return. 

### Purpose
His clients have already invested all their money into DAQO and he would also like to assess how these stocks are faring compared to other companies in the green energy industry. Steve would like to find the total daily volume and yearly return for each stock. Daily volume is the number of shares traded throughout the day and measures how active the stock is. The yearly return gives us the difference in the percentage of the price from the beginning of the year to the end of the year. 

Steve recruited me to help automate his analyis to control for errors and give him the opportunity to reuse the code in the future. 


## Results
When analyzing the DQ ticker and the data from 11 other green energy stocks we saw a significant difference in the both the values for "Total Daily Volume" and the "Return" for each from 2017 to 2018. 

### Analysis
When looking at the DQ Total Daily Volume specifically it appears it is not traded as actively as the other stocks in this category. In 2017 it was traded the least actively amongst the other 11 green energy competitors that we analyzed. There was a very large margin between DAQO and the majority of the other stocks in this category. In 2018 we saw a sizeable jump in DQ's Total Daily Volume, but it was still traded much less actively relative to their competitors. 

/assets/Resources/VBA_Stocks_Analysis_2017.png

When assessing the Yearly Return for DQ there was an impressive increase in the price for the stock at the end of 2017 with 199.4%. It had the highest yearly return percentage in their group of competitors. The only other company that came close to that jump in price was the SEDG ticker at 184.5%. However, when we analyzed the data from DQ's 2018 ticker, the yearly return percentage was in the negatives at 62.6%. This appears to be on trend with the rest of the competition as 10 other competitiors were also in the negatives on their yearly return. The only two tickers that saw an increase in the yearly return for 2018 were ENPH and RUN. It is also important to note that these two tickers had the highest "Total Daily Volume" values and appeared to be performing the best across the board for 2018. 

/assets/Resources/VBA_Stocks_Analysis_2018.png

The data suggests that ENPH is steadily outperforming the other tickers in both the "Total Daily Volume" and the "Return" categories. This would be a good stock for Steve to identify to his clients and recommend as they look for ways to diversify their stock portfolio. 


## Summary
Using refractored code to perform this analysis allowed us to provide a cleaner, shorter, more comprehensible code for our client. This is an advantage for any future applications of this code because it removed redundancy and increased the codes effectiveness. A disadvantage might be the impression the imporved code has on the client. It is not extremely salient to the untrained eye that many changes were made.

One of the advantages of using original and refractored code in VBA script is it simplifies the process for the coder. Having something original to work from is a huge advantage and saves a lot of time compared to constructing a code from scratch. One of the main disadvantages of using the refractored code in VBA script is debugging problematic areas. Although you have the original code to reference, it can be very time consuming to isolating and correcting the problem area. 


