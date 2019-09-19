
https://www.ems2019.eu/plenaries_and_events/python_workshop.html

# Python: Machine Learning applications for weather-related problems
# Training Workshop, 8 September 2019, Copenhagen

- Welcome to the workshop repository. We recommend you clone and follow the instructions in this README file before the workshop day.

- It is also recommended that you configure a virtual environment for this project. The most efficient way to install is to use to `conda` tool:
  - Install anaconda **Python 3.7 version** for your system (if you don't have it already): https://www.anaconda.com/distribution/#download-section
  - create a new environment:
    - `conda create -n ml_workshop python=3.7 anaconda`
  - activate the env you just created:
    - `conda activate ml_workshop`
  - install the necessary packages for this course using the `prepare.sh` script:
    - `chmod +x prepare.sh; ./prepare.sh`

  - After installing all libraries, make an account on [Climate Data Store](https://cds.climate.copernicus.eu/#!/home). You will also need to install the CDS API key (instructions are [here](https://cds.climate.copernicus.eu/api-how-to))

- The content of this repo is organized in the following directories:

```
  Data\
     Weather\ - weather data (see link below)
     Energy\ - csv used in renewable energy exercises
     Tourism\ - csv used for the tourism exercises

  CDSAPI_examples.ipynb
  Manipulating meteorological data.ipynb   
  ML – Part 1.ipynb
  ML – Part 2.ipynb

  README
  LICENSE
  requirements.txt
```

- Some of the weather data files that will be used in the exercises are bigger than GitHub's filesize limit, you can download them in a separate link. Please save these files in the `data\weather` directory:

  https://meteogroup.box.com/v/workshop-input-data

  - era5_EU_monthly.nc : Weather data for the Machine Learning 1st exercise
  - era5_DE_hourly_YYYY.nc : Weather data for the Machine Learning 2nd exercise
