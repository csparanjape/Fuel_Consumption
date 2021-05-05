# Fuel Consumption

This project analyses fuel consumption and carbon emission of light duty vehicles available for sale in Canada.
The dataset includes information about fuel consumption for dofferent models in period 1995-2014. 

The data is downloaded from this source - [DATA Source-(Original Fuel Consumption Ratings 2000-2014)](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64)


After first round of data cleaning, following features are kept in the dataset.


- **MODELYEAR** e.g. 2000
- **MAKE** e.g. Acura
- **MODEL** e.g. ILX
- **VEHICLE CLASS** e.g. SUV,COMPACT,MID-SIZE etc.
- **ENGINE SIZE** e.g. 4.7 (lit)
- **CYLINDERS** e.g 6
- **TRANSMISSION** e.g. A6
- **FUEL TYPE** X,Z, etc. 
- **FUEL CONSUMPTION in CITY**(lit/100 km) e.g. 9.9
- **FUEL CONSUMPTION in HWY** (lit/100 km) e.g. 8.9
- **FUEL CONSUMPTION COMB** (lit/100 km) e.g. 9.2
- **CO2 EMISSIONS (g/km)** e.g. 182   --> low --> 0
