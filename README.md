# NLP-Analysis_of_Automotive_Discussion_Forum

This project showcases analysis conducted using NLP on around 10,000 comments posted on Edmunds Mid-Size Sedan forum to determine top 10 brands by frequency and the most frequently mentioned attributes for these cars. Furthermore, analysis is done to see which attributes are associated with the top 5 brand names in the forum. Additional analysis is conducted to determine the most aspirational brand. The project also outlines the business insights derived from these results and how the companies can leverage this analysis to determine areas of improvement for business growth.

## Source of Data:
The data has been scraped from the following link, using "scrapper.ipynb" file:
https://forums.edmunds.com/discussion/7526/general/x/midsize-sedans-2-0

## Methodology:
1. The data (Date, User and Comment) is scraped from the discussion forum using the "scrapper.ipynb" file
2. The data is then cleaned and tokenized. Stop words and Punctuations are also removed. 
3. Top 10 most-discussed brands are determined through decreasing order of frequency
4. Lift Analysis, MDS (Multidimensional scaling) plot and Association Analysis are done to determine which brands are perceived to be closer to each other
5. An analysis is done to determine which attributes are associated with top 5 brands. Recommendations are then given to: 
(i) Product Managers and (ii) Marketing/Advertising Managers of each of these brands. 
The recommendations are also compared to news and blogs from 2007-2008 period to determine whether the analysis conforms to the actual recommendations implemented by these brands, during the same period.
6. An analysis is conducted to determine the most aspirational brand, perceived by the users of the discussion forum
