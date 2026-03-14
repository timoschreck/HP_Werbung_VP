# HomePlus Partner Acquisition Agent

This repository contains a Python script `agent.py` that provides a starting point for automating partner acquisition for HomePlus via LinkedIn.

## Overview
The agent is designed to:
- Authenticate with the LinkedIn API using your LinkedIn credentials.
- Search for potential partners based on keywords (e.g., "Energieberater", "Immobilienmakler") and locations (e.g., "Germany").
- Send personalized connection invitations or messages.
- Track responses and maintain a local record.

## Setup
1. Clone the repository and create a virtual environment.
2. Install dependencies (for example, a LinkedIn API client library such as `linkedin_v2`) using pip.
3. Obtain your LinkedIn API credentials (Client ID, Client Secret, and Access Token) and set them as environment variables:
   ```bash
   export LINKEDIN_CLIENT_ID=your_client_id
   export LINKEDIN_CLIENT_SECRET=your_client_secret
   export LINKEDIN_ACCESS_TOKEN=your_access_token
   ```
4. Open `agent.py` and replace the placeholder `TODO` parts with actual LinkedIn API calls and error handling.

## Usage
Run the script using Python:

```bash
python agent.py
```

By default, the `main()` function authenticates with LinkedIn, searches for leads matching "Energieberater" in Germany, and sends connection invitations with a basic introduction message. You can customize the keywords, location, and message in the `main()` function or extend the script to read these values from a configuration file or command-line arguments.

## Disclaimer
This project is a proof of concept and does not constitute an official LinkedIn integration. Ensure you comply with LinkedIn's terms of service and respect recipient privacy when using the LinkedIn API.
