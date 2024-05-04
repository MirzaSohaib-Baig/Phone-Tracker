# Phone Number Tracker

## Introduction

This Python script allows you to track the approximate location of a phone number, along with additional details such as the time zone, region, and service provider. It utilizes libraries such as `phonenumbers`, `colorama`, `dotenv`, and `opencage.geocoder`.

## Requirements

Before using the script, make sure you have the following installed:

- Python 3.x
- Required Python libraries (install via pip):
  - phonenumbers
  - colorama
  - dotenv
  - opencage

## Setup

1. Clone or download the script to your local machine.
2. Navigate to the directory where the script is located.
3. Install the required Python libraries if you haven't already:

```bash
pip install phonenumbers colorama python-dotenv opencage
```

4. Obtain an API key from OpenCage:

   - Visit [OpenCage Geocoding API](https://opencagedata.com/api) and sign up for an account.
   - After signing up, you'll receive an API key. Keep this key secure.

5. Create a `.env` file in the same directory as the script.
6. Add your OpenCage API key to the `.env` file:

```
KEY=your_opencage_api_key_here
```

## Usage

To use the script, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory containing the script.
3. Run the script with Python, specifying the phone number you want to track:

```bash
python phone_tracker.py -p +1234567890
```

Replace `+1234567890` with the phone number you want to track, including the country code.

**Note:** Ensure that you include the country code when specifying the phone number.

## Output

The script will provide information about the tracked phone number, including its approximate location, time zone, and service provider. Additionally, it will generate an HTML file displaying the aerial coverage of the location.

## Disclaimer

- Use of this script should be in compliance with all applicable laws and regulations.
- Obtaining consent from the owner of the phone number is advisable before tracking.
- This script should not be used for illegal or unauthorized activities.

## Troubleshooting

- If you encounter any issues with the script, ensure that you have provided a valid phone number with the country code.
- Check your internet connection to ensure that the script can retrieve location information from the OpenCage API.
