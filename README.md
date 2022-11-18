<h1> :dollar: Automatic Financial Report</h1> 

<img src="http://img.shields.io/static/v1?label=STATUS&message=IN%20PROGRESS&color=YELLOW&style=for-the-badge"/>

### Topics 

:small_blue_diamond: [Project description](#project-description)

:small_blue_diamond: [Features](#features)

:small_blue_diamond: [How it works](#how-it-works)

## :clipboard: Project description 

<p align="justify">
  This project was undertaken to automate the process of compiling various financial data into a report and sending it via email. 
</p>

## Features

:heavy_check_mark: Get Ibovespa and S&P500 data from Yahoo Finance 

:heavy_check_mark: Calculate return in the year, return in the month, 12m volatility, month-to-month return and plot the charts

:heavy_check_mark: Get DI data on the B3 (brazilian stock exchange) website

:heavy_check_mark: Get dollar, inflation and selic data from the brazilian central bank website  

:heavy_check_mark: Create a custom PDF

:heavy_check_mark: Send the report by e-mail 


## :hammer: How it works

This project is divided into five parts:
1. Pick the data
2. Treat the data
3. Calculate and generate the charts
4. Generate a report in PDF
5. Send report by e-mail


### Pre-requisites

Before you begin, you will need to install the following libraries on your Python IDE:

:small_orange_diamond: html5lib
:small_orange_diamond: webdriver-manager
:small_orange_diamond: python-bcb
:small_orange_diamond: pandas-datareader
:small_orange_diamond: mplfinance
:small_orange_diamond: selenium
:small_orange_diamond: FPDF
:small_orange_diamond: mplcyberpunk
:small_orange_diamond: python-dotenv
:small_orange_diamond: pywin32


## Developer
|[<img src="https://avatars.githubusercontent.com/u/106716539?v=4" width=115><br><sub>Rafaël Magalhães</sub>](https://github.com/magalhaes-rafael)
| :---: |
[![Twitter Badge](https://img.shields.io/badge/-@omagalhaesrafa-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/omagalhaesrafa)](https://twitter.com/omagalhaesrafa) [![Linkedin Badge](https://img.shields.io/badge/-Rafaël-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/magalhaesrafael/)](https://www.linkedin.com/in/magalhaesrafael/) 
[![Gmail Badge](https://img.shields.io/badge/-rafael.rmoliveira@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rafael.rmoliveira@gmail.com)](mailto:rafael.rmoliveira@gmail.com)

## License
This project is under the license [MIT](./LICENSE).
