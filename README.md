# Collection-of-Indonesia-GeoJSON

Here are collection of Indonesia Adminisrative Area Geospatial Data that you can use as a template or base for your data visualization. I have used them in Metabase which I would explain below. 

All of this data is retrieved from this website, by April 2st, 2020:
data.humdata.org/dataset/wfp-geonode-indonesia-adminboundary

* Administrative Level 1 shows regional area in Province level
* Administrative Level 2 shows regional area in City/Municipality/Regency level
* Administrative Level 3 shows regional area in District level
* Administrative Level 4 shows regional area in Urban/Village level

To use this in Metabase, 
1. Import the zipped file which consists of these types of file (.cpg, .dbf, .prj, .shp, .shx) to https://mapshaper.org/
2. Make sure you import the right administrative level you want to use for your data visualization
3. Export them into GeoJSON format map file and download
4. Upload the map into your own Github account
5. Open your Metabase account and find Admin Settings
6. Paste the link of your GeoJSON format map file into Metabase and select the right tag/column as the identifier (better to use BPS code) and the display name
7. Click Save Map. Now is is ready to use!
8. If you want to select only several area of the map, for example only Bogor's district. You have to use additional GIS platform. You can use QGIS which you can download here: https://qgis.org/en/site/forusers/download.html# and follow the instruction here: https://mangomap.com/industries/web-mapping/tutorials/remove-unwanted-regions-from-map-data.html

That's all!
