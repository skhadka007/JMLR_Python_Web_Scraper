
# JMLR Python Web Scraper
- Web scraper built using Python 3 & the beautifulsoup4 web scraper library.
- Built specifically for The Journal of Machine Learning Research website/publication
	- (https://www.jmlr.org/).
- **CURRENT STATUS:** In progress.
## Installation
Python 3. (https://www.python.org/download/releases/3.0/)
beautifulsoup4 (https://www.crummy.com/software/BeautifulSoup/)
lxml (https://lxml.de/)
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install beautifulsoup4
pip install lxml
pip install requests
pip install unidecode
```

## Usage
- JMLR_scraper_FULL.py  : For the entire scrape.
	- Titles, Abstracts, Abstract URLs, Authors, Keywords, Affiliations, Month of Publication, Volume URL, Journal Name, Year of Publication, Volume List, and Issue List.
- JMLR_scraper_VolumeX_abstract.py: Use to scrape just the abstracts of specific volumes(x).
- JMLR_scraper_VolumeX_abstractURL: Use to scrape just the abstracts URLs of specific volumes.
- Same usage for the rest of rest of the data. 
```python
python JMLR_scraper_FULL.py
```
- Output is written onto csv files in the same directory as the program file:
```
JMLR_Volume_1.csv
JMLR_Volume_2.csv
...
etc.
```

## Contributing
	Created by Santosh Khadka skhadka.code@gmail.com 
Pull requests are welcome. 

## License
[MIT](https://choosealicense.com/licenses/mit/)
