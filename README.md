# Web Crawler for Fakebook

This Python script is a web crawler designed to traverse the Fakebook website in search of secret flags. The purpose of the web crawler is to collect five unique secret flags hidden within the Fakebook website.

## Usage

To use the web crawler, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Navigate to Directory**: Open a terminal and navigate to the directory containing the Python script (`webcrawler.py`).

3. **Execute the Script**: Run the Python script using the following command:
   ```bash
   python3 webcrawler.py <username> <password>
Replace <username> and <password> with your Fakebook credentials.

Additionally, you can specify the server and port using the -s and -p options:

python3 webcrawler.py -s <server> -p <port> <username> <password>
Collect Secret Flags: The web crawler will start traversing the Fakebook website, searching for secret flags. Once it discovers five flags, it will print them to the console.
Features
HTTP/1.1 Implementation: The web crawler implements HTTP/1.1 protocol to communicate with the Fakebook server.

TLS/SSL Support: It establishes a TLS-encrypted connection (HTTPS) to ensure secure communication with the Fakebook server.

Login Functionality: The script logs in to Fakebook using the provided username and password via HTTP POST requests.

Cookie Management: It handles cookies properly, storing and sending session cookies with subsequent requests after successful login.

Flag Detection: The crawler searches HTML responses for flags hidden within the Fakebook website. Flags are identified by a specific format.

Parallelism Limitation: Parallelism is limited to five requests at a time to avoid overloading the server, as per the project requirements.

Requirements
Python 3.x
Internet connection (to crawl the Fakebook website)
Disclaimer
This web crawler is provided as an educational tool and should be used responsibly. Excessive crawling or misuse of this tool may violate terms of service or have legal implications. Use it at your own risk.

Feel free to further customize the Markdown README according to your needs.
