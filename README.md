# Project Name
>  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company wants to identify the key factors that can lead to increase in the bike users.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- The company wants to know:
   Which variables are significant in predicting the demand for shared bikes.
   How well those variables describe the bike demands

- The datset contains informations from BoomBikes for the Year 2018 and 2019.


## Conclusions
Year 2019 has the highest number of bike rentals
Fall has highest average followed by summer
Months in Q3 has almost same number of bike rentals
Bike rentals are more in working days compared to holidays

Variables significant in predicting the demand
                                                                   
yr                                                                                         
holiday                                                                                   
temp                                                                                       
windspeed                                                                                 
spring                                                                                    
winter                                                                                     
DEC                                                                                       
JAN                                                                                       
JULY                                                                                      
NOV                                                                                       
SEP                                                                                        
SUN                                                                                       
Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds   
Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist                              

Equation will be 
0.2992 + 0.2349 * yr -0.09885 * holiday + 0.3988 * temp -0.1539 * windspeed  -0.1037 * spring + 0.0651 * winter -0.0522 * DEC -0.0572 * JAN -0.0620 * JULY -0.0485 *NOV + 0.0519 * SEP -0.0494 * SUN -0.29964 * Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds  -0.0818 * Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist



## Technologies Used
library pandas == 1.5.3
library numpy  == 1.24.4
library seaborn == 0.13.2
library matplotlib == 3.5.3




## Contact
Created by [@VKVishnuVinod] - feel free to contact me!
