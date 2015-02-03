# Kibana-India-Map
Adding Indian states on kibana map
==================================

*  sudo gedit /var/www/kibana/app/panels/map/editor.html
   add india in list as shown editor.html
*  Download and paste map.india.js present in this repository at /var/www/kibana/app/panels/map/lib/
*  Open kibana add map panel 
    - In map, select india 
    - In the field ,write geoip.real_region_name
    - save
    -  ![alt tag](https://github.com/tushargit/Kibana-India-Map/blob/master/configure_india_map.png)
       ![alt tag](https://github.com/tushargit/Kibana-India-Map/blob/master/kibana_India_Map.png)


