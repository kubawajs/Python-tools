# Olx-room-scrapper

Simple scrapper for popular polish website with ads with flats/rooms for rent.

![alt example file](https://github.com/kubawajs/Python-scrappers/raw/master/olx-rooms-scrapper/example.PNG)

## Usage

```
python ./olx-rooms-scrapper.py -c <city_name> -n <number_of_offers> -o <output_file_name>
# all parameters are optional
```

## Libraries used

* Beautiful Soup
* CSV
* Sys
* getopt
* time
* datetime
* Requests

## DONE

* move city to parameter
* move result file name to parameter
* pagination
* add timestamp to default file name
* added support for scrapping without specified city

## TODO

* FEATURE: optimization and saving the file on the fly
* FEATURE: progress bar instead printing processing files
* better tests
* better documentation
* refactoring
* BUGFIX: showing some columns as dictionary instead of common strings