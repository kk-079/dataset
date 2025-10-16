# dataset
it is used for LoRa Link Path Loss estimation
Experimental site: Shenzhen University, Shenzhen, Guangdong, China

Gateway locations: 
Shenzhen University Science and Technology Building rooftop (G1),
2nd Floor, Science and Technology Building (G2),
Zhili Building rooftop (G3),
Zhili Building ground floor (G4),
Ziweizhai rooftop (G5)

CSV file information: RSSI, SNR, longitude, latitude, and altitude
RSSI and SNR can be used to calculate the "Expected Signal Power (ESP)" metric defined by LoRa.
Longitude, Latitude can be mapped to pixels on the image of the study area.
Height can be used as auxiliary information to input into the deep learning model to better learn link characteristics
