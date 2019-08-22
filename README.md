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

Course's slug can be obtained using its url
e.g:<br>
**COURSE URL**: https://www.linkedin.com/learning/python-advanced-design-pattern <br>
**SLUG**: `python-advanced-design-pattern`

##### Download courses

* Prompt execution permission:
```bash
chmod +x linkedin_learning
```
Run the command:
```groovy
linkedin_learning --user USER --password PASSWORD --courses slug1 slug2
```

To get more help run `./linkedin_learning -h`.

**Note**: `/usr/bin/python` is set. So if you have your python3 at somewhere else like `/usr/bin/python3`, change it.
