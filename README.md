# Introduction

This project aims to identify the best location for a new company office considering various factors, including the proximity to other tech startups and design companies, airports, schools, Starbucks, restaurants with vegan options, a basketball court, and pet grooming services.

## Data Collection

To gather the necessary data, several sources were used, including a Mongo DB for the list of tech and design companies and Foursquare API for nearby venue information.

## Methodology

![UE](https://user-images.githubusercontent.com/127798793/237025438-2feddd2d-aeb0-41c6-99a8-e103ddc82d11.png)

![Europe](https://user-images.githubusercontent.com/127798793/237025449-3a5aea3a-d3af-4d11-8d00-2bb30b8ec817.png)

The project first identified the areas with the most tech and design companies, and it was found that UE and EU had the most concentration of companies. The analysis then focused on San Francisco and divided the city into two areas: San Francisco city center and nearby southern cities. The mean coordinates of the centers of the tech and design companies in each area were calculated, and the ideal location for the new office was found to be in the San Francisco city center.

Using the Foursquare API, the project identified nearby venues that met all the specified requirements. The final map was then created, showing the optimal location for the new office, nearby companies, and required amenities.

## Results

![Place of the new office](https://user-images.githubusercontent.com/127798793/237025214-f39a5f2f-6f49-41f0-9e21-eb1a761366d1.png)

The optimal location for the new office was found to be at coordinates [37.7824, -122.4039] in the San Francisco city center. This location satisfies all the specified requirements, including nearby airports, schools, Starbucks, restaurants with vegan options, a basketball court, and pet grooming services.


## Conclusion

This project successfully identified the optimal location for a new company office in San Francisco by considering several factors. The results show that the San Francisco city center is the best location for the new office, as it satisfies all the specified requirements and has the highest concentration of nearby tech startups and design companies.
