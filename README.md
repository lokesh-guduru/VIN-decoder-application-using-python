# VIN Decoder
This is a Python application for decoding Vehicle Identification Numbers (VINs) using the National Highway Traffic Safety Administration (NHTSA) API. The application allows users to select an Excel or CSV file containing VINs, choose the column containing the VINs, and decode the VINs using the NHTSA API. The application outputs a new CSV file containing the original data plus additional columns with decoded information.

## Requirements
Python 3.6 or later,
PyQt5,
pandas,
requests

## Installation
1. Install Python 3.6 or later on your system.
2. Install PyQt5, pandas, and requests using pip. You can use the following command: pip install PyQt5 pandas requests.
3. Download or clone the source code from this repository.

## Usage
1. Open a terminal or command prompt.
2. Navigate to the directory containing the source code.
3. Run the application by executing the following command: python vin_decoder.py.
4. In the application window, click the "Select File" button to choose an Excel or CSV file containing VINs.
5. Select the column containing the VINs from the drop-down menu.
6. Click the "Decode" button to decode the VINs using the NHTSA API.
7. Save the output file by selecting a file name and location in the file dialog.

## Credits
This project was created by me as a part of VIN Decoding project at **Center for Urban Transportation Research (University of South Florida)**.

If you use this project or any part of its code, please make sure to credit the author and provide a link to the source code repository.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
