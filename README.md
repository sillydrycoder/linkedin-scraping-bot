# LinkedIn Scraping Bot

![License](https://img.shields.io/github/license/tensor35/linkedin-scraping-bot?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/tensor35/linkedin-scraping-bot?style=flat-square)
![Python](https://img.shields.io/badge/python-v3.8+-blue.svg?style=flat-square)

This repository contains a powerful and configurable scraping bot specifically designed for LinkedIn. The bot is capable of gathering job listings and extracting detailed contact information for key roles within US-based companies that are looking to hire remote software engineers, DevOps, and full-stack developers.

## Features

- **Targeted Scraping:** Collects job postings for remote positions from US companies, including job title, job description, offered salary, and more.
- **Role-Specific Contact Information:** Extracts contact details for key positions such as VP of Engineering, Engineering Manager, CTO, and more.
- **Data Sources:** Leverages LinkedIn job postings and company pages.
- **Anonymity:** Implements advanced proxy management to avoid detection and ensure continuous scraping.
- **Scalability:** Designed to handle large-scale scraping operations efficiently.

## How It Works

1. **Data Collection:**
   - The bot crawls LinkedIn to gather job postings that match the specified criteria (e.g., remote software engineering roles in the US).
   - For each job posting, the bot extracts details such as the company name, job title, job description, salary, and LinkedIn page URL.

2. **Contact Information Extraction:**
   - The bot identifies and collects contact information for specific roles (e.g., VP of Engineering, CTO) associated with the job postings.
   - Data points include the contact's name, job title, email, phone numbers, and LinkedIn profile URL.

3. **Proxy Management:**
   - Utilizes rotating residential or mobile proxies to maintain anonymity and reduce the risk of being blocked by LinkedIn.

4. **Data Engineering:**
   - The collected data is processed and organized into a structured format, making it easy to analyze and utilize.

## Setup

### Prerequisites

- **Python 3.8+**
- **LinkedIn API Access** (if applicable)
- **Proxy Service Subscription** (e.g., residential or mobile proxies)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/tensor35/linkedin-scraping-bot.git
   cd linkedin-scraping-bot
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure your environment variables:
   - Set up your LinkedIn credentials and proxy settings in a `.env` file:
     ```
     LINKEDIN_USERNAME=your_username
     LINKEDIN_PASSWORD=your_password
     PROXY_URL=your_proxy_service_url
     ```

### Usage

1. Run the bot:
   ```bash
   python linkedin_scraping_bot.py
   ```

2. The bot will start collecting job postings and contact information according to the parameters defined in the configuration.

3. Data will be saved in the `output/` directory in CSV format.

### Customization

- **Job Filters:** Modify the search criteria in the configuration file to target specific job roles, locations, or other parameters.
- **Proxy Settings:** Adjust proxy settings based on your subscription to optimize scraping efficiency.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## Contact

For any inquiries or issues, please contact the repository owner:

- **Developer:** [Muhammad Ali](https://github.com/tensor35)

## Related Projects

- [iCloud Mail Generator](https://github.com/tensor35/icloud-mail-generator)
- [Outlook and Reddit Bot Creator](https://github.com/tensor35/reddit_bot)
- [Judicial Scraper (Collaboration with Justice Bar Officials)](https://github.com/tensor35/judicial_records_scrapper)