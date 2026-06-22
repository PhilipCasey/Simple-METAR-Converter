# Simple METAR Decoder - PowerShell

A PowerShell script that retrieves raw METAR aviation weather reports and converts them into a readable weather summary.

## Example Output

```text
Input desired airport: KCHS

Raw METAR:
METAR KCHS 221356Z 26005KT 10SM SCT015 28/23 A3002 RMK AO2 SLP166 T02780233

Decoded Output:
Time                9:56 AM EDT
Wind                260° at 5 kts
Visibility          10+ sm
Clouds (AGL)        Scattered 1500'
Temperature         28°C (82°F)
Dewpoint            23°C (74°F)
Altimeter           30.02 inHg
Humidity            77%
Density Altitude    1,448'
```

## Features
- Retrieves METAR data from the Aviation Weather Center API
- Parses wind, visibility, cloud layers, temperature, dewpoint, altimeter, humidity, and density altitude
- Supports cached XML data to reduce unnecessary API calls
- Formats aviation weather data into a cleaner, pilot-readable output

## Why I Built It
I built this project to practice PowerShell data parsing, API interaction, and aviation weather interpretation while creating a useful tool for pilots.
