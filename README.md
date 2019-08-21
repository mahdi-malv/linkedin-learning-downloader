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
**COURSE URL**: https://www.linkedin.com/learning/python-advanced-design-pattern

**SLUG**: `python-advanced-design-pattern`

##### Get courses

Prompt execution permission:
```bash
chmod +x linkedin_learning
```

If you have set courses in config file:
```bash
./linkedin_learning
```

And alternatively, if you want to set courses using **arguments**:
```bash
# Courses will not be loaded from CONFIG file. Instead it will download argument courses.
./linkedin_learning --courses slug1 slug2 ...
```
