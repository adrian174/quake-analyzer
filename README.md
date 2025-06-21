# 🌍 Quake Analyzer: Your CLI Tool for Earthquake Insights

![Quake Analyzer](https://img.shields.io/badge/Quake%20Analyzer-CLI%20Tool-brightgreen)

Welcome to the **Quake Analyzer** repository! This tool helps you analyze global earthquake data sourced from the US Geological Survey (USGS). With this command-line interface (CLI) tool, you can fetch, filter, find recurrence intervals, and visualize trends in earthquake data. 

[Download the latest release here!](https://github.com/adrian174/quake-analyzer/releases)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Fetch Earthquake Data**: Get real-time data from USGS.
- **Filter Options**: Narrow down results based on location, magnitude, and date.
- **Recurrence Intervals**: Calculate how often earthquakes occur in a specific area.
- **Data Visualization**: Create graphs and charts to visualize trends over time.
- **User-Friendly CLI**: Simple commands make it easy to navigate and use.

## Installation

To get started with Quake Analyzer, you need to install it on your machine. Follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/adrian174/quake-analyzer.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd quake-analyzer
   ```

3. **Install Dependencies**:
   Make sure you have Python installed. Then run:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   Execute the main script:
   ```bash
   python main.py
   ```

## Usage

Once you have installed Quake Analyzer, you can start using it right away. Here are some basic commands to get you started:

- **Fetch Data**:
   ```bash
   python main.py fetch --start-date YYYY-MM-DD --end-date YYYY-MM-DD
   ```

- **Filter by Magnitude**:
   ```bash
   python main.py filter --magnitude > 5.0
   ```

- **Calculate Recurrence Intervals**:
   ```bash
   python main.py recurrence --location "San Francisco"
   ```

- **Visualize Trends**:
   ```bash
   python main.py visualize --type "bar" --location "California"
   ```

You can always check the full documentation by running:
```bash
python main.py --help
```

## Data Sources

Quake Analyzer uses data from the **US Geological Survey (USGS)**. This ensures that you are working with reliable and up-to-date information. The data includes various parameters like:

- Magnitude
- Depth
- Location
- Time of occurrence

For more information on USGS data, visit the [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/).

## Contributing

We welcome contributions to improve Quake Analyzer. Here’s how you can help:

1. **Fork the Repository**: Click on the "Fork" button at the top right of this page.
2. **Create a New Branch**: 
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**: Add your feature or fix.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to the Branch**: 
   ```bash
   git push origin feature/YourFeature
   ```
6. **Create a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to reach out:

- **Email**: yourname@example.com
- **GitHub**: [YourGitHubProfile](https://github.com/YourGitHubProfile)

Thank you for checking out Quake Analyzer! We hope you find it useful in your earthquake analysis endeavors. Don't forget to [download the latest release here!](https://github.com/adrian174/quake-analyzer/releases) 

Happy analyzing! 🌟