## What
A simple demonstration of how to use the [mbed-connector-api-python](https://github.com/ARMmbed/mbed-connector-api-python) module to grab values from devices connected to [mbed connector](https://connector.mbed.com) and log them to an excel file. 

## How to use
1. Install requirements with `pip install -r requirements.txt`
2. Replace the `API_KEY`, `endpointName`, and `resourceName` variables in the script with your [API Key](https://connector.mbed.com/#accesskeys), and the names of the endpoint/resource you are trying to log. 
3. Run the script with `python script.py`
4. A `results.xlsx` file with the log will be generated in the same directory as the `script.py` file

## License
Apache 2.0
