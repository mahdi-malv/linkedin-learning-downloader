# LinkedIn Learning Downloader

Asynchronous scraping tool to fetch LinkedIn-learning's courses videos.

Dependencies:
- Python 3.6
- aiohttp
- lxml
- argparse

#### Info

Please use this script for your own purposes.

This script was written for educational usage only.

Make sure your LinkedIn account is **NOT** protected with 2FA

#### Usage
> pip install -r requirements.txt

Edit config.py file (username, password and courses slugs)  

Course's slug can be obtained using its url
e.g:

**COURSE URL**: https://www.linkedin.com/learning/python-advanced-design-pattern <br>
**SLUG**: `python-advanced-design-pattern`

##### Get courses

* Prompt execution permission:
```bash
chmod +x linkedin_learning
```

```groovy
linkedin_learning --user USER --password PASSWORD --courses slug1 slug2
```

To get more help run `./linkedin_learning -h`.
