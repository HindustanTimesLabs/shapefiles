# Uttar Pradesh Districts

### Sources
- **uttarpradesh_district.ext** 75 districts (four were not included in the 2011 Census) scraped from [Shristi(GIS-UP)](http://gis.up.nic.in/srishti/election2017/). [View the scraper's repository](https://github.com/HindustanTimesLabs/up-shape-scrape).
- **uttarpradesh_district_2011.ext** 71 districts from the 2011 Census. Started with shapefile from [DataMeet](https://github.com/datameet/maps/tree/master/Survey-of-India-Index-Maps/Boundaries), then filtered only Uttar Pradesh districts using [mapshaper](http://mapshaper.org/).

### Delimitation
Some districts have been renamed since the 2011 Census was conducted.
- Amroha, renamed in 2012 from Jyotiba Phule Nagar. [[Source]](https://en.wikipedia.org/wiki/Amroha_district#History)
- Kasganj, renamed in 2012 from Kanshiram Nagar. [[Source]](https://en.wikipedia.org/wiki/Kasganj_district#History)
- Lakhimpur Kheri, renamed from just Kheri.

Four districts have been added to UP since the 2011 Census was conducted.

| district | created        | original_name                     | renamed   | carved_out_of            | source                                                                                                                      | 
|----------|----------------|-----------------------------------|-----------|--------------------------|-----------------------------------------------------------------------------------------------------------------------------| 
| Amethi   | July 2010      | Chhatrapati Shahuji Maharaj Nagar | 2012      | Sultanpur and Rae Bareli | [[Wikipedia]](https://en.wikipedia.org/wiki/Amethi_district#General_characteristics_of_the_district)                        | 
| Hapur    | September 2011 | Panchsheel Nagar                  | July 2012 | Ghaziabad                | [[Wikipedia]](https://en.wikipedia.org/wiki/Hapur_district#History)                                                         | 
| Sambhal  | September 2011 | Bhimnagar                         | July 2012 | Budaun and Moradabad     | [[Wikipedia]](https://en.wikipedia.org/wiki/Sambhal_district#Creation) [[Wikipedia]](https://en.wikipedia.org/wiki/Sambhal) | 
| Shamli   | September 2011 | Prabudh Nagar                     | July 2012 | Muzaffarnagar            | [[Wikipedia]](https://en.wikipedia.org/wiki/Shamli_district)                                                                | 

![UP district changes](https://raw.githubusercontent.com/HindustanTimesLabs/shapefiles/master/state_ut/uttarpradesh/district/img/uttarpradesh_district_changes.png "UP districts changes from 2011")

### To-do

Determine if the updated shapes of Bahraich and Shravasti are correct, or if there was an error in the Shristi(GIS-UP) shapefiles.

![Bahraich-Shravasti error](https://raw.githubusercontent.com/HindustanTimesLabs/shapefiles/master/state_ut/uttarpradesh/district/img/shristi_gis_up_bahraich_shravasti.png "Bahraich-Shravasti error")

On 25 August, 2017, I sent an email to the National Informatics Centre in Lucknow (support-up@nic.in):

>Greetings,
>
>I work for the Hindustan Times in New Delhi, India. I noticed what I believe is an error in the KML files of Uttar Pradesh districts on the Srishti(GIS-UP) map (http://gis.up.nic.in:8080/srishti/election2017/). Bahraich district seems to have subsumed a portion of Shravasti district to the east. I have attached a screenshot.
>
>Either Bahraich district actually grew since the 2011 Census, or your shapefiles are slightly incorrect. Please let me know what happened.
>
>Thank you and regards,
>Harry