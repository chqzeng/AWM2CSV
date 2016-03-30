# AWM2CSV
This is a project to convert DJI flight log file (waypoints) from its AWM (xml) format to a readable format(csv table); It also provides the function to inversely import coordinates from other software(e.g. GoogleEarth) to an AWM file, in order to better plan the flight in advance.  

Please download and run the .exe file under commandline mode under Windows platform, and use the ```test.awm``` and ```test.csv``` in the directory for test purpose.  

Author: [Chuiqing Zeng](http://chuizeng.ca); Carleton Unversity; Ottawa, Canada; chzeng@gmail.com

Usage: ```AWM2CSV -i input_file_path [-o output_file_path] [-r true/false] [-h]```  

Options:
```
  -i, --input=INPUT     The INPUT path of a DJI UAV flight log file (*.awm)
  -o, --ouptut=OUTPUT   The OUTPUT path of the generated CSV file. If no output file is assigned, then the program will automatically generate a file in the same folder (with a .csv extension)
  -r, --reverse=false   Indicate if it is the reverse procedure: inputing the CSV and need to convert to an AWM file. Need to switch the input/output data format when it is true.   [default is false]
  -h, --help            Show this message and exit
```
