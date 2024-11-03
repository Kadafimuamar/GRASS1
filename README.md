# GRASS - Auto Farming & Proxy Scraping Tool

**GRASS** is an automation tool designed for proxy scraping and auto-farming activities, ideal for scenarios requiring frequent proxy validation and WebSocket communication. The tool is easy to configure and allows for scheduled execution, providing efficient proxy management.

## Features

- **Proxy Scraping and Validation**: Automatically fetches and validates proxies from a specified source.
- **WebSocket Connection Support**: Establishes WebSocket connections via SOCKS5 proxies, enabling automated messaging and response handling.
- **Automated Scheduling**: Executes tasks automatically at specified intervals (default: every 24 hours).
- **Detailed Logging**: Enhanced logging with Loguru for tracking proxy statuses and WebSocket activities.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DonsPabloXYZ/GRASS.git
   cd GRASS
2. Install dependencies:
pip install -r requirements.txt
3. Run Script
python main.py

# Example Output
While the script runs, you'll see log outputs showing proxy statuses, WebSocket connection messages, and other scheduled task information.

# Troubleshooting
Invalid Proxies: Check that the proxy source is reliable and up-to-date.
Connection Timeouts: Adjust timeout settings if you experience frequent disconnections.

# Contact
For support or inquiries, reach out via Telegram:

@DonsPabloXYZ
@KelasMalamXYZ
