# Python / Data Science / Webscraping

#### Technical Skills: Python, Pandas, BeautifulSoup, Selenium

---

## Projects

### Webscraping ETL: BCCR dollar exchange rate extraction
[Repo](https://github.com/lemilosm/bccr_dollar_exch_rate_hist_webscr)

The Central Bank of Costa Rica website provides daily updates on USD/CRC from a page.
The page also offers the option of exporting a file of the daily exchange history since 1983-01-01.

The objective of this project is to 
(E) Extract the USD/CRC info into a Pandas dataframe.  In this case a time series one.
(T) Transform fields to proper formats, as the ones from the bank webpage may not be suitable
(L) Backup the dataframe to a a file that contains the most up to date CRC/USD exchange rate, that can later be used in other data science projects, as input data, for example as a new column, merging it to other tables/dataframes using the date index.

<!-- ![sample image](/assets/img/example.jpeg) -->


### Webscraping ETL: BCCR CRC/USD exchange rate (from different costarrican entities) extraction
[Repo](https://github.com/lemilosm/bccr_dol_exc_entities_rate_history_webscraping)

This is a project closely related to the previous one where the BCCR USD/CRC info was ETL'd.

The objective of this project is to produce a file that contains the most up to date CRC/USD exchange rate for the diferent entities, that can later be used in other data science projects, as input data, for example as a new column, merging it to other tables/dataframes using the date index.
