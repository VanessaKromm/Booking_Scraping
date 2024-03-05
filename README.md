# Booking_Scraping

## Purpose
This repository looks at the effect on hotel prices for Barcelona due to the Primavera Sound Festival (30.05. - 01.06.2024). For that, hotel prices for the week of the festival (27.05. - 02.06.) and the week before as baseline (20.05. - 26.06.) were scraped from Booking.com. Together with the prices, also main features of the hotels as well as the descriptions were scraped, to include more features in the analysis. To make sure, that the change in prices really is because of the festival, hotel prices for the same 2 weeks were scraped as well for Rome. With that, a Difference in Difference analysis was possible.

## Structure
The Jupyter Notebook contains all the code that was used to scrape the data and analyse it. The data, that resulted from scraping can be found in the folder "raw_data". For the regression, reshaping of the data and implementation of text features were necessary. The files can be found in the folder "data_for_regression". Lastly, the results of the analysis are reported in the PDF document "FinalReport.pdf".
