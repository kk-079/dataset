# dataset
it is used for LoRa Link Path Loss estimation<br>
Experimental site: Shenzhen University, Shenzhen, Guangdong, China<br>

Gateway locations: 
Shenzhen University Science and Technology Building rooftop (G1),<br>
2nd Floor, Science and Technology Building (G2),<br>
Zhili Building rooftop (G3),<br>
Zhili Building ground floor (G4),<br>
Ziweizhai rooftop (G5)<br>

CSV file information: RSSI, SNR, longitude, latitude, and altitude<br>
RSSI and SNR can be used to calculate the "Expected Signal Power (ESP)" metric defined by LoRa.<br>
Longitude, Latitude can be mapped to pixels on the image of the study area.<br>
Height can be used as auxiliary information to input into the deep learning model to better learn link characteristics<br>
