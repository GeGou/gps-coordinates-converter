# GPS-coordinates-converter
Converts coordinates (latitude, longitude) to location and creates a device_tracker entity

Add the following to configuration.yaml:

gps_coordinates_converter:
  latitude_sensor: sensor.esp32_NEO-6M_GPS_Module_latitude 
  longitude_sensor: sensor.esp32_NEO-6M_GPS_Module_longitude
