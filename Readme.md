This folder contain a virtual environment with python 3.11.9 version to extract the data inserted by Gaetan in the new format and convert it to a json messge to be sent using MQTT mosquitto broker.

1. testpy is the python virtual environment.

2. edf2ascii.exe is used to extract the data inside the STR.edf and insert it on the STR_data.txt file.

3. requirements.txt list the major python libraries to be installed using pip. 

4. Canomed_OldFormat contains data in the old format very similar to that one used by the S10.

5. Canomed_NewFormat contains data in the new format propossed by Gaetan. 

NOTE:
Here is not clear for me the change in the number of sections. Moreover, in the s10 format for a maskon-masoff the number of sections was counted as 2; what meas that if in the night the machine was used two times it will have 2 maskon and 2 mas off having the number of section counted as 4. The first two maskon-maskoff were inserted in the main long data line wile the others were listed up to 10 sections after the main sata line.

What I may see now is that the number of section changed to 2 when the machine is used two times in the night. With the first maskon-maskoff still in the main long data line and the secon inside one of the 10 slots. 

THIS NEED TO BE CLARIFIED  BY GAETAN. 