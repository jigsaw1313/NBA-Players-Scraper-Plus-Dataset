
# Basketball Players Information Scraper

## Overview

This Python script allows you to scrape detailed information about basketball players from basketball-reference.com. It iterates through the alphabet, collecting data for players whose last names start with each letter ('a' to 'z').

## Dependencies

- Python 3.x
- Requests
- BeautifulSoup
- Pandas

Install the required dependencies using:

```bash
pip install requests beautifulsoup4 pandas
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/basketball-players-scraper.git
```

2. Navigate to the project directory:

```bash
cd basketball-players-scraper
```

3. Run the script:

```bash
python scrape_players.py
```

The script will create a CSV file named `basketball_players_data.csv` containing player information.

## Code Structure

- `scrape_players.py`: The main script for scraping player information.
- `requirements.txt`: Lists the required Python packages.

## Contribution

Contributions are welcome! If you find any issues or want to enhance the functionality, feel free to create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Make sure to replace "your-username" with your actual GitHub username in the clone command. Additionally, if you have a specific license for your project, replace "MIT License" with the appropriate license name and provide the corresponding license file (`LICENSE`).