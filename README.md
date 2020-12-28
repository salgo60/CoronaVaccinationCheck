# Corona vaccine progress
see [Notebook](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Check%20Corona%20Vaccination.ipynb) 
*  accessing data from [github owid covid-19-data vaccinations country_data](https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations/country_data) and [Wikidata](https://www.youtube.com/watch?v=m_9_23jXPoE) see [WD query](https://w.wiki/sCU)

* see also [Our World in Data - Coronavirus (COVID-19) Vaccinations](https://ourworldindata.org/covid-vaccinations)

* Notebook [Check Corona Vaccination](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Check%20Corona%20Vaccination.ipynb)
  * Data source: [owid/covid-19-data/public/data/vaccinations/country_data](https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations/country_data)
    * [Issues](https://github.com/owid/covid-19-data/issues) about the data, see search [Sweden](https://github.com/owid/covid-19-data/issues?q=sweden) 
  * Sweden status reporting data about Corona Vaccination
    * Unsure were we will find Sweden data see also [description covid-19-data update procedures](https://github.com/owid/covid-19-data/pull/229#issuecomment-751218953) --> there is a lack of machine readable data
       * Sweden 
         * 2020-12-22 [www.regeringen.se](https://www.regeringen.se/artiklar/2020/12/vaccinering-mot-covid-19-inleds-den-27-december) Pfizer/BioNTech start 27 dec 9 750 doses 
* [CoronaVaccinationCheck Board](https://github.com/salgo60/CoronaVaccinationCheck/projects/1)                  
![Corona_Vaccination / Population](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Corona_VaccinationperCountryPopulation_sns_2.png?raw=true "Corona Vaccination per population")         

![Corona Vaccination Continent Scatter plot](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Corona_VaccinationperCountryPopulation_Categorical_scatterplot.png?raw=true "Corona Vaccination Continent Scatter plot")         

![Corona_Vaccination Correlation heatmap](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Correlation_heatmap.png?raw=true "Corona Vaccination Correlation")         


![Corona_Vaccination per Country](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Corona_VaccinationperCountry.png?raw=true "Corona Vaccination per Country")         

![Corona_Vaccination per Vaccine](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Corona_VaccinationperVaccine.png?raw=true "Corona Vaccination per Vaccine")         

### Version history 
* 0.5
  * new chart [Continent scatter plot](https://raw.githubusercontent.com/salgo60/CoronaVaccinationCheck/main/Corona_VaccinationperCountryPopulation_Categorical_scatterplot.png "Corona Vaccination Correlation")          
  * new parameter [continent](https://w.wiki/sBb) from Wikidata
* 0.4
  * new chart [correlation heat map](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Correlation_heatmap.png?raw=true "Corona Vaccination Correlation")          
  * new parameter [member in EU or not](https://w.wiki/s8F) from Wikidata
* 0.302
  * [Seaborn](https://seaborn.pydata.org/) used to create [barchart](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Corona_VaccinationperCountryPopulation_sns_2.png?raw=true)
* 0.3
  * as data is reported both for United Kingdom but also subnational data England, Scotland, Northern Ireland, Wales see [issue 228](https://github.com/owid/covid-19-data/issues/228) this version filter subnational data out. Subnational data have been published quite irregularly so far...
  * added translations of Labels in data to Wikidata Qnumber --> [Semantic interoperability](https://en.wikipedia.org/wiki/Semantic_interoperability#:~:text=Semantic%20interoperability%20is%20the%20ability,data%20federation%20between%20information%20systems.) with Wikidata
  * retrieved country data from [Wikidata](https://www.youtube.com/watch?v=m_9_23jXPoE) see  [query](https://w.wiki/r$X)
     * population --> Wikidata Property [P1082](https://www.wikidata.org/wiki/Property:P1082) 
     * [ISO 3166-1 alpha-3 code ](https://en.wikipedia.org/wiki/ISO_3166-1) -> Wikidata Property [P298](https://www.wikidata.org/wiki/Property_talk:P298) 
     * [nominal GDP per Capita](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)_per_capita) -> Wikidata Property  [P2132](https://www.wikidata.org/wiki/Property_talk:P2132) 
     * [PPP GDP per capita](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(PPP)_per_capita)  -> Wikidata Property [P2299](https://www.wikidata.org/wiki/Property_talk:P2299)
     * [Human Development Index](http://hdr.undp.org/en/content/human-development-index-hdi) -> Wikidata Property [P1081](https://www.wikidata.org/wiki/Property_talk:P1081) 
  * plot [Corona_VaccinationperCountryPopulation](https://github.com/salgo60/CoronaVaccinationCheck/blob/main/Corona_VaccinationperCountryPopulation.png?raw=true)
