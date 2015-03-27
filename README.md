Indian Village Boundaries
=========================

"The village is the cell of the national body and the cell-life must be healthy and developed for the national body to be healthy and developed." - Sri Aurobindo (During his speech on the Palli Samiti resolution at Kishoregunj). To track and assess development of our country, its important to understand the pace of development in our villages. In order to do so, many of the data do-gooders, non-profits, activists, designers and journalists struggle a lot to get Indian village boundaries in a clean machine consumable form. Here is beginning of an attempt to open Indian village boundaries consolidated at one place, currently this contains data for 12 Indian states namely Andhra Pradesh, Assam, Bihar, Gujarat, Haryana, Jharkhand, Karnataka, Kerala, Madhya Pradesh, Maharashtra, Rajasthan, West Bengal.

##Data Format
Data is currently maintained in [CSV](http://en.wikipedia.org/wiki/Comma-separated_values) format compressed using [XZ](http://en.wikipedia.org/wiki/Xz) and geometery of villages being in [WKT](http://en.wikipedia.org/wiki/Well-known_text) format. 

##Data Dictionary

1. **village_id**: Unique ID for the village
2. **village_name**: Name of the village
3. **village_descriptive_name**: Descriptive name of village of following format ( Village - Block - District- State Code ) 
4. **village_census_code**: Village census code according to 2011 Census of India
5. **panchayat_name**: Name of the panchayat
6. **panchayat_code**: Unique ID for the panchayat 
7. **block_code**: Unique ID for block
8. **block_name**: Name of the block
9. **district_name**: Name of the district
10. **district_code**: Unique ID for the district
11. **district_census_code**: District census code according to 2011 Census of India
12. **state_name**: Name of the state
13. **state_code**: Unique ID for the state
14. **state_census_code**: State census code according to 2011 Census of India
15. **geometery_in_wkt**: Geometery of the village in WKT(Well-known Text) format
16. **centroid_latitude**: Latitude value of centroid of the village geometery  
17. **centroid_longitude**: Longitude value of centroid of the village geometery   
  
## Author

**Gaurav Godhwani**
Technologist, data nerd, NGO lover, polyglot programmer, doing Data-for-Good at [DataKind Bangalore](http://www.datakind.org/howitworks/datachapters/datakind-blr/) and working for child welfare at [Orenda Initiatives](http://www.orendainitiatives.org/).
- <https://github.com/gggodhwani>
- <https://twitter.com/gggodhwani>
