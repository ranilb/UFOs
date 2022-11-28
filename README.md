# UFOs

## Overview of the UFO
This analysis was performed on Unidentified Flying Objects (UFOs) data to visualize information. The data was stored in a JavaScript arry. The analysis was 
extended to filter data according to the use-input such as city, state, counry and the shape of the UFOs.

### Resources
Data source: data.js

Software: JavaScript, HTML & CSS and Bootstrap

## UF Analysis Results
The main goal of this analysis was to extract data from a JavaScript file and show them in webpage using a HTML table. Further more, imporve the webpage 
so that users can fillter the data according to their requirements.  The data was stored as objects in JavaScript object. The following image shows an example of 
one object in the data file.

  <img width="475" alt="Screen Shot 2022-11-28 at 5 07 28 PM" src="https://user-images.githubusercontent.com/112113327/204391305-5b7735de-5861-4868-9036-3018bf132044.png">

The JaveScript object in the preceding image is very similar to a dictionary in python. Keys are "datetime", "city', "state', "country", "shape", "durationMinutes"
and "comments". First, data from the JavaScript file was converted to a HTML table and displayed on the webbrowser. The image is shown bellow.

  ![Screen Shot 2022-11-28 at 5 33 24 PM](https://user-images.githubusercontent.com/112113327/204395092-c26790c6-97de-4eb4-bea2-423f1a8b6167.png)

Seven observations of UFOs are displayed in the preceding image. It can be observed that the observations have different values other than the country. 
Therefore, the next step is to include filters so users can change their search criteria.

### Average Fare per Ride and the Average Fare per Driver


### Weekly Total Fare for each City Type
As the second step, the total fare for each city type was considered. Then, the "resample" function was used to determine the weekly fare for each city type. The weekly fares from January, 2019 to April 2019 were considered for each city type and plot the following line graph to visualize the information.

  ![PyBer_fare_summary](https://user-images.githubusercontent.com/112113327/195691444-08c531e8-3523-4cd8-91d2-e48b165c12dc.png)

From the preceding graph, it can be observed that the weekly fare in urban cities are very high compared to the rural cities. The total fares in suburban cities are higher than rural cities, but less than the urban cities. Another interesting to see here is that the total fares in urban and suburban cities decreased in January, but it increased in rural cities.


## PyBer Analysis Summary
According to the information extracted from the two data sets, there are more drivers in urban cities than in suburban and rural cities. This leads to the low average fare for the drivers in urban cities than the drivers in suburban and rural cites. On the other hand, the riders in urban cities get better rates due to higher number of drivers. Also, this may be due to short distances, but there is no data to compare the distances. In the graph of the "total fare by city type", the total fare for urban and suburban cities are lower at the begining of the uear. This may be due to seasonal effecs. Finally, the suburban cities are better for riders compared to the riders in rural cities and also better for drivers compated to the drivers in urban cities.
