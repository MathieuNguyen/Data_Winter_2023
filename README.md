# Data_Winter_2023
The repositery is divided into 3 separate .csv files. These files are used in the paper titled "Exploring Imaging Methods for in-situ Measurements of the Visual Appearance of Snow". The methods of acquisition are described in this paper for all physical correlates. The data either collected or generated from the processing algorithms is shared so that other people can use them.

- optical_properties.csv.
The data of this file was collected with the translucency meter DiaStron TLS850, and the inversion method to obtain absorption and reduced scattering coefficients is decribed in the paper. The .csv file contains the following columns:
  - Day: it states the day number with day 1 being 9.2.2023 (Februarry 9th).
  - Abs R: value of the absorption coefficient for the Red channel (unit mm^{-1}).
  - Abs G: value of the absorption coefficient for the Green channel (unit mm^{-1}).
  - Abs B: value of the absorption coefficient for the Blue channel (unit mm^{-1}).
  - Sca R: value of the reduced scattering coefficient for the Red channel (unit mm^{-1}).
  - Sca G: value of the reduced scattering coefficient for the Green channel (unit mm^{-1}).
  - Sca B: value of the reduced scattering coefficient for the Blue channel (unit mm^{-1}).
  - Label Snow: type of the snow from which the data was collected from.

- sparkle.csv.
Data from the sparkle study of 2023 is collected in this file. The two indicators to describe sparkle, contrast and density of sparkle spots, are in this file. They were computed for 1033 digital snow images. The .csv file contains the following columns:
  - Day: it states the day number with day 1 being 9.2.2023 (Februarry 9th).
  - Contrast: it gives the value of the contrast indicator computed.
  - Density: it gives the value of the density indicator computed.
  - Label Snow: type of the snow from which the data was collected from.
 
- temperature.csv.
This file reports the temperatures for each day of the field campaign. As mentioned in the paper, the temeprature were recorded from the website yr.no. The .csv file contains the following columns:
  - Day: it states the day number with day 1 being 9.2.2023 (Februarry 9th).
  - Average Temperature: average temperature of the day (unit °C).
  - Minimum Temperature: minimum temperature of the day (unit °C).
  - Maximum Temperature: maximum temperature of the day (unit °C).
  - Label Snow: type of the snow from which the data was collected from.

- temperature_hourly-resolution.csv.
This file report the temperatures for each day of the field campaign with an hourly resolution. Records of temperatures starts from 12am (00:00) until 11pm (23:00).
  - Day: it states the day number with day 1 being 9.2.2023 (Februarry 9th).
  - Temperature: temperature on the hour (unit °C).
  - Label Snow: type of the snow from which the data was collected from.
