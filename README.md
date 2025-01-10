# WhatsApp Chat Analyzer

A Python-based tool for analyzing WhatsApp chat exports. This application processes and visualizes chat data to help users understand their messaging habits and interactions.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Visualization](#data-visualization)
- [Contributing](#contributing)
- [License](#license)

## Features

- Analyze message frequency over time
- Identify top contacts and groups
- Mood analysis based on keywords
- Generate visual reports including graphs and charts
- Export analysis results to CSV/JSON files

## Installation

To set up the project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/whatsapp-chat-analyser.git
   cd whatsapp-chat-analyser
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Export chat from WhatsApp:

Open the chat you want to analyze.
Tap on the menu icon and select "More" > "Export chat".
Choose to export "Without media" for a cleaner analysis.
Run the analyzer:

bash
Copy code
python main.py path/to/your/chat.txt
View the results:

After running the analysis, the results will be saved in the output directory.
Open the generated reports to view insights and visualizations.
Data Visualization
The tool generates various plots and charts to help visualize data:

Message Counts: A line chart showing messages over time.
Top Contacts: A bar chart of the most frequent contacts.
Sentiment Analysis: Pie chart representing sentiment distribution (if implemented).
Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch (e.g., feature/your-feature).
Make your changes and commit them.
Push to your branch and submit a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Inspired by various open-source chat analysis tools.
Thanks to the contributors of the libraries used in this project.
Copy code

**Note**: Be sure to replace `yourusername
