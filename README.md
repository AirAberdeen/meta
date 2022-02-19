# AirAberdeen 

Air Aberdeen are a collective of people interested in using sensors to measure air quality across Aberdeen and the surrounding area. Working with Sensor.Community we contribute to a global sensor network that creates Open Environmental Data.

This project holds project plans, meetings and some overview documents

For details information on specific subjects you check out the [wiki](https://github.com/AirAberdeen/meta/wiki).

## Useful Links

- **[Air Aberdeen Website](https://www.airaberdeen.org/)**
- **[Official AirAberdeen Github](https://github.com/AirAberdeen)**
- **[Sensor Community](https://sensor.community/)** (this used to be Luftdaten)
- **[Sensor Community Forum](https://forum.sensor.community/)**
- **[Sensor Community Mattermost](https://chat.sensor.community/)** (an opensource alternative to Slack)
- **[Sensor Community Archive](http://archive.sensor.community/)** (CSV archives of sensor data)
- **[AirTable Database of Devices](https://airtable.com)** (this is private to the steering group)

## Active projects

#### JSON data scraper and Google Cloud importer by Bruce Schalau

This is in a private repo just now, but please get in touch if you think you can help.

## Previous projects

#### Data Gathering project by Gavin Barnett
https://github.com/AirAberdeen/CTC16-Data-Gathering

This project scrapes data from the sensor.community page and downloads it in JSON format. 


## Data

Data is pushed from sensors directly to [Sensor.community](https://sensor.community) and is displayed on their [maps](http://maps.sensor.community). This data is only stored for a short time. With this in mind one of our key projects is to create long term storage for Aberdeen City and Shire sensors, and to provide an API that can be used to serve that data to anybody wishing to use it.

### Example data

[A JSON file containing](https://github.com/AirAberdeen/meta/tree/master/examples/data) 24 hours of sensor data from several Aberdeen sensors is available in the repo for you to test with.

```JSON
{
    "humidity": "99.90",
    "latitude": "57.150",
    "location_id": "11991",
    "longitude": "-2.134",
    "sensor_id": "23629",
    "sensor_type": "DHT22",
    "temperature": "13.70",
    "timestamp": "2021-07-31T00:02:21"
}
```

### How much data is there?

To give an idea of data sizes, 2 sensors across 2.5 years totalled ~300mb in a MongoDB database. The example JSON file provided totals 5.3MB.
We are currently looking for a hosting option to store this data longterm.


## Contributors

People who have contributed and are happy to be contacted:

- [Alan Gardner](https://github.com/urfolomeus)
- [Bruce Scharlau](https://github.com/scharlau)
- [Gavin Barnett](https://github.com/gavbarnett)
- [Ian Nebbiolo](https://github.com/mrnebbi)
- [James Littlejohn](https://github.com/aboynejames)
- [Kevin Mulhern](https://github.com/KMulhern-A)


## Inventory

We have a number of sensors, kits, and other equipment available for running workshops.

For details of our current inventory, please visit our [wiki](https://github.com/AirAberdeen/meta/wiki).
