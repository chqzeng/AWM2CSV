# AWM2CSV
This is a project to convert DJI flight log file (waypoints) from its AWM (xml) format to a readable format(csv table); It also provides the function to inversely input a CSV file of coordinates from other software(e.g. GoogleEarth) to better plan the flight in advance.  

Please download and run the .exe file under commandline mode in Windows platform, and use the ```test.awm``` and ```test.csv``` for test purpose.  

Author: Chuiqing Zeng; Carleton Unversity; Ottawa, Canada; chzeng@gmail.com

Usage: ```AWM2CSV -i input_file_path [-o output_file_path] [-r true/false] [-h]```
Options:
```
  -i, --input=INPUT     The INPUT path of the DJI UAV flight log file (*.awm)
  -o, --ouptut=OUTPUT   The OUTPUT path of the generated CSV file of the ways points. If no output file is assigned, then the program will automatically generate the resultant file in the same folder (with different extension)
  -r, --reverse=false   Indicate it is the reverse procedure by inputing   the CSV and need to convert to a AWM file,  Need to switch the input/output data format  when it is true.[default is false]
  -h, --help            Show this message and exit
```
