# Dataset for LoRa link estimation


The data is collected on the campus of Shenzhen University, Shenzhen, Guangdong, China. G1, G2, G3, G4, and G5 are five gateways, which collect RSSI and SNR of packets transmitted from a series of devices.


Gateway Location (defined by its voxel(1m x 1m x 1m) Coordinates x, y, z): <br>
G1 (Roof, Science and Technology Building of Shenzhen University): (528, 764, 100)<br>
G2 (2nd Floor, Science and Technology Building of Shenzhen University): (528, 764, 40)<br>
G3 (Roof, Zhili Building): (1296, 1092, 84)<br>
G4 (Ground Floor, Zhili Building): (1296, 1092, 8)<br>
G5 (Roof, Ziweizhai Building): (632, 1068, 64)<br>


CSV file information: RSSI, SNR, longitude, latitude, and altitude.<br>
RSSI and SNR can be used to calculate the "Expected Signal Power (ESP)" metric defined by LoRa.<br>
The formula for calculating ESP is: ESP = RSSI + SNR - 10log10(1 + 10**0.1SNR).<br>
Longitude, Latitude can be mapped to pixels on the image of the study area.<br>
Height can be used as auxiliary information to input into the deep learning model to better learn link characteristics.<br>
