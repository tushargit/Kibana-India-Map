# Kibana-India-Map
Adding Indian states on kibana map
==================================

*  sudo gedit /var/www/kibana/app/panels/map/editor.html
   add india in list as shown editor.html
*  Download and paste map.india.js present in this repository at /var/www/kibana/app/panels/map/lib/
*  Open kibana add map panel 
        *1)In map, select india 
        *2)In the field ,write geoip.real_region_name
        *3) save


