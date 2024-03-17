# Redoc CityBikes API Documentation

--> View the documentation [here](https://kchonka.github.io/citybikes-api-docs/).


This API documentation explains how to use the CityBikes API for developers. 


It leverages Redoc to enhance the 
[existing documentation](https://api.citybik.es/v2/) by elaborating 
on all avaliable endpoints, requests and responses, schemas,
error codes, authentication requirements, and examples. 


[CityBikes](https://www.citybik.es/), powered by 
[PyBikes](https://github.com/eskerda/pybikes), 
is an open-source project providing information about global 
bike-sharing transportation services. 

*This project is intended for educational purposes.*

## Local Commands

These are to be run from the root directory.

1. To merge all your standalone files into a single definition file called bundled.yaml 
in the openapi directory: 

`redocly bundle openapi/openapi.yaml --output openapi/bundled.yaml`

2. To preview the documentation locally:

`redocly preview-docs openapi/bundled.yaml --config redocly.yaml`

3. To create a dist.json file in the docs directory for documentation that can be deployed online:

`redocly bundle openapi/openapi.yaml -o docs/dist.json`