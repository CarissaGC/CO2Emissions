# Investigating CO2 Emission Trends (1971-2020) for Top 10 Highest Emitting Countries
## This project focuses on analyzing trends in CO2 emissions over 50 years from different countries, with a focus on the top 10 highest emitters as of 2020.
### Description 
This project uses Python and associated open-source data analysis tools to visualize global CO2 data retrieved from the Our World in Data github page. Using a mixture of time plots, box plots, and histograms, this project inspects the dataset for completion and uses data visualization to draw conclusions about the CO2 emission trends for the top 10 emitting countries over the past 50 years. From our analysis, we conclude that there is significant disparity in CO2 emission quantities between countries, and that there is an overall upward trend in global CO2 emissions over the past 50 years.
### Requirements
This project was completed using Google Colaboratory software and organized using a github repository. In addition, data analysis software pandas, numpy, matplotlib, and seaborn were used.
### Data
Data used in this project was obtained retrieved from the Our World in Data github page on March 29th, 2023. Their CO2 and Greenhouse Gas Emissions dataset can be found here: https://github.com/owid/co2-data
### Data Processing
The OWiD dataset owid-co2-data.csv should be viewed as raw and loaded in with pandas. To effectively use the OWiD CO2 and Greenhouse Gas Emissions dataset for this project, some adjustments must be made to the original dataset.

The dataset must be redefined to remove non-country data. See notebook for details.
### Author
This project was created by Seattle University student Carissa Caulton for MATH 2315, Probability, Statistics, and Data Computation.

Linkedin: https://www.linkedin.com/in/carissa-caulton-246419269/
### License
MIT License

Copyright (c) [2023] [Carissa Caulton]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
