# golden_opp is currently under development 

# Golden Hour Times (golden_opp)

This Python script calculates and displays the morning and evening golden hour times for a specified location and date range. It supports multiple languages and time zones, making it a versatile tool for photographers, filmmakers, and anyone interested in capturing the beauty of golden hour light.


## Features

- **Calculates Golden Hour Times:** Accurately determines the start and end times of the morning and evening golden hours based on the sun's position.
- **Multilingual Support:** Provides output in English, French, German, Spanish, and Russian.
- **Customizable Location:** Allows users to specify the city, country, and time zone for their desired location.
- **Date Range:** Starts calculations from a specified date (default: April 9, 2025) and increments daily until interrupted.
- **User-Friendly Interface:** Provides clear prompts for input and displays results in a readable format.
- **Easy to Interrupt:** Runs continuously until the user presses `CTRL+C`, allowing for flexible control.


## Requirements

- **Python 3.6 or higher:** Make sure you have a compatible version of Python installed on your system.
- **Required Libraries:** 
    - `astral`
    - `pytz`
    
You can install these libraries using `pip`:
bash pip install astral pytz

## Usage

1. **Clone the repository:** bash git clone
2. **Navigate to the project directory:** bash cd golden_opp
3. **Run the script** bash python golden_opp.py
4. **Follow the prompts:**
   - Select your desired language.
   - Enter the city, country, and time zone for your location.

5. **View the results:**
   - The script will display the golden hour times for each day, starting from the specified date.
   - Press `CTRL+C` to stop the script.


## Example Output
Available languages: English (en), French (fr), German (de), Spanish (es), Russian (ru) Select language (default 'en'): en Enter city name (e.g., New York): New York Enter country name (e.g., USA): USA Enter timezone (e.g., America/New_York): America/New_York

Golden Hour Times for New York, USA (Timezone: America/New_York) Press CTRL+C to stop.

Date: 2025-04-09 Morning Golden Hour: 06:30:12 to 07:30:12

Evening Golden Hour: 18:45:55 to 19:45:55
Date: 2025-04-10 Morning Golden Hour: 06:28:45 to 07:28:45

Evening Golden Hour: 18:46:58 to 19:46:58
[Press CTRL+C to stop]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Acknowledgments
- The `astral` library for providing accurate sun position calculations.
- The `pytz` library for handling time zones.
- Code developed by Grok AI
- Read me developed by Google Gemini AI
- edited and tweaked by wifiknight45
