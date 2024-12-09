
# Email Crawler

**Email Crawler** is a Python-based script designed to scrape and collect email addresses from a given website. 
It automates the process of finding email addresses by crawling through web pages and filtering relevant URLs. 

---

## Features

- Crawls a website and extracts email addresses.
- Skips unnecessary URLs (e.g., images, videos, and other non-relevant files).
- Filters duplicate emails and maintains a clean list.
- Saves results in a CSV file for easy access.
- Provides logs of processed URLs.

---

## Installation Requirements

### Prerequisites

- **Python 3.7+** must be installed on your system.
- Ensure that `pip` is installed and up to date.

### Required Libraries

The following Python libraries are required to run the script:
- `re`
- `requests`
- `lxml`
- `csv`
- `urllib`

You can install the dependencies by running:

```bash
pip install requests lxml
```

---

## Installation Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/Nambili-Samuel/Email-Crawler.git
    cd EmailCrawler
    ```

2. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the script using the following command:

    ```bash
    python email_crawler.py
    ```

4. Input the website you want to crawl when prompted, or pass the website URL as a command-line argument:

    ```bash
    python email_crawler.py https://example.com
    ```

---

## Usage

1. Run the script and provide the URL of the website you wish to crawl.
2. The script will log progress as it processes URLs and emails.
3. All extracted email addresses will be saved to a CSV file named after the website’s domain (e.g., `example_com.csv`).

---

## Limitations

- The script is not optimized for JavaScript-rendered content. Emails within dynamically loaded content may not be captured.
- Only crawls within the same domain as the input URL.

---

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

---

## Credits

This script was created and enhanced by **Dr. Nambili Samuel**.  

Follow Dr. Nambili Samuel on [LinkedIn](https://www.linkedin.com/in/nambilisamuel/) for updates on projects and research.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

### Sample Output
```
WELCOME TO EMAIL CRAWLER
Please enter a website to crawl for emails: https://example.com
CRAWL: https://example.com
1 Email found: example@example.com
...
```

---

### Support

For issues, questions, or feature requests, open an issue in the repository or contact Dr. Nambili Samuel through LinkedIn: [Dr. Nambili Samuel](https://www.linkedin.com/in/nambilisamuel/).
