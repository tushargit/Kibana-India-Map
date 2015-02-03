# Kibana-India-Map
Adding Indian states on kibana map
==================================

*  sudo gedit /var/www/kibana/app/panels/map/editor.html and 
   add 'india' in list as shown  in editor.html
*  Download and paste map.india.js present in this repository at /var/www/kibana/app/panels/map/lib/
*  Open kibana add 'map' panel 
    - In 'map', select india 
    - In 'field' ,write geoip.real_region_name
    - save
    -  ![alt tag](https://github.com/tushargit/Kibana-India-Map/blob/master/configure_india_map.png)
       ![alt tag](https://github.com/tushargit/Kibana-India-Map/blob/master/kibana_India_Map.png)


