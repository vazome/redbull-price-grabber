# price-grabber
With this tool you can check goods price on variety of online grocers. A fun project originating from a bet I made with a friend.

Technically it can be used for casual webscrapping and data collection, but the main purpose was monitoring of Red Bull prices.

![image](https://user-images.githubusercontent.com/46573198/148906394-c99bce72-95e1-433a-9a53-178b664030c4.png)

## Prerequisites
- Linux or Windows Subsystem for Linux 2 (WSL 2), `bash` presence
- Python 3
- Script prompts user to check and install the following pip3 packages:
  - BeautifulSoup4
  - Selenium
  - webdriver-manager
## Usage
[Download price-grabber.sh and websites.csv](https://github.com/vazome/price-grabber/releases), set your links and div classes in csv file. For a scrapping protected website edit "url" variable in the script.

macOS - `bash ./price-grabber.sh`

Other - `./price-grabber.sh`

Logs are available under current working directory (where you launch the script) in `redbull-result.log` file

https://user-images.githubusercontent.com/46573198/148727983-e3745679-0aee-443c-aea2-be780673de95.mp4
