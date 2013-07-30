## Enigma Virtual Box Extractor

### Overview
It is a tool to extract the files from the file container made ​​using the program [Enigma Virtual Box](http://enigmaprotector.com/en/aboutvb.html)

## Features
 * shows the information of options with which to make the file
 * extract not compressed file

### RoadMap
 * extracting compressed files
 * extracting registry
 * extracting containers

### Usage
**Tested only on Python 2.7.3**

`python evbe.py [-h] [-e] [-o output_directory] file`

Shows the information of options with which to make the file:

`python evbe.py file`

Extract data:

`python evbe.py -e file`

Extract data to custom directory:

`python evbe.py -e file -o directory`

### License
`evb-extractor`'s code uses the MIT license, see `LICENSE` file.
