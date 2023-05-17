# Module-11-Challenge

This assignment was split into two parts. In the first part I were asked to scrape the titles and preview the text from the Mars News website. 

I was able to scrape the titles and preview the text from the website and store them in a Python dictionary. 
An image of the stored text is below: 

 <img width="1074" alt="Screenshot 2023-05-17 at 5 58 47 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/26c65a99-e93d-4fde-b0b1-a8de31d5bf8a">

In the second part of this assignemnt I was asked to scrape and analyze Mars Weather Data from the website. 

After I scraped all the weather data from the website I assembled it into a Pandas DataFrame this way I would be able to analyze the data better. The columns in this dataframe had the same headers as the website, these included id, terrestrial_date, sol, ls, month, min_temp, and pressure. An image of the dataframe is below: 

  <img width="476" alt="Screenshot 2023-05-17 at 5 40 03 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/e2838956-f705-4fe1-91ff-a63d770185f9">

I then had to convert some of the data to the appropriate data types. ID is an int64, terrestrial_date is datetime64[ns], sol is an int64, ls is an int64, month is an int64, min_temp is a float64, and pressure is a float64. 

I then had to find how many months are there on Mars. A picture of the table is below: 

  <img width="308" alt="Screenshot 2023-05-17 at 5 44 41 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/7a828435-5d39-44a5-a111-0541452d43cd">
  
I then figured out that there are 1,867 Martian days' worth of data in the data set. I then found the average low temperature. I did this by grouping the data set by month and then finding the mean of the min_temp. A picture of the table is below: 

  <img width="353" alt="Screenshot 2023-05-17 at 5 47 48 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/8fdfe844-ae6b-43a9-83a2-500bc977be92">

I then graphed the average low temperatures in a bar graph. The bar graph is below: 

  <img width="403" alt="Screenshot 2023-05-17 at 5 49 41 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/47c2dded-6b9c-44c9-a72f-01b30b42b4c7">

I then sorted the average low temperature table so that the coldest months were at the top and the warmest months were at the bottom. The two coldest months were month 3 at -83.307292 and month 4 at -82.747423. The two hottest months were month 9 at -69.171642 and month 8 at -68.382979. 

I then was asked to find the average pressure by Martian month and I did this by grouping the data set by month and then taking the mean of pressure. A picture of the table is below: 

  <img width="351" alt="Screenshot 2023-05-17 at 5 53 47 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/d351548e-5ccd-41ca-953d-5b19b3f4468e">

I then ploted the average pressure as a bar graph. A picture of the graph is below: 

  <img width="403" alt="Screenshot 2023-05-17 at 5 55 01 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/5e53fb3d-e653-4b72-890e-417c0705dbe5">

I was then asked to find how many terrestrial (earth) days are there in a Martian year. I graphed it out and the graph is below:

  <img width="402" alt="Screenshot 2023-05-17 at 5 56 34 PM" src="https://github.com/jgillas/Module-11-Challenge/assets/125215083/2345eb70-cd18-459e-bcfb-0027a99dac0b">

Lastly in part two I exported the data to a CSV file. 

This concludes my module 11 challenge.
