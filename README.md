# heatmap
python based webpage to allow a user to upload csv with zip codes and metric of some sort and page will render heatmap

requirements:
1) simple web page written in python inside docker container that allows a user to upload a csv file with two columns: zip code and some metric.  
2) page should read data, automatically determine scale based on range of values in metric column, and then generate a heatmap file which it returns to user as image file.
-->Here is a very relevant code example written in python: https://sensitivecities.com/so-youd-like-to-make-a-map-using-python-EN.html#.W7u6QhNKjVq
-->And this may be resource for valid us zip code shape file: https://www.census.gov/geo/maps-data/data/cbf/cbf_zcta.html

3) ideally write using flask microservice and docker container

