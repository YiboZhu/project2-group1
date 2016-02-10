#Travel Data of NYC<br/>

| Tables        | Source        | Ext.  |Dimension   |
| ------------- |:-------------:| :-----:|:-----:|
| Natural Preserves| [NYCOD](http://www.nyc.gov/html/dpr/nycbigapps/DPR_naturepreserves_001.csv) |csv|`Name`,`Borough`,`Directions`,`Description`,`Type`|
| Museums and Galleries| [NYCOD](https://data.cityofnewyork.us/Recreation/Museums-and-galleries/kcrm-j9hh)|xml|`Name`,`Phone&Address`,`Closing`,`Special` |
| Barbecue Areas | [NYCOD](http://www.nycgovparks.org/bigapps/DPR_Barbecue_001.xml)|xml|`Name`,`ID`,`Location`|
| Directory of Contemporary Arts|[NYCOD](http://www.nycgovparks.org/bigapps/DPR_PublicArt_001.xml)|xml|`Name`,`Artist`,`Discription`,`Lat&Lon`|
| Directory of Historical Signs|[NYCOD](http://www.nycgovparks.org/bigapps/DPR_HistoricalSigns_001.xml)|xml|`Name`,`Location`,`Borough`,`Content`|
| Time Sqare Venues|[NYCOD](https://data.cityofnewyork.us/Business/Times-Square-Entertainment-Venues/jxdc-hnze)|Any|`Name`,`Type`,`Phone&Address`,`Website`|
| Filming Permit|[Enigma](https://app.enigma.io/table/us.states.ny.cities.nyc.mome.filming-permits.events?row=0&col=2&page=1)|Any|`Name`,`Time(start&End)`,`Borough`,`Location`|